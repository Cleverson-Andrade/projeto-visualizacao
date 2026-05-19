# Projeto Prático – Visualização da Informação 📊
> **Análise Mercadológica e Produtiva: Evolução do Preço do Milho, Produtividade Agrícola e Relação Cambial (2021 - 2025)**

Este repositório contém o projeto prático desenvolvido para a disciplina de **Visualização da Informação** do curso de **Ciência de Dados** da **Cruzeiro do Sul Virtual**. 

O objetivo principal é aplicar técnicas computacionais avançadas em Python para estruturar dados numéricos e gerar visualizações estísticas limpas, culminando na exportação automática de um relatório técnico em formato PDF.

---

## 👨‍💻 Informações do Estudante
* **Nome:** Cleverson Moura Andrade
* **Instituição:** Cruzeiro do Sul Virtual
* **Curso:** Ciência de Dados

---

## 📊 Estrutura e Unidades de Visualização

O script gera automaticamente três tipos de representações visuais fundamentais, respeitando as boas práticas de design e adequação de dados:

1. **Plot 1: Análise Temporal de Preços (Unidade: R$)**
   * *Tipo:* Linha Contínua (Série Temporal)
   * *Descrição:* Ideal para o monitoramento de tendências históricas e flutuações de preços da saca de milho ao longo das safras.
2. **Plot 2: Rendimento Físico por Safra (Unidade: Sacas / ha)**
   * *Tipo:* Barras Verticais (Discreto)
   * *Descrição:* Permite a comparação direta e imediata do volume total de produtividade entre períodos fechados.
3. **Plot 3: Correlação Macroeconômica (Unidade: Proporção USD/BRL)**
   * *Tipo:* Gráfico de Dispersão (*Scatter Plot*) com Regressão Linear
   * *Descrição:* Avalia o grau de dependência matemática e impacto da taxa de câmbio (Dólar) frente ao preço doméstico da commodity.

---

## 📂 Arquivos do Repositório

* `projeto_visualizacao_dados.py`: Código-fonte Python responsável pela carga dos dados, plotagem dos gráficos e compilação nativa do relatório.
* `USD_BRL_hist.csv`: Base de dados real contendo o histórico de cotações diárias para cruzamento de indicadores.

---

## 🛠️ Tecnologias e Como Rodar o Projeto

### Pré-requisitos
Certifica-te de ter o Python instalado na tua máquina junto com as bibliotecas necessárias. Podes instalá-las executando:

```bash
pip install pandas matplotlib seaborn reportlab
