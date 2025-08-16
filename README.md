# 📊 Projeto de Precificação de Imóveis com Regressão Linear
## 🛠️ Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-3A7AB1?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)

## 🏠 Sobre o Projeto
Análise preditiva de preços de imóveis utilizando **Regressão Linear**, explorando correlações entre características dos imóveis e seus valores de mercado. Baseado em dataset inspirado na compilação [House Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) do Kaggle.

## 🔍 Variáveis Analisadas
| Variável | Descrição |
|----------|-----------|
| `area_primeiro_andar` | Área construída do 1º andar (m²) |
| `existe_segundo_andar` | Indicador binário (0/1) |
| `area_segundo_andar` | Área construída do 2º andar (m²) |
| `quantidade_banheiros` | Número total de banheiros |
| `capacidade_carros_garagem` | Vagas na garagem |
| `qualidade_da_cozinha_Excelente` | Indicador de cozinha excelente (0/1) |
| `preco_de_venda` | **Variável alvo** (R$) |

## 📈 Metodologia
1. **Análise Exploratória**
   - Correlação entre variáveis (Pearson)
   - Identificação de features mais relevantes

2. **Modelagem Preditiva**
   - Regressão Linear
   - Avaliação de métricas de desempenho
   - Interpretação dos coeficientes

3. **Visualização**
   - Gráficos de dispersão
   - Análise de resíduos

## 📊 Resultados Principais
- ![Scikit-learn](https://img.shields.io/badge/R²-0.64-blue) Score do modelo
- ![Pandas](https://img.shields.io/badge/Correlação-0.74-brightgreen) entre área e preço
- ![Python](https://img.shields.io/badge/MAE-R$10000-yellow) Erro absoluto médio

## 🚀 Como Executar
```bash
git clone https://github.com/revilojakie/precificacao-imoveis.git
cd precificacao-imoveis
jupyter notebook Projeto_final_Precos_de_Imoveis_Regressao_Linear.ipynb
