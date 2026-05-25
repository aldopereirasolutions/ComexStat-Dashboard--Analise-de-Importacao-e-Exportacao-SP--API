## Relatório Técnico Sprint 2. 

 

## 2. Definição do Objetivo do MVP 2 

O MVP foi definido como uma versão melhorada da solução, com escopo maior, com foco no aprimoramento dos dados já coletados anteriormente no projeto. 

O objetivo do MVP 2 é ampliar e aprimorar a plataforma de BI desenvolvida na Sprint 1, expandindo as análises de comércio exterior dos municípios do estado de São Paulo por meio de dashboards mais completos e interativos. 

A definição desse objetivo foi realizada com base na necessidade de melhorar os dashboards para que contenham funcionalidades mais complexas, como integração web e análise completa de todos os municípios. 

 
## 3. Definição do Problema: 

O problema foi definido a partir da análise do cenário atual de uso de dados públicos de comércio exterior. 

Atualmente, os dados de importação e exportação encontram-se dispersos e com baixa padronização visual, dificultando análises comparativas, identificação de tendências econômicas e interpretação de indicadores logísticos dos municípios paulistas. 

A definição do problema orientou diretamente o escopo do MVP, garantindo foco na organização e visualização dos dados. 

 
## 4. Definição da Hipótese: 

A hipótese da sprint 2 foi definida como: 

Se os dashboards forem ampliados com novos indicadores, filtros por municípios e dados atualizados de importação e exportação, será possível realizar análises mais detalhadas e eficientes, facilitando a interpretação dos dados e apoiando a tomada de decisão. Essa hipótese foi construída com base no princípio de que a visualização de dados melhora significativamente a capacidade de interpretação e tomada de decisão. 

 
## 5. Definição do Valor Entregue: 

O valor do MVP 2 foi definido com foco no usuário final e nos benefícios diretos da solução. 

O MVP entrega um painel interativo contendo dados filtrados de exportação dos anos de 2021 até 2026 dos municípios do estado de São Paulo. 

As funcionalidades entregues permitem: 

- Visualização dos fluxos de exportação 

- Visualização dos fluxos de importação 

- Identificação de produtos por código NCM 

- Análise de valor FOB (US$) 

- Identificação de países de destino 

- Análise das vias e modais de transporte 

- Visualização geográfica dos municípios 

- A definição do valor foi baseada na necessidade de fornecer uma solução prática, de escopo maior. 

 
## 6. Definição da Solução Técnica: 

- A solução foi definida com base em sete pilares principais: 

- Expansão dos dashboards de exportação (2021 a 2026); 

- Criação de dashboards de importação; 

- Filtros por municípios do estado de São Paulo; 

## Visualização de: 

- Valor FOB; 

- Valor de frete; 

- Valor de seguro; 

- Produtos importados; 

- Países de origem; 

- Quantidade estatística; 

- Mês; 

- Produto; 

- Organização e melhoria visual dos dashboards; 

 

Para o tratamento dos dados foi utilizado o Google Colab, devido à sua facilidade de uso, integração com Python e capacidade de manipulação de grandes volumes de dados. 

O processo incluiu: 

-Importação dos dados do COMEXSTAT 

-Limpeza dos dados (remoção de inconsistências e padronização) 

-Seleção dos campos relevantes 

-Filtragem por período (2021 a 2026) 

-Organização em tabelas estruturadas 

Após o tratamento, os dados foram exportados para utilização no Power BI. 


## 7. Estruturação das Tabelas: 

As tabelas foram definidas com base nas variáveis necessárias para atender às histórias de usuário. 

Foi criada uma tabela principal de exportações contendo: 

-Código NCM 

-Valor FOB (US$) 

-País de destino 

-Via de transporte 

-Município 

-Ano 

-Mês 

-produto 

A definição dessas colunas foi baseada nas perguntas de análise do projeto, especialmente relacionadas à logística e fluxo de mercadorias. 

 
## 8. Desenvolvimento do Dashboard: 

O dashboard foi desenvolvido no Power BI com foco em usabilidade e validação da hipótese. 

Foram implementados: 

-Gráficos de distribuição de importação 

-Indicadores de valor total importado 

-Segmentações por mês 

-Filtros por produto 

 
## 9. Definição das Personas: 

As personas foram definidas com base nos usuários que mais se beneficiariam da solução. 

