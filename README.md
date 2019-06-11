## Jupyter Notebook

Para executar os Notebook's é necessário a instalação do Jupyter Notebook no computador do usuário, Try Jupyter na web ou pelo Colaboratory da Google.

* [Try Jupyter](https://jupyter.org/try)
* [Colaboratory](https://colab.research.google.com/)

### Instalação do Jupyter Notebook

Há duas maneiras de instalarmos o Jupyter Notebook no computador, uma delas é através da [Distribuição Anaconda](https://docs.anaconda.com/anaconda/install/) e outra diretamente pelo terminal. Ao instalar a Distribuição, o Jupyter Notebook, já está pronto para ser executado.

Tendo o Python3 ou uma versão mais atual do Python use : 
```console
(<nome_do_ambiente>) user@computer:~$ python3 -m pip install --upgrade pip 
(<nome_do_ambiente>) user@computer:~$ python3 -m pip install jupyter
```
Caso tenha o Python2 use :
```console
(<nome_do_ambiente>) user@computer:~$ python -m pip install --upgrade pip 
(<nome_do_ambiente>) user@computer:~$ python -m pip install jupyter
```

Para executar o Jupyter Notebook :
```console
(<nome_do_ambiente>) user@computer:~$ jupyter notebook
```
### Abrindo o Notebook

Ao executar o Jupyter no seu terminal, ele irá abrir na respectiva pasta que você está, então é preferível que o Jupyet seja executado na pasta onde está o notebook.
```console
(<nome_do_ambiente>) user@computer:~/pasta_do_notebook$ jupyter notebook
```
E então, logo que o Jupyter abrir basta acessar o notebook.