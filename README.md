# LH_CD_PEDROLOPES
Desafio Técnico da Indicium - Ciência de Dados.

LightHouse Ciência de Dados
Introdução
Desafio da Indicium para o programa LightHouse na trilha de Ciência de Dados.

O objetivo deste repositório, será desenvolver experimentos do dataset desafio_indicium_imdb.csv, para compreender sobre a sua estrutura, limpar, aplicar análise exploratória, técnicas de NLP, engenharia de features, preparar os dados para treinamento e criar/treinar um modelo de Machine Learning com sckit-learn.

Estrutura do Projeto
```
LightHouse-DataScience/
├── data/
│   └── desafio_indicium_imdb.csv       # Dataset do desafio
├── notebooks/          
│   └── LH_CD_PEDROLOPES.ipynb          # notebook com experimentos
│   └── imdb_rating_model.pkl           # Modelo de regressão
├── .gitignore                          # impede upload de arquivos locais ao git
├── requirements.txt                    # documento para instalar as bibliotecas
└── README.md
```
Instalação
Certifique-se de instalar essas ferramentas nas versões descritas ou superiores:

Python 3.11 (ou superior)
Git 2.51 (ou superior)
VSCode 1.103.2 (ou superior)
Extensões do VSCode:
- Jupyter Notebook

1. Clonando e acessando
Clone este repositório via terminal após abrir o cmd dos passos anteriores:

```bash
# Clone do repo
git clone https://github.com/PLeonLopes/LH_CD_PEDROLOPES.git

# Acessando pasta
cd LH_CD_PEDROLOPES

# Abrir o projeto no VSCode
code .
```
2. Ambiente Virtual e bibliotecas
Ao abrir o VSCode com os passos anteriores, tecle CTRL + J para acessar o terminal pelo VSCode.

Em seguida, crie um ambiente virtual e instale as bibliotecas python através do requirements.txt:

```bash
# Criar o ambiente
python -m venv .venv

# Acessar o ambiente
.\.venv\Scripts\activate

# instalar os pacotes necessários
pip install -r requirements.txt
```
Acessando o projeto
Finalizada a instalação, acesse o notebook em `notebooks/LH_CD_PEDROLOPES.ipynb` e conecte o kernel `.venv` após iniciar a primeira célula do notebook. Após isso, iniciar as demais células para rodar todo o projeto.
