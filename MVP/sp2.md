# 📌 MVP - Aldo Pereira Solutions.

## 🎯 Objetivo do MVP
O MVP (Produto Mínimo Viável) da Sprint 2 tem como objetivo ampliar e aprimorar a plataforma de BI desenvolvida na Sprint 1, expandindo as análises de comércio exterior dos municípios do estado de São Paulo por meio de dashboards mais completos e interativos.

- **Problema a ser resolvido:** 
Atualmente, os dados de importação e exportação encontram-se dispersos e com baixa padronização visual, dificultando análises comparativas, identificação de tendências econômicas e interpretação de indicadores logísticos dos municípios paulistas.

- **Hipótese a ser validada:** Se os dashboards forem ampliados com novos indicadores, filtros por municípios e dados atualizados de importação e exportação, será possível realizar análises mais detalhadas e eficientes, facilitando a interpretação dos dados e apoiando a tomada de decisão.

- **Valor entregue:** O MVP entrega dashboards interativos contendo informações de comércio exterior entre 2021 e 2026, permitindo visualizar produtos exportados, países de destino, modais de transporte utilizados, quantidade estatística, peso líquido das cargas, mapa de visualização, rank de via por valor FOB e a porcentagem de participação dos produtos.

---

## 📝 Descrição da Solução
Nesta sprint, será realizada a continuidade do projeto iniciado anteriormente, com melhorias estruturais e visuais nos dashboards existentes, além da ampliação da base de dados utilizada nas análises.

Os dashboards passam a incluir informações de 2021 a 2026, incorporando filtros por municípios, produtos SH4, países exportados, anos, meses, modais de transporte, etc.

**Funcionalidades principais incluídas:**

### Dashboard de Exportação

- Mapa de localização do Estado de São Paulo;
- Soma do Valor FOB em dólar;
- Total de produtos exportados;
- Mapa de visualização dos países exportados;
- Gráfico de participação dos produtos em porcentagem;
- Tabela de vias e seus totais de movimentações.

#### Filtros

- Municípios;
- Produtos em SH4;
- Países exportados;
- Ano (2021 a 2026);
- Mês.

### Dashboard de Importação

- Soma do valor em dólar;
- Quantidade estatística;
- Peso total líquido dos produtos (KG);
- Número total de operações;
- Mapa de localização do Estado de São Paulo;
- Soma do valor de frete;
- Ranking das vias por Valor FOB;
- Evolução do Valor FOB por ano.

#### Filtros

- Ano;
- Mês;
- Municípios;
- País;
- Modais de transporte (via);
- Produtos.


**Limitações conhecidas:**

- Plataforma ainda limitada ao Power BI;
- Dependência de tratamento manual dos dados;
- Ausência de análises preditivas e projeções futuras;
- Algumas análises avançadas ainda não foram adicionadas.

**Escopo reduzido:**

- Expansão dos dashboards de exportação para o período de 2021 a 2026;
- Desenvolvimento dos dashboards de importação;
- Implementação de filtros por municípios, produtos, países e períodos;
- Inclusão de indicadores logísticos e econômicos;
- Melhoria visual e estrutural das análises.

---

## 👥 Personas / Usuários-Alvo

## 👥 Persona 1: Analista Institucional de Dados (CADI)
Profissional responsável por acompanhar o desempenho econômico e comercial dos municípios do estado de São Paulo.

- **Necessidades:**
Necessita analisar grandes volumes de dados de comércio exterior para identificar padrões, tendências e comparações regionais. Entretanto, enfrenta dificuldades devido à falta de organização e padronização das informações.

- **Dores atendidas:**
O MVP disponibiliza dashboards organizados e filtros por municípios, permitindo análises mais rápidas, comparações eficientes e melhor interpretação dos indicadores econômicos.
    
## 👥 Persona 2: Estudante/Pesquisador
Usuário acadêmico que realiza pesquisas relacionadas à logística, economia e comércio exterior.

- **Necessidades:**
Precisa acessar dados estruturados e confiáveis para desenvolvimento de estudos e análises exploratórias, reduzindo o tempo gasto com coleta e tratamento manual das informações.

- **Dores atendidas:**
O MVP oferece uma base de dados organizada e dashboards interativos, facilitando análises acadêmicas e interpretação de padrões comerciais.

