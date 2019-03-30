# PyTrigo - Introdução à Data Science com Python

Este repositório possui um conjunto de notebooks em português criados para servirem de introdução à DataScience com Python.

A versão do Python utilizada neste tutorial é a versão 3.

O primeiro passo é instalar o software necessário à aprendizagem.

## Instalação do Python3 (em Windows)

O primeiro passao é instalar o software que lhe irá permitir executar os programas criados na linguagem Python.

Existem várias formas de o fazer, sendo aqui aparesentadas duas formas: através da instalação da distribuição Anaconda da Continum Analytics; e através da instação do Python a partir da fonte original, a Python Software Foundation.

1. Distribuição Anaconda
A vantagem da distribuição Anaconda é que oferece para além do Python um conjunto vasto de packages de suporte ao desenvolvimento de programas ligados à DataScience.
    1. Descarregue e instale o package Anaconda3 (https://www.anaconda.com/distribution/ ).\
    2. Durante a instalação siga as opções recomendadas
    3. Abrir a aplicação Anaconda Navigator\
   ![Anaconda3 Navigator](http://res.cloudinary.com/dbcauiwaz/image/upload/c_scale,w_512/v1523867285/anaconda-navigator.png)
    4. Iniciar a aplicação Jupyter Lab ou Jupyter Notebook
    5. Caso no futuro deseje instalar packages que não estão disponíveis na instalação do anaconda por omissão, inicie uma consola do windows configurada para o Anaconda, a "Anaconda Prompt" (faça pesquisar no Windows) e corra o comando conda, que permite aceder aos packages disponibilizados pelo Anconda Cloud. Caso o package que deseja não esteja disponível aí corra, na mesma janela, o comando [pip](https://pypi.org/project/pip/), uma ferramenta de gestão de packages do próprio Python.
    
2. Python Software Foundation
Para fazer a instalação do Python e dos packages associados à temática da DataScience deverá:
    1. Descarregar o Python a partir do seguinte endereço https://www.python.org/downloads/
    2. Após a instalação do Python abra uma consola do windows e escreva python. Verifique que está acorrer a versão que instalou. Após verificar saia desse ambiente escrevendo o comando exit().
    3. De seguida utilize o comando [pip](https://pypi.org/project/pip/) para fazer a instalação dos packages necessários para executar os notebooks
        3.1 pip install numpy
        3.2 pip install scipy
        3.3 pip install scikit-learn
        3.4 pip install pandas
    4. A instalação de outros packages no futuro é similar, utilizando o comando pip

Poderá ainda ter a necessidade de fazer a instalação de algum package específico não disponibilizado no gestor de pacotes pip.

As intruções de instalação são para o ambiente Windows. Para outros ambientes terá de consultar as páginas da Continum Analytics e da Python Software Foundation e seguir as instruções de instalação. Depois de a instalação estar feita a forma de trabalhar com a consola de Python e com o Jupyter Notebook é similar.

## Utilização do Jupyter Notebook

A utilização do Jupyter Notebook é descrita no notebook [pytrigo-1-intro.ipynb](pytrigo-1-intro.ipynb). Para o abrir este notebook terá de utilizar a aplicação Jupyter Lab ou Jupyter Notebook, instaladas no ponto anterior, aceder à pasta que contém o ficheiro [pytrigo-1-intro.ipynb](pytrigo-1-intro.ipynb) e clicar duas vezes sobre ele.

### Jupyter lab online

Caso queira abrir este repositório num jupytyer lab online podem fazê-lo utilizando a seguinte ligação:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/atrigo/trigo-data-science.git/master?urlpath=lab)

As alterações aos ficheiros não serão guardadas!

## Ordem de aprendizagem dos conteúdos

A ordem de aprendizagem dos contéudos é a seguinte:
* Introdução ao Python (pytrigo-1-intro.ipynb)
* Descrição das bibliotecas disponíveis no Python (pytrigo-2-bibliotecas)
* Package SciPy.org (computação científica)
  * Introdução à biblioteca NumPy (pytrigo-3-numpy.ipynb)
  * Introdução à biblioteca SciPy (pytrigo-4-scipy.ipynb)
  * Introdução à biblioteca MatPlotLib (pytrigo-5-matplotlib.ipynb)
  * Introdução à biblioteca Pandas (pytrigo-6-pandas.ipynb)
* Package Scikit (machine learning)
  * Introdução à biblioteca Scikit (pytrigo-7-scikit-learn.ipynb)
* Package NetworX (manipulação de grafos)
  * Introdução à biblioteca NetworkX (pytrigo-8-networkx.ipynb)
* Exemplos de utilização das bibliotecas
  * Regressão linear (pytrigo-ex1-regressao.ipynb)

## Citação deste trabalho

Agradeço que, caso estes notebooks sejam úteis para o seu trabalho que dê uma estrela ao projeto e que o cite da seguinte forma:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1226769.svg)](https://doi.org/10.5281/zenodo.1226769)

## Dúvidas ou situações menos claras

Sempre que tiverem dificuldade na instalação de alguma coisa ou algo que percebam menos bem digam-me pois a ideia é tornar o mais claro possível os textos deste repositório.

### Dúvida 1

Algumas dificuldades na instalação:

1. Nome do diretorio de instalação não deverá conter caracteres acentuados ou espaços. Ver (https://docs.anaconda.com/anaconda/install/windows  e  https://docs.anaconda.com/anaconda/faq#how-do-i-get-anaconda-with-python-3-5).


### Dúvida X - aqui pode estar a sua dúvida :)
