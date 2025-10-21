# 🧾 Análise de Vendas — Produtos mais Vendidos por Quantidade e Receita

## 📌 Descrição do Projeto
Este projeto tem como objetivo analisar dados de vendas para identificar **os produtos mais vendidos** tanto por **quantidade** quanto por **receita total**, além de explorar padrões de **sazonalidade** e **distribuição geográfica** das vendas.

A análise foi realizada em **Python**, utilizando bibliotecas amplamente usadas em **Ciência de Dados** como **Pandas**, **NumPy**, **Matplotlib** e **Seaborn**, dentro de um ambiente **Jupyter Notebook**.

---

## 🎯 Objetivos da Análise
- Identificar os **top produtos** com maior volume de vendas e maior receita.  
- Analisar o **desempenho por estado e cidade**, avaliando os principais mercados.  
- Investigar a **tendência mensal de vendas** e possíveis padrões sazonais.  
- Obter **insights estratégicos** para tomada de decisão (estoque, marketing, precificação).

---

## ⚙️ Etapas da Metodologia

1. **Importação e inspeção dos dados**  
   - Leitura da base de dados (Excel/CSV).  
   - Visualização inicial com `df.head()` e verificação de tipos de dados (`df.info()`).

2. **Tratamento e limpeza**  
   - Remoção de colunas desnecessárias.  
   - Padronização de nomes de colunas.  
   - Conversão de colunas de data (`ORDERDATE`) para o formato datetime.  
   - Verificação de valores ausentes e duplicados.

3. **Análise exploratória (EDA)**  
   - Agrupamento por `PRODUCTLINE` e cálculo de:
     - Quantidade total (`sum(QUANTITYORDERED)`)
     - Receita total (`sum(SALES)`)
   - Ordenação decrescente dos resultados para identificar os produtos de maior destaque.  
   - Visualizações com **gráficos de barras e linhas** para representar quantidades e receitas.

4. **Análises complementares**
   - Vendas por **Estado** e **Cidade**.  
   - Tendência de vendas por **mês** e **ano** (colunas `MONTH_ID` e `YEAR_ID`).  
   - Cálculo de **percentual de participação** de cada produto ou região sobre o total.  

5. **Visualização de dados**
   - Gráficos criados com `Matplotlib` e `Seaborn`:  
     - Barras para produtos mais vendidos.  
     - Linhas para evolução mensal.  
     - Gráficos comparativos por região.

---

## 📊 Principais Resultados

| Métrica | Descrição |
|----------|------------|
| **Produtos mais vendidos** | As categorias com maior quantidade de pedidos incluem *Classic Cars* e *Motorcycles*. |
| **Maior receita** | Linhas de produtos como *Classic Cars* e *Vintage Cars* geram a maior receita total. |
| **Cidades com maior volume de vendas** | As vendas se concentram em grandes centros urbanos, com destaque para cidades norte-americanas. |
| **Estados líderes em faturamento** | A análise estadual mostra concentração em poucos estados com grandes volumes. |
| **Tendência mensal** | Há picos de vendas nos meses correspondentes ao 3º e 4º trimestre, sugerindo sazonalidade. |



---


---

## 🧠 Conclusão
A análise permite compreender o comportamento de vendas por produto, região e tempo, oferecendo subsídios para decisões estratégicas.  
A utilização de **Python e suas bibliotecas de análise de dados** mostrou-se eficiente para gerar visualizações claras e insights de negócio relevantes.

---

## 💻 Tecnologias Utilizadas
| Categoria | Ferramentas |
|------------|--------------|
| Linguagem | Python |
| Análise de dados | Pandas, NumPy |
| Visualização | Matplotlib, Seaborn |
| Ambiente | Jupyter Notebook |
| Exportação | Excel / CSV |

---