Analista Institucional de Dados (CADI): responsável por analisar o desempenho dos municípios. Necessita de dados organizados e visualizações eficientes para reduzir o tempo de análise. 

Estudante/Pesquisador: utiliza os dados para fins acadêmicos. Necessita de dados estruturados e confiáveis para desenvolvimento de estudos. 

Analista de Logística: responsável por entender modais e rotas. Necessita de dados claros sobre transporte e fluxo de mercadorias. 

A definição das personas orientou diretamente as funcionalidades do MVP 2. 

 

## 10. Definição das Histórias de Usuário: 

As histórias de usuário foram definidas utilizando a estrutura padrão ágil: 

## “Como [usuário], quero [funcionalidade], para [objetivo]”. 

A priorização foi realizada com base no impacto para validação do MVP 2. 

 

Histórias de alta prioridade foram escolhidas por serem essenciais para validar a hipótese, incluindo: 

- Otimização e padronização das planilhas iniciais; 

- Novas planilhas segmentadas por tema (importações, exportações, modais e países); 

- A análise da balança comercial com comparações entre importações e exportações; 

 

Histórias de média prioridade foram incluídas para enriquecer a análise de: 

- Identificação dos modais de transporte predominantes no estado de SP; 

- Filtros e seleção de produtos específicos dentro da base de dados; 

- Visualização da evolução histórica das importações de SJC por categoria de produto; 

 
## 11. Definição dos Critérios de Aceitação: 

Os critérios de aceitação foram definidos para garantir que cada história de usuário fosse considerada concluída apenas quando atendesse requisitos mínimos. 

Os principais critérios definidos foram: 

-O MVP deve permitir que o usuário visualize e análise dados de importação e exportação por municípios do estado de São Paulo utilizando dashboards interativos e filtros dinâmicos. 

-O sistema deve registrar os dados de comércio exterior organizados em tabelas estruturadas, garantindo clareza e consistência das informações apresentadas. 

Métricas coletadas: 

-Tempo de resposta dos dashboards; 

-Taxa de utilização dos filtros; 

-Tempo médio de navegação; 

-Número de análises realizadas; 

-Desempenho no carregamento das visualizações. 

 

Esses critérios foram definidos com base na necessidade de validar a hipótese da sprint 2. 

 
## 12. Execução da Sprint 2: 

A Sprint 2 foi executada seguindo o processo ágil com as seguintes etapas: 

-Definição do backlog da sprint 

-Priorização das tarefas 

-Desenvolvimento das tabelas 

-Tratamento dos dados 

-Construção do dashboard 

-Testes internos 

As entregas principais foram: 

-Tabela de importações e exportações estruturada 

-Dados tratados do COMEXSTAT 

-Dashboard funcional no Power BI 


## 13. Métricas de Validação: 

A validação do MVP 2 foi realizada por meio de testes internos com membros da equipe. 

Número de usuários que testaram: 2 

Os testes foram realizados por Luiz Augusto (Scrum Master) e Rita Carolina (Team Member). 

Os feedbacks indicaram: 

-clareza das informações; 

-melhoria dos filtros; 

-oportunidades de melhoria; 

 

## 14. Resultados Obtidos: 

Os principais resultados da Sprint 2 foram: 

-Redução do tempo de análise de dados; 

-Aumento da eficiência na tomada de decisão; 

-Melhoria na visualização e interpretação das informações; 

-Apoio na identificação de oportunidades no comércio exterior; 

-Redução de custos operacionais com análise manual de dados; 

-Otimização dos custos logísticos; 

-Implementação dos dados de importação. 

 
## 15. Limitações Identificadas: 

As limitações do MVP 2 foram; 

-Plataforma ainda limitada ao Power BI; 

-Dependência de tratamento manual dos dados; 

-Plataforma web ainda não implementada; 

-Algumas análises avançadas ainda não foram adicionadas. 

 
## 16. Conclusão da Sprint 2: 

A Sprint 2 cumpriu seu objetivo ao validar as melhorias propostas. 

Foi possível comprovar que a organização e visualização dos dados de comércio exterior permitem uma análise mais eficiente e acessível. 

A partir deste ponto, o projeto poderá evoluir para incluir novas funcionalidades, expansão de dados e desenvolvimento de uma plataforma completa, além da inclusão da plataforma digital. 
