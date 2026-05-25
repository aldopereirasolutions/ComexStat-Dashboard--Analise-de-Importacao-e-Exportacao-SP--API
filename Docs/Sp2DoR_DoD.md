## ✅Critérios de Validação — Sprint 2

## User Story 1

" Como cliente, quero otimizar e padronizar as planilhas iniciais, para garantir que os
dados estejam limpos, consistentes e prontos para análise no dashboard. "

## Critérios de validação:
• O sistema deve validar se todas as colunas obrigatórias das planilhas foram
preenchidas corretamente antes da importação dos dados.

• O sistema deve padronizar automaticamente formatos de dados, como datas,
valores monetários e nomes de campos, garantindo consistência entre as
planilhas.

• O sistema deve identificar e sinalizar dados duplicados, incompletos ou
inconsistentes para correção antes do envio ao dashboard.

• O sistema deve permitir a exportação ou visualização de uma prévia dos dados
tratados, confirmando que as informações estão prontas para análise no
dashboard.

## User Story 2
" Como cliente, quero organizar e criar planilhas segmentadas por tema (importações,
exportações, modais e países), para facilitar o cruzamento de informações e a
construção das análises."

## Critérios de validação:
• O sistema deve permitir a criação de planilhas separadas por categorias
definidas (importações, exportações, modais e países).

• O sistema deve garantir que os dados sejam organizados em estruturas
padronizadas, facilitando o cruzamento de informações entre as planilhas.

• O sistema deve validar se os dados inseridos em cada planilha correspondem
ao tema correto, evitando informações inconsistentes ou fora da categoria.

• O sistema deve possibilitar a integração das planilhas segmentadas com o
dashboard, permitindo análises consolidadas e comparativas.

## User Story 3
" Como cliente, quero visualizar a análise da balança comercial com comparações
entre importações e exportações ao longo do tempo, para identificar tendências,
avaliar o desempenho econômico e apoiar a tomada de decisões estratégicas."

## Critérios de validação:
• O sistema deve apresentar gráficos e indicadores comparativos entre
importações e exportações em diferentes períodos.

• O sistema deve permitir filtros por período, país, modal e categoria de produto
para facilitar análises específicas da balança comercial.

• O sistema deve exibir cálculos automáticos do saldo da balança comercial,
destacando superávit ou déficit em cada período analisado.

• O sistema deve atualizar os dados do dashboard de forma consistente e
organizada, garantindo que as análises reflitam as informações mais recentes
disponíveis.

## User Story 4
" Como cliente, quero identificar os modais de transporte predominantes no estado de
SP, para entender a logística e priorizar investimentos. "

## Critérios de validação:

• O sistema deve apresentar os modais de transporte utilizados no estado de São
Paulo com indicadores de volume e participação percentual.

• O sistema deve permitir a comparação entre diferentes modais de transporte ao
longo do tempo, identificando tendências logísticaas.

• O sistema deve disponibilizar filtros por período, tipo de carga e região do
estado de São Paulo para análises mais detalhadas.

• O sistema deve exibir visualizações gráficas e relatórios que facilitem a
identificação dos modais predominantes e apoiem a tomada de decisão sobre
investimentos.

## User Story 5
"Como cliente, quero filtrar e selecionar produtos específicos dentro da base de
dados, para analisar seu desempenho comercial, identificar tendências e comparar
resultados ao longo do tempo."

## Critérios de validação:
• O sistema deve permitir a busca e seleção de produtos específicos por nome,
categoria ou código dentro da base de dados.

• O sistema deve disponibilizar filtros por período, país, modal e tipo de operação
(importação ou exportação) para análises detalhadas dos produtos.

• O sistema deve apresentar indicadores e gráficos comparativos do
desempenho comercial dos produtos ao longo do tempo.

• O sistema deve atualizar automaticamente os resultados e visualizações
conforme os filtros aplicados, garantindo análises consistentes e precisas.

## User Story 6
"Como cliente, quero visualizar a evolução histórica das importações de SJC por
categoria de produto, para monitorar a dependência de insumos externos e o
crescimento industrial."

## Critérios de validação:
• O sistema deve apresentar a evolução histórica das importações de São José
dos Campos (SJC) segmentadas por categoria de produto.

• O sistema deve permitir filtros por período, categoria e país de origem para
análises detalhadas das importações.

• O sistema deve exibir gráficos e indicadores comparativos que demonstrem o
crescimento ou redução das importações ao longo do tempo.

• O sistema deve atualizar automaticamente os dados e análises no dashboard,
garantindo informações consistentes e confiáveis para monitoramento
industrial.

## 📌Definition of Ready (DoR) – Sprint 2

Antes do início da Sprint 2, todas as User Stories selecionadas devem atender aos
critérios abaixo, garantindo que estejam prontas para desenvolvimento.
Sobre as User Stories:
• Possuem título claro, descrição bem definida e objetivo compreendido

• Estão escritas no formato padrão: “Como cliente, quero..., para...”

• Possuem critérios de validação definidos

• Possuem regras de negócio claras e documentadas

• Estão alinhadas ao escopo do projeto (dados de exportação de São Paulo e
municípios – 2021 a 2026)

• Não possuem dependências bloqueadoras para desenvolvimento

• Foram compreendidas e validadas pelo time

## Sobre os artefatos correlatos às User Stories:
• Dashboard (Power BI) com estrutura inicial definida (layout ou esboço)

• Script base no Google Colab disponível para tratamento dos dados

• Fonte de dados (ComexStat) definida e acessível

• Regras de negócio documentadas (ex: definição de métricas como valor em
dólar)

• Estrutura de versionamento definida no GitHub

• Estratégia de testes definida (validação dos dados e consistência das
informações)

## 📌Definition of Done (DoD) – Sprint 2

A Sprint 1 só pode ser considerada concluída quando atender aos seguintes critérios:
• Dados de importação e exportação dos anos de 2021 a 2026 coletados e
organizados corretamente.

• Tabela de exportação estruturada e validada.

• Tabela de importação estruturada e validada.

• Tratamento e limpeza dos dados realizados no Google Colab.

• Dashboard inicial desenvolvido no Power BI.

• Filtros dos dados de importação e exportação implementados e funcionando corretamente.

• Indicadores de Código NCM, Valor FOB (US$), País de destino e Via de
Transporte exibidos corretamente.

• Mapa das regiões selecionadas implementado e funcional.

• Testes realizados pelos membros da equipe para validação dos dados e
dashboards.

• Backlog da Sprint 2 documentado.

• Repositório GitHub atualizado com os artefatos produzidos na Sprint.

• Atividades da Sprint documentados no relatório parcial do projeto.