## 👥 Persona 3: Analista de Logística
Profissional responsável pelo planejamento e análise das operações logísticas e comerciais.

- **Necessidades:** Busca compreender custos logísticos, países envolvidos nas operações comerciais e produtos movimentados, porém enfrenta dificuldades devido à falta de visualização integrada dessas informações.

- **Dores atendidas:** O MVP disponibiliza dashboards específicos de importação contendo indicadores logísticos, custos de transporte, produtos importados e quantidade estatística, facilitando análises operacionais.
 

---

## 🔑 User Stories (Backlog do MVP)
| Rank | Prioridade | User Story (Sprint 2) | Sprint |
|------|------------|----------------------|--------|
| 1 | Alta | Como cliente, quero otimizar e padronizar as planilhas iniciais, para garantir que os dados estejam limpos, consistentes e prontos para análise no dashboard. | 2 |
| 2 | Alta | Como cliente, quero organizar e criar novas planilhas segmentadas por tema (importações, exportações, modais e países), para facilitar o cruzamento de informações e a construção das análises. | 2 |
| 3 | Alta | Como cliente, quero visualizar a análise da balança comercial com comparações entre importações e exportações ao longo do tempo, para identificar tendências, avaliar o desempenho econômico e apoiar a tomada de decisões estratégicas. | 2 |
| 4 | Média | Como cliente, quero identificar os modais de transporte predominantes no estado de SP, para entender a logística e priorizar investimentos. | 2 |
| 5 | Média | Como cliente, quero filtrar e selecionar produtos específicos dentro da base de dados, para analisar seu desempenho comercial, identificar tendências e comparar resultados ao longo do tempo. | 2 |
| 6 | Média | Como cliente, quero visualizar a evolução histórica das importações de SJC por categoria de produto, para monitorar a dependência de insumos externos e o crescimento industrial. | 2 |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Tabelas de exportação, Desenvolvimento inicial do dashboard no Power BI, Filtro de dados para São Paulo.                        | Concluído|
| 02     | Expansão dos dashboards, dashboards de importação, filtros por municípios e melhorias organizacionais.                           | Concluído |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário visualize e analise dados de importação e exportação por municípios do estado de São Paulo utilizando dashboards interativos e filtros dinâmicos.
- O sistema deve registrar os dados de comércio exterior organizados em tabelas estruturadas, garantindo clareza e consistência das informações apresentadas.
- Métricas coletadas:
  - Tempo de resposta dos dashboards;
  - Taxa de utilização dos filtros;
  - Tempo médio de navegação;
  - Número de análises realizadas;
  - Desempenho no carregamento das visualizações.


---

## 📈 Métricas de Validação
## **Número de usuários que testaram o MVP:**

Os testes foram realizados por membros da equipe, sendo:

* Luiz Augusto (Scrum Master - SM);
* Rita Carolina (Team Member - TM).
 
## **Feedback qualitativo (positivo/negativo):**

Os feedbacks foram positivos em relação à organização dos dashboards, clareza das informações e melhoria dos filtros. Também foram destacadas oportunidades de melhoria relacionadas aos tipos de filtros que poderiam ser incluídos.
    
## **Indicadores de negócio:**
- Redução do tempo de análise de dados;
- Aumento da eficiência na tomada de decisão;
- Melhoria na visualização e interpretação das informações;
- Apoio na identificação de oportunidades no comércio exterior;
- Redução de custos operacionais com análise manual de dados;
- Otimização dos custos logísticos.

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências

- Prints de tela:

<img width="877" height="490" alt="WhatsApp Image 2026-05-23 at 17 31 02 (1)" src="https://github.com/user-attachments/assets/92efb3b7-7011-437e-96da-bb09c4a879c2" />

<img width="1290" height="736" alt="WhatsApp Image 2026-05-22 at 15 49 56 (1)" src="https://github.com/user-attachments/assets/b5f211ef-aa28-416b-bc33-cd44596525e4" />
    
- Fluxos ou protótipos: https://drive.google.com/drive/folders/1cyFB0D47e_sD2grL4PLvKERHOpEPR9hu?usp=drive_link

- Vídeo (MVP):   
