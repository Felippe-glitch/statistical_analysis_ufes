<div align="center">

# 📊 Statistical Analysis UFES

**Análise Estatística e Predição da Velocidade de Onda de Pulso (VOP)**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-green?style=for-the-badge)

</div>

---

## 📝 Sobre o Projeto
Este repositório armazena os códigos desenvolvidos durante minha **Iniciação Científica na UFES**. 
O foco central é a análise estatística e a aplicação de equações para o estudo de predição da **Velocidade de Onda de Pulso (VOP)** em diferentes populações.

> **Nota:** Este é um repositório de trabalho (lab notebook). Futuramente, um repositório formal será criado para a publicação da equação de regressão final.

---

## 📁 Estrutura do Repositório

| Arquivo | Tipo | Descrição |
| :--- | :---: | :--- |
| `inferential_statistics.py` | 🐍 Script | **Análises estatísticas inferenciais.**<br>Inclui comparações entre populações para variáveis numéricas e categóricas (ANOVA, Qui-quadrado, testes par a par e ajustes para múltiplas comparações). |
| `avaliacao_desempenho_equacoes_preditivas_vop.ipynb` | 📓 Notebook | **Avaliação de modelos preditivos de VOP.**<br>Aplica equações da UFES e da Europa, calcula métricas de desempenho (R², RMSE, ICC) e gera gráficos de comparação entre valores reais e preditos. |
| `analise_residuos_equacoes.ipynb` | 📓 Notebook | **Análise de resíduos dos modelos.**<br>Gera gráficos de dispersão e distribuição dos erros para avaliar viés, variabilidade e adequação das equações preditivas. |

---

## 💻 Tecnologias e Bibliotecas
As seguintes ferramentas foram fundamentais para a análise de dados:

* ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white) **Manipulação de Dados**
* ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white) **Computação Numérica**
* ![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) **Cálculos Científicos**
* ![Statsmodels](https://img.shields.io/badge/-Statsmodels-blue?style=flat-square) **Modelagem Estatística**
* ![Sklearn](https://img.shields.io/badge/-Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) **Métricas de Erro**

---

## 🚀 Como Executar no PyCharm

Para rodar os scripts e notebooks localmente utilizando o PyCharm, siga estas etapas:

### 1. Preparação do Ambiente
1. **Abrir o Projeto:** No PyCharm, vá em `File > Open` e selecione a pasta raiz deste repositório.
2. **Configurar o Interpretador:** - Vá em `Settings` (Ctrl+Alt+S) > `Project: Statistical-Analysis-UFES` > `Python Interpreter`.
   - Clique em `Add Interpreter` > `New Virtualenv Environment`. Certifique-se de usar o **Python 3.8 ou superior**.

### 2. Instalação de Dependências
Abra o **Terminal** integrado do PyCharm (barra inferior) e execute o comando abaixo para instalar as bibliotecas necessárias:
```bash
pip install pandas numpy scipy statsmodels scikit-learn openpyxl
