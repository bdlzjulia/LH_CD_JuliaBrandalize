Este projeto realiza uma análise com a base de dados desafio_indicium_imdb.csv, incluindo previsões de avaliações com base em características como pontuação no Meta Score, número de votos e receita bruta. Inclui um Jupyter Notebook para análise e um arquivo de modelo salvo para previsões.

### Estrutura do Projeto

- LH_CD.ipynb: Jupyter Notebook contendo a análise de dados, visualizações e o treinamento do modelo.
- modelo.pkl: Arquivo contendo o modelo treinado, salvo para uso posterior.
  
### Pré-requisitos

Antes de executar o projeto, você precisa instalar as seguintes bibliotecas. Você pode instalar todas elas usando o arquivo requirements.txt incluído neste repositório.

### Instalação das Dependências

Clone o repositório para sua máquina local:

`https://github.com/bdlzjulia/LH_CD_JuliaBrandalize.git`

`cd LH_CD_JuliaBrandalize`

### Crie um Ambiente Virtual (Opcional, mas recomendado)

`python -m venv venv`

`source venv/bin/activate`

No windows, use:

`venv\Scripts\activate`

### Instale as Dependências

`pip install -r requirements.txt`

Se o arquivo requirements.txt não estiver funcionando, você pode instalar manualmente as seguintes bibliotecas:

`pip install numpy pandas scikit-learn matplotlib seaborn jupyter`

### Executando o Projeto

No diretório do projeto, inicie o Jupyter Notebook:

`jupyter notebook`

Isso abrirá o Jupyter Notebook no seu navegador padrão.

### Abra o Notebook

No navegador, abra o arquivo LH_CD.ipynb para visualizar e executar o código.

### Carregue o Modelo

O Jupyter Notebook contém células que demonstram como carregar e usar o modelo salvo (modelo.pkl). Certifique-se de que o arquivo modelo.pkl está no mesmo diretório do notebook.
