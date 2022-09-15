# Projetos de estudo em Jupyter Notebooks
* Preparando o ambiente de trabalho
    * Instalação do Jupyter-Lab
    * Ambiente virtual
* Atividades 
    * Curso de Fundamentos de ETL com Python - DIO
        *  CENIPA

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


#