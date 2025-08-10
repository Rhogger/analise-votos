# Analise de Votos

Este projeto realiza análise de dados eleitorais utilizando Python e Jupyter Notebooks.

## Ambiente e Instalação

Este projeto utiliza o [pipenv](https://pipenv.pypa.io/en/latest/) para gerenciar o ambiente virtual e dependências.

### 1. Instale o pipenv (caso não tenha)

```bash
pip install pipenv
```

### 2. Crie o ambiente e instale as dependências

Na raiz do projeto (onde está o `Pipfile`):

```bash
pipenv install
```

### 3. Ative o ambiente virtual

```bash
pipenv shell
```

## Como usar

Os notebooks estão em `src/notebooks/`. Abra-os com Jupyter Notebook ou VSCode para executar as análises.

Os datasets estão num drive com link público.

## Dependências principais

As dependências são gerenciadas pelo `Pipfile`. Exemplos usadas nos notebooks:

- pandas
- numpy
- matplotlib
- seaborn

Instale qualquer dependência adicional com:

```bash
pipenv install <nome-do-pacote>
```

## Referências

- [Pipenv Documentation](https://pipenv.pypa.io/en/latest/)
