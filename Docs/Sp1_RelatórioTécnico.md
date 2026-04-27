### Relatório Técnico Sprint 1.

Projeto: Plataforma de Análise de Comércio Exterior dos Municípios do Estado de São Paulo


---

**1. Contextualização do Projeto:**

O projeto foi desenvolvido com base na necessidade de análise estruturada dos dados de comércio exterior dos municípios do estado de São Paulo, utilizando como fonte principal os dados abertos disponibilizados pelo Ministério do Desenvolvimento, Indústria, Comércio e Serviços, por meio do sistema COMEXSTAT.

A motivação do projeto está diretamente relacionada à dificuldade de acesso, interpretação e análise dos dados de exportação, que se encontram dispersos e pouco organizados para uso prático. Esse cenário dificulta a identificação de padrões logísticos, análise de desempenho municipal e apoio à tomada de decisão estratégica.

Dessa forma, a Sprint 1 teve como objetivo estruturar a base inicial do sistema e validar a proposta por meio de um Produto Mínimo Viável.


---

**2. Definição do Objetivo do MVP**

O MVP foi definido como a primeira versão funcional da solução, com escopo reduzido, focada exclusivamente na validação da ideia central do projeto.

O objetivo do MVP é validar a capacidade de análise e visualização de dados de comércio exterior no estado de São Paulo e seus municípios.

A definição desse objetivo foi realizada com base na necessidade de testar rapidamente a viabilidade da solução antes de expandir o sistema para funcionalidades mais complexas, como integração web e análise completa de todos os municípios.


---

**3. Definição do Problema:**

O problema foi definido a partir da análise do cenário atual de uso de dados públicos de comércio exterior.

Foi identificado que as informações sobre exportação estão dispersas, com baixa padronização e difícil interpretação, o que gera os seguintes impactos:

- Dificuldade na análise de desempenho dos municípios

- Alto tempo de processamento manual de dados

- Baixa eficiência na geração de insights estratégicos

- Limitações na comparação entre regiões


A definição do problema orientou diretamente o escopo do MVP, garantindo foco na organização e visualização dos dados.


---

**4. Definição da Hipótese:**

A hipótese do projeto foi definida como:

Se os dados de comércio exterior forem organizados, filtrados e apresentados de forma visual e interativa utilizando o Power BI, será possível identificar padrões relevantes de exportação e facilitar análises estratégicas.

Essa hipótese foi construída com base no princípio de que a visualização de dados melhora significativamente a capacidade de interpretação e tomada de decisão.


---

**5. Definição do Valor Entregue:**

O valor do MVP foi definido com foco no usuário final e nos benefícios diretos da solução.

O MVP entrega um painel interativo contendo dados filtrados de exportação dos anos de 2021 e 2022 dos municípios do estado de São Paulo.

As funcionalidades entregues permitem:

- Visualização dos fluxos de exportação

- Identificação de produtos por código NCM

- Análise de valor FOB (US$)

- Identificação de países de destino

- Análise das vias e modais de transporte

- Visualização geográfica dos municípios


A definição do valor foi baseada na necessidade de fornecer uma solução prática, mesmo com escopo reduzido.


---

**6. Definição da Solução Técnica:**

A solução foi definida com base em três pilares principais:

- Tratamento de dados

- Estruturação das informações

- Visualização interativa


Para o tratamento dos dados foi utilizado o Google Colab, devido à sua facilidade de uso, integração com Python e capacidade de manipulação de grandes volumes de dados.

O processo incluiu:

- Importação dos dados do COMEXSTAT

- Limpeza dos dados (remoção de inconsistências e padronização)

- Seleção dos campos relevantes

- Filtragem por período (2021 e 2022)

- Organização em tabelas estruturadas


Após o tratamento, os dados foram exportados para utilização no Power BI.


---

**7. Estruturação das Tabelas:**

As tabelas foram definidas com base nas variáveis necessárias para atender às histórias de usuário.

Foi criada uma tabela principal de exportações contendo:

- Código NCM

- Valor FOB (US$)

- País de destino

- Via de transporte

- Município

- Ano


