### Relatório Técnico – Sprint 1

## 1. Contextualização da Sprint

A Sprint 1 teve como objetivo a construção da base funcional do sistema de análise de dados de exportação do estado de São Paulo e seus municípios, considerando exclusivamente o período de 2021 e 2022. O foco principal foi disponibilizar as primeiras funcionalidades de exploração e visualização de dados, garantindo valor imediato ao usuário final.

A definição do escopo priorizou funcionalidades essenciais que permitissem ao cliente interagir com os dados sem necessidade de manipulação técnica direta, alinhando-se ao conceito de entrega incremental do framework Scrum.

---

## 2. Objetivos da Sprint

- Disponibilizar visualizações iniciais de dados de exportação
- Permitir filtragem básica por dimensões relevantes (país, município, ano, produto)
- Apresentar métricas agregadas de valor financeiro
- Introduzir análises logísticas iniciais (vias de transporte e destinos)

A Sprint foi estruturada para garantir que, ao final, o sistema já pudesse ser utilizado para análises exploratórias reais.

---

## 3. User Stories da Sprint 1

As User Stories foram definidas seguindo o padrão:

Como <tipo de usuário>, quero <funcionalidade>, para <valor de negócio>

Foi mantido o tipo de usuário "cliente", conforme definição do projeto.

**Lista de User Stories:**

1. Como cliente, quero selecionar países, para analisar dados de exportação por região.
2. Como cliente, quero visualizar os municípios que realizam exportação, para entender a participação regional.
3. Como cliente, quero visualizar a soma dos valores em dólar, para entender o volume financeiro do comércio exterior.
4. Como cliente, quero visualizar os produtos exportados, para identificar os principais itens comercializados.
5. Como cliente, quero selecionar o ano dos dados, para analisar a evolução ao longo do tempo.
6. Como cliente, quero visualizar os tipos de vias (aérea e marítima), para analisar como os produtos são transportados.
7. Como cliente, quero visualizar os locais de destino das mercadorias, para entender os fluxos logísticos.

---

## 4. Processo de Definição das User Stories

As User Stories foram elaboradas com base nos seguintes critérios:

- Identificação das necessidades principais de análise de dados de exportação
- Priorização de funcionalidades que agregam valor imediato ao usuário
- Uso de linguagem simples e orientada ao negócio
- Foco em funcionalidades independentes e entregáveis dentro de uma única Sprint

A escolha das funcionalidades considerou o fluxo natural de análise de dados, iniciando por filtros básicos e evoluindo para visualizações mais analíticas.

---

## 5. Critérios de Validação das User Stories

Os critérios de validação foram definidos para garantir que cada User Story seja mensurável e verificável ao final da Sprint, conforme o conceito de "Confirmação" dos 3Cs.

A definição seguiu os seguintes princípios:

- Clareza: cada critério descreve exatamente o comportamento esperado
- Testabilidade: deve ser possível validar de forma objetiva
- Orientação ao usuário: valida se a funcionalidade atende ao valor proposto

Critérios por User Story

User Story 1

- Deve existir um filtro de seleção de países
- A seleção deve atualizar os dados exibidos no dashboard
- O sistema deve permitir seleção de um ou múltiplos países

User Story 2

- O dashboard deve exibir os municípios que realizam exportação
- Os municípios devem ser apresentados de forma organizada (tabela, gráfico ou mapa)
- Deve refletir corretamente os dados filtrados

User Story 3

- Deve ser exibida a soma total dos valores de exportação em dólar
- O valor deve ser atualizado conforme filtros aplicados
- O cálculo deve considerar apenas o período de 2021 e 2022

User Story 4

- Deve existir visualização dos produtos exportados
- Os produtos devem ser agrupados por categoria (ex: NCM)
- Deve ser possível identificar os principais produtos

User Story 5

- Deve existir filtro de seleção por ano
- O usuário deve poder alternar entre 2021 e 2022
- As visualizações devem ser atualizadas conforme o ano selecionado

User Story 6

- Deve ser exibida a divisão por tipo de via (aérea e marítima)
- Os dados devem refletir corretamente o volume de exportação por modal
- A visualização deve permitir comparação entre os tipos

User Story 7

- Deve ser exibido o destino das exportações
- Os dados devem apresentar os principais países ou regiões de destino
- Deve ser possível identificar padrões logísticos

---

## 6. Justificativa de Priorização

As User Stories da Sprint 1 foram classificadas como alta e média prioridade com base no valor de negócio entregue.

Critérios utilizados:

- Impacto direto na análise de dados
- Frequência de uso esperada
- Dependência para funcionalidades futuras

As funcionalidades de filtro (país e ano) e métricas principais (valor total e produtos) foram priorizadas por serem essenciais para qualquer análise. Já as funcionalidades logísticas foram classificadas como média prioridade por agregarem valor analítico adicional, mas não serem críticas para uso inicial.

---

## 7. Aderência ao Modelo INVEST

As User Stories foram avaliadas conforme os critérios INVEST:

- Independent: cada funcionalidade pode ser implementada separadamente
- Negotiable: detalhes podem ser ajustados durante a Sprint
- Valuable: todas entregam valor direto ao cliente
- Estimable: possuem escopo claro para planejamento
- Small: são implementáveis dentro da Sprint 1
- Testable: possuem critérios de validação definidos

---

## 8. Resultado Esperado da Sprint

Ao final da Sprint 1, espera-se que o sistema permita:

- Exploração básica dos dados de exportação
- Visualização de métricas principais
- Aplicação de filtros fundamentais
- Análise inicial de padrões comerciais e logísticos

O produto resultante já deve ser utilizável para tomada de decisão preliminar, mesmo que funcionalidades mais avançadas ainda não estejam disponíveis.

---

## 9. Considerações Finais

A Sprint 1 foi estruturada para maximizar entrega de valor com o menor nível de complexidade possível. A abordagem adotada permite que o sistema seja evoluído incrementalmente nas próximas Sprints, mantendo sempre um produto funcional.

A definição clara das User Stories e seus critérios de validação garante alinhamento entre desenvolvimento e necessidade do cliente, reduzindo retrabalho e aumentando a qualidade das entregas.
