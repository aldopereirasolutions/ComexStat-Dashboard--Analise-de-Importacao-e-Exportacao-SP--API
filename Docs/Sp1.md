## ✅ Critérios de Validação — Sprint 1

### 🔹 User Story 1
**Como cliente, quero selecionar países, para analisar dados de exportação por região.**

**Critérios de validação:**
- O sistema deve apresentar uma lista de países disponíveis para seleção.
- Deve ser possível selecionar um ou mais países simultaneamente.
- Ao selecionar um país, os dados exibidos no dashboard devem ser atualizados automaticamente.
- Os dados exibidos devem corresponder apenas aos países selecionados.
- Deve existir uma forma clara de limpar os filtros aplicados.

---

### 🔹 User Story 2
**Como cliente, quero visualizar os municípios que realizam exportação, para entender a participação regional.**

**Critérios de validação:**
- O dashboard deve exibir uma lista ou visualização dos municípios exportadores.
- Apenas municípios com registro de exportação devem ser apresentados.
- Os municípios devem estar corretamente nomeados e sem duplicidade.
- A visualização deve permitir identificação clara de cada município.
- Os dados devem respeitar os filtros aplicados (ex: país, ano).

---

### 🔹 User Story 3
**Como cliente, quero visualizar a soma dos valores em dólar, para entender o volume financeiro do comércio exterior.**

**Critérios de validação:**
- O sistema deve calcular automaticamente a soma total dos valores de exportação.
- O valor deve ser exibido em dólar (USD).
- A soma deve ser atualizada conforme filtros aplicados.
- O valor exibido deve ser consistente com os dados da base.
- Deve haver clareza visual (ex: destaque ou card principal).

---

### 🔹 User Story 4
**Como cliente, quero visualizar os produtos exportados, para identificar os principais itens comercializados.**

**Critérios de validação:**
- O dashboard deve listar ou representar os produtos exportados.
- Os produtos devem estar identificados por nome ou código (NCM).
- Deve ser possível visualizar os produtos mais exportados.
- A visualização deve permitir comparação entre produtos.
- Os dados devem ser atualizados conforme filtros aplicados.

---

### 🔹 User Story 5
**"Como cliente, quero selecionar o ano dos dados, para analisar a evolução ao longo do tempo."**

**Critérios de validação:**
- O sistema deve permitir selecionar o ano (2021 ou 2022).
- Apenas um ano pode ser selecionado por vez (ou múltiplos, se definido).
- Ao alterar o ano, todos os dados do dashboard devem ser atualizados.
- Os dados exibidos devem corresponder exatamente ao período selecionado.
- Deve haver indicação clara do ano ativo.

---

### 🔹 User Story 6
**"Como cliente, quero visualizar os tipos de vias (aérea e marítima), para analisar como os produtos são transportados."**

**Critérios de validação:**
- O dashboard deve exibir os modais de transporte utilizados.
- Deve haver distinção clara entre via aérea e marítima.
- Os dados devem mostrar volume ou quantidade por tipo de via.
- A visualização deve permitir comparação entre os modais.
- Os dados devem respeitar os filtros aplicados.

---

### 🔹 User Story 7
**"Como cliente, quero visualizar os locais de destino das mercadorias, para entender os fluxos logísticos."**

**Critérios de validação:**
- O sistema deve apresentar os países ou regiões de destino das exportações.
- Os destinos devem estar corretamente identificados.
- Deve ser possível visualizar os principais destinos.
- A visualização deve permitir análise de distribuição geográfica.
- Os dados devem ser atualizados conforme filtros aplicados.

## DoR Sprint 1:
## 📌 Definition of Ready (DoR) – Sprint 1

Antes do início da Sprint 1, todas as User Stories selecionadas devem atender aos critérios abaixo, garantindo que estejam prontas para desenvolvimento.

**Sobre as User Stories:**
- [ ] Possuem título claro, descrição bem definida e objetivo compreendido
- [ ] Estão escritas no formato padrão: “Como cliente, quero..., para...”
- [ ] Possuem critérios de validação definidos
- [ ] Possuem regras de negócio claras e documentadas
- [ ] Estão alinhadas ao escopo do projeto (dados de exportação de São Paulo e municípios – 2021 e 2022)
- [ ] Não possuem dependências bloqueadoras para desenvolvimento
- [ ] Foram compreendidas e validadas pelo time

**Sobre os artefatos correlatos às User Stories:**
- [ ] Dashboard (Power BI) com estrutura inicial definida (layout ou esboço)
- [ ] Script base no Google Colab disponível para tratamento dos dados
- [ ] Fonte de dados (ComexStat) definida e acessível
- [ ] Tabela de municípios do IBGE disponível para integração
- [ ] Regras de negócio documentadas (ex: definição de métricas como valor em dólar)
- [ ] Estrutura de versionamento definida no GitHub
- [ ] Estratégia de testes definida (validação dos dados e consistência das informações)

## DoD da Sprint 1:

## 📌 Definition of Ready (DoR) – Sprint 1

Antes do início da Sprint 1, todas as User Stories selecionadas devem atender aos critérios abaixo, garantindo que estejam prontas para desenvolvimento.

**Sobre as User Stories:**
- [ ] Possuem título claro, descrição bem definida e objetivo compreendido
- [ ] Estão escritas no formato padrão: “Como cliente, quero..., para...”
- [ ] Possuem critérios de validação definidos
- [ ] Possuem regras de negócio claras e documentadas
- [ ] Estão alinhadas ao escopo do projeto (dados de exportação de São Paulo e municípios – 2021 e 2022)
- [ ] Não possuem dependências bloqueadoras para desenvolvimento
- [ ] Foram compreendidas e validadas pelo time

**Sobre os artefatos correlatos às User Stories**:
- [ ] Dashboard (Power BI) com estrutura inicial definida (layout ou esboço)
- [ ] Script base no Google Colab disponível para tratamento dos dados
- [ ] Fonte de dados (ComexStat) definida e acessível
- [ ] Tabela de municípios do IBGE disponível para integração
- [ ] Regras de negócio documentadas (ex: definição de métricas como valor em dólar)
- [ ] Estrutura de versionamento definida no GitHub
- [ ] Estratégia de testes definida (validação dos dados e consistência das informações)
