# Análise de ROI em Marketing: Modelo Preditivo para Otimização de Investimentos

## 🎯 Visão Geral do Projeto

Este projeto de Data Science foi desenvolvido para resolver um desafio central da área de marketing: **como alocar o orçamento de publicidade para maximizar o retorno sobre o investimento (ROI)?**

Utilizando um conjunto de dados de gastos com publicidade e resultados de vendas, foi construído um modelo de regressão linear capaz de prever o aumento de vendas com base nos investimentos em diversos canais de mídia. O resultado final é uma ferramenta analítica que não apenas prevê resultados com alta precisão, mas também fornece insights claros sobre quais canais são mais eficazes, orientando decisões estratégicas baseadas em dados.

---

## 📂 Estrutura do Repositório

* `Analise_ROI.ipynb`: Notebook Jupyter contendo todo o fluxo da análise, incluindo:
    * Limpeza e preparação dos dados.
    * Análise exploratória e visualização (Matriz de Correlação).
    * Construção, treinamento e avaliação do modelo de Regressão Linear.
    * Interpretação dos resultados e análise de ROI.
* `Gastos_Publicidade_MelhoresCompras.csv`: O conjunto de dados original utilizado para o treinamento e teste do modelo.
* `README.md`: Este documento, com a documentação completa do projeto.

---

## 🛠️ Ferramentas e Bibliotecas

* **Linguagem:** Python
* **Bibliotecas Principais:**
    * `pandas`: Para manipulação e limpeza dos dados.
    * `scikit-learn`: Para a construção do modelo de Regressão Linear e avaliação de métricas.
    * `seaborn` & `matplotlib`: Para a criação de visualizações, como a matriz de correlação.

---

## 📊 Principais Resultados e Insights

### Performance do Modelo

O modelo de regressão desenvolvido demonstrou um desempenho excelente, alcançando um **Coeficiente de Determinação (R²) de 0.95**. Isso significa que **95% da variação no aumento das vendas pode ser explicada pelos investimentos em publicidade**, confirmando a alta precisão e confiabilidade do modelo para fins preditivos.

### Análise de Retorno Sobre o Investimento (ROI)

A análise dos coeficientes do modelo revelou o impacto de cada real gasto nos diferentes canais de mídia, resultando no seguinte ranking de eficiência:

| Posição | Canal de Mídia    | Retorno por R$ 1,00 Gasto (Aumento em Unidades de Venda) | Categoria de ROI |
| :-----: | ----------------- | :------------------------------------------------------: | :--------------: |
|   🥇 1º   | **Google** |                        **~32 unidades** |   **Excelente** |
|   🥈 2º   | **Instagram** |                        **~27 unidades** |   **Excelente** |
|   🥉 3º   | **Páginas Web** |                        **~13 unidades** |      **Bom** |
|    4º     | **Revista** |                        **~11 unidades** |      **Bom** |
|    5º     | **Rádio** |                        **~10 unidades** |    **Moderado** |
|    6º     | **Jornal** |                         **~9 unidades** |    **Moderado** |
|    7º     | **Redes Sociais (Geral)** |                         **~9 unidades** |      **Baixo** |
|    8º     | **TV** |                         **~7 unidades** |      **Baixo** |

### Conclusão Estratégica

A análise indica uma clara oportunidade para otimização do orçamento de marketing. Canais digitais como **Google e Instagram oferecem um retorno significativamente superior** aos canais mais tradicionais. A recomendação estratégica é **realocar progressivamente os investimentos dos canais de baixo desempenho (como TV e Redes Sociais genéricas) para os canais de alto desempenho**, visando maximizar o volume total de vendas sem necessariamente aumentar o orçamento geral.

---

## 🚀 Como Executar o Projeto Localmente

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
    ```
2.  **Navegue até o diretório:**
    ```bash
    cd nome-do-repositorio
    ```
3.  **Instale as dependências:**
    ```bash
    pip install pandas scikit-learn seaborn matplotlib
    ```
4.  **Execute o Notebook:**
    Abra o arquivo `Analise_ROI.ipynb` em um ambiente como Jupyter Notebook ou Google Colab e execute as células em sequência.