A definição dessas colunas foi baseada nas perguntas de análise do projeto, especialmente relacionadas à logística e fluxo de mercadorias.


---

**8. Desenvolvimento do Dashboard:**

O dashboard foi desenvolvido no Power BI com foco em usabilidade e validação da hipótese.

Foram implementados:

- Gráficos de distribuição de exportação

- Indicadores de valor total exportado

- Segmentações por ano

- Filtros por país e município

- Visualização geográfica


A escolha do Power BI se deu pela sua capacidade de integração com dados estruturados e facilidade de criação de dashboards interativos.


---

**9. Definição das Personas:**

As personas foram definidas com base nos usuários que mais se beneficiariam da solução.

Analista Institucional de Dados (CADI): responsável por analisar o desempenho dos municípios. Necessita de dados organizados e visualizações eficientes para reduzir o tempo de análise.

Estudante/Pesquisador: utiliza os dados para fins acadêmicos. Necessita de dados estruturados e confiáveis para desenvolvimento de estudos.

Analista de Logística: responsável por entender modais e rotas. Necessita de dados claros sobre transporte e fluxo de mercadorias.

A definição das personas orientou diretamente as funcionalidades do MVP.


---

**10. Definição das Histórias de Usuário:**

As histórias de usuário foram definidas utilizando a estrutura padrão ágil:

- “Como [usuário], quero [funcionalidade], para [objetivo]”.

- A priorização foi realizada com base no impacto para validação do MVP.

- Histórias de alta prioridade foram escolhidas por serem essenciais para validar a hipótese, incluindo:

- Seleção de países

- Visualização de municípios

- Análise de valores em dólar

- Identificação de produtos

- Filtro por ano


Histórias de média prioridade foram incluídas para enriquecer a análise:

- Visualização de vias de transporte

- Identificação de destinos



---

**11. Definição dos Critérios de Aceitação:**

Os critérios de aceitação foram definidos para garantir que cada história de usuário fosse considerada concluída apenas quando atendesse requisitos mínimos.

Os principais critérios definidos foram:

- O usuário deve conseguir visualizar dados por município

- O usuário deve conseguir filtrar dados por período

- Os dados devem estar estruturados corretamente em tabelas

- O dashboard deve apresentar visualização clara e interativa


Esses critérios foram definidos com base na necessidade de validar a hipótese do projeto.


---

**12. Execução da Sprint 1:**

A Sprint 1 foi executada seguindo o processo ágil com as seguintes etapas:

- Definição do backlog

- Priorização das tarefas

- Desenvolvimento das tabelas

- Tratamento dos dados

- Construção do dashboard

- Testes internos


As entregas principais foram:

- Tabela de exportações estruturada

- Dados tratados do COMEXSTAT

- Dashboard funcional no Power BI



---

**13. Métricas de Validação:**

A validação do MVP foi realizada por meio de testes internos com membros da equipe.

Número de usuários que testaram: 2

Os testes foram realizados por Luiz Augusto (Scrum Master) e Felipe Borges (Team Member).


Os feedbacks indicaram:

- Facilidade de uso dos filtros

- Clareza das visualizações

- Boa organização dos dados



---

**14. Resultados Obtidos:**

Os principais resultados da Sprint 1 foram:

- Estruturação eficiente dos dados de exportação

- Redução da complexidade de análise

- Geração de insights iniciais sobre padrões de exportação

- Validação da hipótese de uso de dashboards



---

**15. Limitações Identificadas:**

As limitações do MVP foram definidas de forma intencional para manter o escopo reduzido:

- Análise restrita a exportações

- Período limitado a 2021 e 2022

- Ausência de sistema web

- Dependência do Power BI para visualização



---

**16. Conclusão da Sprint 1:**

A Sprint 1 cumpriu seu objetivo ao validar a viabilidade da solução proposta.

Foi possível comprovar que a organização e visualização dos dados de comércio exterior permitem uma análise mais eficiente e acessível.

O MVP demonstrou que mesmo com um escopo reduzido é possível gerar valor ao usuário e validar a hipótese central do projeto.

A partir dessa base, o projeto poderá evoluir para incluir novas funcionalidades, expansão de dados e desenvolvimento de uma plataforma completa.
