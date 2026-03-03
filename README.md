# 💸 App de Organização Financeira da Claudia com Vibe Coding

PRD refinado no Copilot Web

```
# PRD – App Porquinho (versão enxuta)

## 1. Visão Geral

O Porquinho é um aplicativo mobile de controle financeiro pessoal focado em simplicidade, rapidez e baixo esforço cognitivo. O app permite que usuários registrem gastos e receitas do dia a dia em poucos segundos, entendam onde estão gastando (categorias) e como estão pagando (meio de pagamento). O app também sugere automaticamente a categoria do gasto para reduzir fricção, mantendo sempre a possibilidade de correção pelo usuário.

## 2. Problema a ser Resolvido

Muitas pessoas querem controlar seus gastos, mas desistem por falta de tempo, excesso de complexidade e jornadas longas em aplicativos financeiros. Além disso, é comum não ter clareza sobre:

- Para onde o dinheiro está indo (categorias)
- Como as despesas estão sendo pagas (dinheiro, PIX, cartão)

O Porquinho busca resolver essas dores oferecendo registro rápido, visualizações simples e insights básicos, sem exigir conhecimento financeiro.

## 3. Objetivos do Produto

Objetivo principal:

- Ajudar pessoas a controlar gastos e receitas do dia a dia, identificando gargalos e oportunidades de economia de forma simples e prática.

Objetivos secundários:

- Criar hábito diário de registro financeiro
- Reduzir fricção no registro (principalmente na escolha de categoria)
- Aumentar consciência sobre o uso de meios de pagamento
- Entregar clareza com o mínimo de passos possível
 

## 4. Usuários

Perfil:
- Pessoas físicas
- Sem conhecimento financeiro avançado
- Interessadas em controlar gastos do dia a dia de forma prática e rápida

Frequência:

- Uso diário, com possibilidade de múltiplos registros por dia

## 5. Escopo do Produto

Dentro do escopo:

- Registro rápido de gastos
- Registro de receitas
- Seleção de meio de pagamento (Dinheiro, PIX, Cartão de crédito, Cartão de débito)
- Sugestão automática de categoria (assistida e editável)
- Resumo financeiro por período
- Análise por categoria
- Análise por meio de pagamento
- Insights simples e compreensíveis

Fora do escopo (nesta fase):

- Integração com bancos/cartões
- Planejamento financeiro avançado
- Investimentos
- Multiusuário/contas compartilhadas
- Relatórios sofisticados e configurações complexas

## 6. Requisitos Funcionais

RF01 – Registro de gastos

- O usuário deve conseguir registrar um gasto informando, no mínimo: valor, data, categoria e meio de pagamento.
- A descrição do gasto é opcional, mas recomendada para melhorar a sugestão automática de categoria.

RF02 – Seleção de meio de pagamento

- O usuário deve selecionar o meio de pagamento da despesa com opções pré-definidas:
  - Dinheiro
  - PIX
  - Cartão de crédito
  - Cartão de débito
- A seleção deve exigir o mínimo de toques possível.

RF03 – Registro de receitas

- O usuário deve conseguir registrar receitas (entradas) de forma simples (valor e data; tipo opcional).

RF04 – Visualização de resumo financeiro

- O app deve exibir resumo simples de gastos e receitas por período (ex.: diário, semanal, mensal), com totais e saldo simples. 

RF05 – Análise por categoria

- O app deve permitir visualizar gastos agrupados por categoria, destacando as categorias com maior impacto.
 
RF06 – Análise por meio de pagamento

- O app deve permitir visualizar e analisar os gastos agrupados por meio de pagamento (valores e/ou percentuais por Dinheiro, PIX, Crédito e Débito).

RF07 – Insights automáticos

- O app deve apresentar insights curtos e compreensíveis com base nos dados registrados (ex.: “A maior parte dos gastos do mês foi no cartão de crédito”).
- Os insights devem evitar termos técnicos e manter foco em ações simples.

RF08 – Sugestão automática de categoria (assistida)

- Ao registrar uma despesa, o app deve sugerir automaticamente uma categoria com base em:
  - texto informado na descrição (quando houver) e/ou
  - histórico de escolhas do usuário (últimas categorias usadas para descrições semelhantes ou padrão do usuário).
- O usuário deve conseguir aceitar a sugestão com 1 toque ou alterar facilmente.
- Se não houver confiança suficiente na sugestão, o app pode sugerir “Outros” ou a última categoria utilizada.

## 7. Requisitos Não Funcionais

- Usabilidade: interface simples e intuitiva; poucos cliques; fluxo de registro rápido.
- Performance: resposta rápida em registro e visualizações.
- Segurança e privacidade: proteção dos dados do usuário e aderência à LGPD (princípios de minimização e transparência).
- Compatibilidade: aplicativo mobile (Android e/ou iOS).

## 8. Métricas de Sucesso (iniciais/sugeridas)

- Retenção de 7 e 30 dias
- Média de registros de despesas por usuário/dia
- Percentual de gastos com meio de pagamento informado
- Taxa de aceitação da sugestão automática de categoria (aceitou vs. alterou)
- Tempo médio para registrar um gasto
- Feedback qualitativo sobre simplicidade e utilidade (ex.: “me ajudou a entender meus gastos?”)

## 9. Dependências e Riscos

Dependências:
- Definição de UX/UI focada em simplicidade
- Definição de categorias padrão e regras iniciais de sugestão (palavras-chave e/ou histórico)

Riscos:
- Sugestões de categoria com baixa precisão gerarem frustração
- Aumento de fricção no registro por excesso de campos/opções
- Insights pouco claros ou pouco acionáveis
- Falta de diferenciação caso a experiência não seja realmente mais simples

## 10. Critérios de Aceite
- O usuário consegue registrar um gasto em poucos segundos.
- O meio de pagamento é selecionável com facilidade e clareza.
- A sugestão automática de categoria aparece e pode ser alterada rapidamente.
- O usuário consegue visualizar gastos por categoria e por meio de pagamento de forma simples.
- A experiência geral do app permanece prática, com baixo esforço e sem complexidade desnecessária.


```

- Prints ou pequenos vídeos das interações com a IA;
  Crie um protótipo de app mobile chamado “Porquinho”, focado em controle financeiro pessoal simples e rápido.

 
<img width="1298" height="585" alt="image" src="https://github.com/user-attachments/assets/87a51c0b-5091-4825-94e0-572d7b721dde" />




 


- Um resumo do que o seu **App de Finanças Pessoais** faz;
  O Porquinho é um aplicativo mobile de controle financeiro pessoal focado em simplicidade, rapidez e baixo esforço cognitivo. O app permite que usuários registrem gastos e receitas do dia a dia em poucos segundos, entendam onde estão gastando (categorias) e como estão pagando (meio de pagamento). O app também sugere automaticamente a categoria do gasto para reduzir fricção, mantendo sempre a possibilidade de correção pelo usuário.
  
## reflexão sobre o processo:
###  - O que funcionou bem?  
  tudo funcionou bem. usar o copilot web previamnte e fazer todos os ajustes por la, é uma ótima ideia. Os ajustes são fáceis e rápidos de serem feitos.
### - o que não funcionou como o esperado?
a versao gratuita tem poucas possibilidaes de interação.

## - O que aprendeu sobre conversar com IAs?
  - Foi simples e objetivo.Basta ter clareza do que se quer e conversar normalmente com um amigo. Precisa de detalhes e clareza nas informações.
  - 



