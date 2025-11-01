<h1 align="center">📊 Dashboard Calbon</h1>

---

## 🧠 Sobre o Projeto

O **Dashboard Calbon** foi desenvolvido a partir dos dados de **empresas** e **funcionários** armazenados no banco de dados **SQL da Calbon**.  
Seu objetivo é **gerenciar e analisar informações corporativas e de colaboradores**, apoiando **decisões estratégicas** sobre o futuro da empresa.  

O dashboard é dividido em **duas seções principais** — 🏢 **Empresa** e 👥 **Funcionário** —, possibilitando uma **análise detalhada** de cada contexto.

---

## 🗂️ Tabelas Utilizadas

| Tabela | Descrição |
|:-------|:-----------|
| 🏢 **empresa** | Dados cadastrais das empresas |
| 👨‍💼 **funcionario** | Informações dos colaboradores |
| 📍 **localizacao** | Endereços e estados das empresas |
| 🏭 **setor** | Setor de atuação empresarial |
| 🏷️ **categoria_empresa** | Classificação das empresas |
| 💼 **cargo** | Cargos e funções dos funcionários |

---

## 🏢 Análises — Empresa

| Tipo de Análise | Descrição |
|------------------|------------|
| 📊 **Gráfico de Barras** | Quantidade de empresas por estado |
| 📈 **Gráfico de Área** | Quantidade de empresas por categoria |
| 💬 **Cartão** | Total de empresas cadastradas |
| 🧮 **Tabela Dinâmica** | Empresas divididas por categoria |
| 🗺️ **Mapa** | Localização das empresas no território nacional |

### 🔍 Filtros Disponíveis:
- Categoria da Empresa  
- Nome da Empresa  
- Estado  

---

## 👥 Análises — Funcionário

| Tipo de Análise | Descrição |
|------------------|------------|
| 📈 **Gráfico de Área** | Quantidade de funcionários por cidade |
| 🧾 **Cartões Informativos** | 👔 Total de **gestores** <br> 🧑‍💼 Total de **não gestores** <br> 📊 Percentual de cada grupo <br> 👥 Quantidade **total de funcionários** |
| 🗺️ **Mapa** | Distribuição geográfica dos funcionários |

### 🔍 Filtros Disponíveis:
- Nome do Funcionário  
- Cargo  
- Estado

---

## 🧮 Medidas Presentes

| Medida | 
|------------------|
| 📛 **Quantidade de funcionários Não Gestores** |  
| ✅ **Quantidade de funcionários Gestores** | 
| 📊 **Percentual de funcionários Não Gestores** | 
| 📶 **Percentual de funcionários Gestores** | 

---

<h1 align="center">📊 Dashboard Feira</h1>

---

## 🧠 Sobre o Dashboard

O **Dashboard Feira** foi desenvolvido a partir dos dados da **api** de **mongo** desenvolvida pelo terceiro ano TECH.  
Seu objetivo é **gerenciar e analisar informações relacionadas a notas, visitantes e avaliações**.  

---

## 🗂️ Campos presentes na tabela - **`grades_df`**

| Campo | Descrição |
|:-------|:-----------|
| ✅ **grade_name** | Nome da Categoria a ser avaliada |
| 👨‍💼 **review_id** | ID do avaliador |
| 📝 **score** | Nota da avaliação |
| 🏋️‍♂️ **weight** | Peso da avaliação (o que resulta em nota) |

---

## 🤖 Análises 

| Tipo de Análise | Descrição |
|------------------|------------|
| 📊 **Gráfico de Barras** | Distribuição das avaliações por categoria |
| 📈 **Tabela Dinâmica** | Média de Avaliação por Avaliador |
| 💬 **Cartão** | Média da nota de apresentação do projeto |
| 💬 **Cartão 2** | Média da nota de apresentação do stand |
| 💬 **Cartão 3** | Média da nota de ideia usada |
| 💬 **Cartão 4** | Média da nota de solução desenvolvida |
| 💬 **Cartão 5** | Média geral das notas |
| 💬 **Cartão 6** | Média geral das avaliações |
| 💬 **Cartão 7** | Quantidade de visitas |

### 🔍 Filtros Disponíveis:
- Categoria
- Avaliador por Categoria  

