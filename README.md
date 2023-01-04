# Projetos de estudo em Jupyter Notebooks
* Preparando o ambiente de trabalho
    * Instalação do Jupyter-Lab
    * Ambiente virtual
* Atividades 
    * [Curso de Fundamentos de ETL com Python - DIO](https://github.com/JoseWRPereira/jupyter-lab/blob/489b29eba52958c7c5833faf159fb6dcfa7fdb6e/DIO/cenipa.ipynb)
        *  CENIPA
    * [Curso de Visualiação de Dados com Python - Coursera/IBM](https://github.com/JoseWRPereira/jupyter-lab/blob/1d87cae21f95f6417f7c20d893289ee04ef60d65/Coursera-IBM/data_visualization.ipynb)
#

# Preparando o ambiente de trabalho


## Instalação do Jupyter-Lab
```bash
# Instalação utilizando o pip
sudo pip install jupyter-lab

# Instanciando o servidor 
jupyter-lab

# Parando a execução do servidor
#   No terminal de execução, digite Ctrl+C 
```
Fonte: [Jupyter-lab](https://jupyter.org/install)


## Ambiente virtual

```bash
# install virtual environment
python3 -m venv pylab-venv

# install requirements
pip3 install -r requirements.txt

# load virtual environment
source pylab-venv/bin/activate

# freeze requirements
pip3 freeze > requirements.txt
```

## Editor 
VSCode + Extensão: Jupyter (Microsoft)


# Atividades 

## Curso de Fundamentos de ETL com Python - DIO
ETL - *Extract, Transform and Load*

Extração > Validação > Limpeza > Transformação > Carregamento


Fonte de dados: [CENIPA](https://dados.gov.br/dataset/ocorrencias-aeronauticas-da-aviacao-civil-brasileira) - Base de dados de ocorrências aeronáuticas.


## Curso de Visualiação de Dados com Python - Coursera/IBM


## Como estudar? [Seja um Data Scientist](https://youtu.be/VlYDWOfiFuc)

### Planejamento
* Em quanto tempo quero estar preparado? 
* Linha do tempo
* O que preciso saber para estar pronto para aplicar para vaga de Data Scientist?
* Definir um tempo de estudo diário

### Vídeos introdutórios
* [Como Estudar Ciência de dados - Seja um Data Scientist](https://youtu.be/2g7TBUDkDhM)
* [Como eu aprendo Machine Learning? - Seja um Data Scientist](https://youtu.be/wuQC9YUvXes)

### Etapas de estudo
* Dados
* Linguagem de programação - Python
* Modelos de Machine Learning
* Visualização de dados e Storytelling
* SQL


* Estudos de caso (Ex: House Rocket)
    * Elaborar perguntas sobre o caso e tentar responder com Manipulação e Análise de dados
    * Manipulação de dados
        * Biblioteca Pandas:
            * Selecionar colunas
            * Filtrar linhas
            * Agregação (group by)
            * Funções apply lambda
            * União de dados (Merge, concat)
    * Análise de dados
        * Bibliotecas Seaborn e Matplolib
            * Gráficos
            * Correlações
            * Validações

