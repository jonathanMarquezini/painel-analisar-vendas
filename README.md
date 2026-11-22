# 📈 Sales Analytics 360

Projeto de inteligência comercial desenvolvido no **Power BI** a partir de **banco de dados**, estruturado em cinco visões integradas para acompanhar desempenho de vendas, evolução temporal, catálogo de produtos, base de clientes e performance da força de vendas.

---

## 🎯 Objetivo do Projeto

Oferecer uma visão completa e dinâmica da operação comercial para responder a perguntas estratégicas:
- Como está o faturamento total, o ticket médio e o crescimento frente aos períodos anteriores?
- Qual é a sazonalidade mensal e trimestral entre os anos analisados?
- Quais produtos, categorias e marcas concentram a maior receita?
- Como se distribui a receita entre clientes PF e PJ, regiões e faixas de concentração?
- Qual é a performance individual e por equipe dos vendedores?

---

## 🛠️ Arquitetura e Ferramentas

- **Banco de Dados & SQL:** extração, junção e preparação dos dados comerciais na origem.
- **Power BI & DAX:** modelagem relacional, métricas temporais (*Ano Anterior / LY*, *MoM %*, *YTD vs LY %*) e construção dos painéis interativos.
- **Abas do relatório:** **Visão Geral**, **Análise Temporal**, **Produtos**, **Clientes** e **Vendedores**.

---

## 🖥️ Estrutura do Dashboard

### 1. Visão Geral
Painel executivo com os principais indicadores consolidados:
- **KPIs:** Faturamento Total de **R$ 582,28 Mi**, Faturamento YTD de **$209,03 Mi** *(conforme cartão exibido no painel)*, Crescimento de **56,00%** e Ticket Médio de **R$ 291,14 Mil**.
- **Marcas:** **Gamma** lidera com **R$ 208,41 Mi (35,79%)**, seguida por **Alpha** com **R$ 191,66 Mi (32,91%)** e **Beta** com **R$ 182,22 Mi (31,29%)**.
- **Visuais:** evolução mensal comparando atual vs. ano anterior, mapa regional de vendas e faturamento por marca.

### 2. Análise Temporal
Foco na evolução cronológica, sazonalidade e variação entre períodos:
- **KPIs:** Faturamento Total de **R$ 582,28 Mi**, Faturamento Mês Anterior de **R$ 567,75 Mi**, Evolução MoM de **2,56%** e Crescimento YTD vs. LY de **10,09%**.
- **Trimestres e evolução:** faturamento por trimestre (*Qtr 1* a *Qtr 4*, variando de **R$ 151,74 Mi** a **R$ 142,15 Mi**), matriz mensal comparativa (2023, 2024 e 2025) e linha de evolução mês a mês.

### 3. Produtos
Avaliação do portfólio de **20 produtos** e categorias:
- **KPIs:** **20** produtos vendidos, Ticket Médio de **R$ 291,14 Mil**, **Produto 9** como destaque de faturamento (**R$ 35,97 Mi**).
- **Categorias:** **Móveis** lidera com **R$ 159,10 Mi**, seguido por **Acessórios** (**R$ 97,70 Mi**) e **Eletrônicos** (**R$ 63,98 Mi**).
- **Visuais:** mapa de desempenho por marca (*Alpha*, *Beta* e *Gamma*), ranking Top 10 produtos por faturamento e faturamento por categoria.

### 4. Clientes
Análise da carteira de **50 clientes**, perfil e distribuição geográfica:
- **KPIs:** **50** clientes, Receita Média por Cliente de **R$ 11,65 Mi**, **Cliente 45** como destaque com **R$ 17,04 Mi** no cartão de destaque.
- **Perfil e regiões:** divisão entre **PJ (27 / 54%)** e **PF (23 / 46%)**, além de faturamento por estado liderado por **PR (R$ 145,06 Mi)**, **SP (R$ 73,09 Mi)**, **MG (R$ 51,90 Mi)** e **RJ (R$ 50,72 Mi)**.
- **Visuais:** concentração da receita (*Top 5 vs. Demais*), perfil PF x PJ, ranking por cliente e faturamento por estado.

### 5. Vendedores
Acompanhamento de **10 vendedores** e equipes comerciais:
- **KPIs:** **10** vendedores, Ticket Médio Geral dos Vendedores de **R$ 58,23 Mi**, **Vendedor 10** como destaque com **R$ 67,85 Mi**.
- **Equipes e ranking:** comparação entre **Equipe A (R$ 162,88 Mi)** e **Equipe B (R$ 157,89 Mi)**, mapa de desempenho, barras de vendas por vendedor e tabela detalhada com faturamento, quantidade vendida e ticket médio.

---

## 💡 Principais Observações do Painel

- A receita total acumulada no período alcança **R$ 582,28 Mi**, com **Equipe A** (**R$ 162,88 Mi**) e **Equipe B** (**R$ 157,89 Mi**) em disputa próxima[cite: 14, 18].
- Entre as categorias de produto, **Móveis** (**R$ 159,10 Mi**) concentra a maior fatia frente a *Acessórios* e *Eletrônicos*[cite: 16].
- Na carteira de clientes, **PJ** representa **54%** da base (**27 clientes**) contra **46% PF** (**23 clientes**), com forte concentração regional no **PR** e em **SP**[cite: 17].

---

## 📂 Como Abrir o Arquivo

1. Baixe o arquivo `.pbix` deste repositório.
2. Abra no **Power BI Desktop**.
3. Utilize os filtros laterais para explorar os períodos, categorias, clientes e vendedores.