> 💡**Nota:** Avalição e categoria são coisas diferentes, avaliação refere-se a classificação de 1 a 5 que o avaliador deve dar ao visitar o stand nas categorias requisitadas, nota é a avaliação aplicada com o peso que ela vale na nota.

---

## 🧮 Medidas Presentes

| Medida | 
|------------------|
| ✅ **Média da nota de apresentação do projeto** |  
| ⛺ **Média da nota de apresentação do stand** | 
| 📝 **Média da nota de ideia usada** | 
| 💬 **Média da nota de solução desenvolvida** |
| 📶 **Média Geral das Notas** | 
| 📈 **Média Geral das Avaliações** | 

> 💡**Nota:** O peso das avaliações está registrado em cada linha da tabela, mas isso não faz muito sentido, já que todas as avaliações possuem o mesmo peso **0,25**, segundo o terceiro ano TECH. Além disso, essa estrutura dificultava principalmente o cálculo das médias por categoria no BI, pois exigia o uso constante do peso, que está presente **cada linha** . Por isso, o peso passou a ser tratado como uma regra de negócio fixa, sendo aplicado diretamente nas medidas, o que torna o modelo mais simples, consistente e fácil de manter.

---

## 🎨 Paleta de Cores Utilizadas

| Categoria | Cores |
|:--------:|:-----|
| **Tons Azuis** | ![0CACBF](https://img.shields.io/badge/-0CACBF-0CACBF?style=for-the-badge&logoColor=white) ![1199A9](https://img.shields.io/badge/-1199A9-1199A9?style=for-the-badge&logoColor=white) ![007684](https://img.shields.io/badge/-007684-007684?style=for-the-badge&logoColor=white) ![005A65](https://img.shields.io/badge/-005A65-005A65?style=for-the-badge&logoColor=white) ![00353C](https://img.shields.io/badge/-00353C-00353C?style=for-the-badge&logoColor=white) ![00272C](https://img.shields.io/badge/-00272C-00272C?style=for-the-badge&logoColor=white) |
| **Tons Roxos (Mobile)** | ![9B84EC](https://img.shields.io/badge/-9B84EC-9B84EC?style=for-the-badge&logoColor=white) ![2C0532](https://img.shields.io/badge/-2C0532-2C0532?style=for-the-badge&logoColor=white) |
| **Tons Brancos** | ![FFFFFF](https://img.shields.io/badge/-FFFFFF-FFFFFF?style=for-the-badge&logoColor=black) |
| **Tons Pretos** | ![07101C](https://img.shields.io/badge/-07101C-07101C?style=for-the-badge&logoColor=white) ![000000](https://img.shields.io/badge/-000000-000000?style=for-the-badge&logoColor=white) |

> 🎨 **Nota:** Os tons roxos são utilizados somente na versão mobile do dashboard devido ao layout de dashboard para mobile no figma.

---

## 🔗 Links Importantes

📐 [**Design no Figma**](https://www.figma.com/design/Qf8O3BndHIXPBJQ8RGorik/Calbon?node-id=1-2&p=f&t=KmgTbgTImpu7Fm83-0)  
📊 [**Dashboard Calbon Público no Power BI**](https://app.powerbi.com/view?r=eyJrIjoiNWJiMWMzNmQtNGFjYi00MTU3LWI4NzgtNmRhY2RiMGQ5ZThkIiwidCI6ImIxNDhmMTRjLTIzOTctNDAyYy1hYjZhLTFiNDcxMTE3N2FjMCJ9)
📶 [**Dashboard Feira Público no Power BI**](https://app.powerbi.com/view?r=eyJrIjoiNDZiMTE1MzAtN2VmYS00MDA0LWE5MTAtMzNiMDQxNzc5ZGUwIiwidCI6ImIxNDhmMTRjLTIzOTctNDAyYy1hYjZhLTFiNDcxMTE3N2FjMCJ9)

---

## ⚖️ Licença

Este projeto está sob a licença [**MIT**](https://choosealicense.com/licenses/mit/).  
Sinta-se livre para **usar, modificar e compartilhar** com os devidos créditos. 💙

---

<h3 align="center">✨ Desenvolvido para a Calbon — dados que impulsionam decisões inteligentes 📈</h3>
