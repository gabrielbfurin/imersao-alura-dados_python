# Dashboard de Salários na Área de Dados

Dashboard interativo desenvolvido em **Python** para exploração e visualização de dados salariais de profissionais da área de dados.

A aplicação utiliza **Pandas** para manipulação dos dados, **Plotly** para criação das visualizações e **Streamlit** para disponibilizar uma interface web interativa.

O projeto foi desenvolvido durante a **Imersão Dados com Python da Alura**, como parte dos meus estudos de análise de dados e desenvolvimento de aplicações Python.

## Aplicação online

**[Acesse o dashboard em funcionamento](https://imersao-alura-dadospython-by-gabrielfurin.streamlit.app/)**

## Preview

### Dashboard principal

<p align="center">
  <img width="1920" height="1080" alt="Dashboard de salários na área de dados" src="https://github.com/user-attachments/assets/c311efcd-6c69-4e6e-bce5-f28bde1fc484" />
</p>

## Funcionalidades

- Filtros interativos por ano, senioridade, contrato e tamanho da empresa
- Cálculo de salário médio e salário máximo
- Identificação do cargo mais frequente
- Visualização do número total de registros
- Ranking dos 10 cargos com maior salário médio
- Histograma da distribuição salarial
- Análise da proporção entre modalidades de trabalho
- Mapa da média salarial de Data Scientists por país
- Visualização dos dados filtrados em tabela

## Tecnologias utilizadas

- Python
- Pandas
- Streamlit
- Plotly
- Git
- GitHub

## Fonte de dados

A aplicação utiliza um **dataset tratado disponibilizado durante a Imersão Dados com Python da Alura**, carregado diretamente de uma fonte remota pelo Pandas.

Essa abordagem permite que o dashboard publicado no Streamlit carregue os dados automaticamente durante sua execução.

O repositório também contém o arquivo `df_limpo.csv`, mantido como referência local do conjunto de dados trabalhado durante o projeto.

> Para executar a aplicação, é necessária uma conexão com a internet para que o dataset utilizado pelo dashboard possa ser carregado.

## Estrutura do projeto

```text
imersao-alura-dados_python/
├── app.py
├── df_limpo.csv
├── requirements.txt
├── .gitignore
└── README.md
```

### `app.py`

Arquivo principal da aplicação.

Responsável pelo carregamento dos dados, aplicação dos filtros, cálculo dos indicadores e construção da interface e das visualizações do dashboard.

### `df_limpo.csv`

Arquivo local mantido no repositório como referência do conjunto de dados tratado durante o desenvolvimento do projeto.

A aplicação atual utiliza diretamente a versão remota do dataset.

### `requirements.txt`

Contém as dependências necessárias para executar o projeto.

### `.gitignore`

Define arquivos e diretórios locais que não devem ser versionados, como ambientes virtuais e arquivos temporários do Python.

## Como executar

### 1. Pré-requisitos

Tenha instalado:

- **Python 3.10 ou superior**
- Git
- Conexão com a internet

Para verificar sua versão do Python:

```bash
python --version
```

### 2. Clone o repositório

```bash
git clone https://github.com/gabrielbfurin/imersao-alura-dados_python.git
```

### 3. Entre na pasta

```bash
cd imersao-alura-dados_python
```

### 4. Crie um ambiente virtual

```bash
python -m venv .venv
```

No Windows:

```bash
.venv\Scripts\activate
```

No Linux/macOS:

```bash
source .venv/bin/activate
```

### 5. Instale as dependências

```bash
pip install -r requirements.txt
```

### 6. Execute a aplicação

```bash
streamlit run app.py
```

O Streamlit iniciará um servidor local e disponibilizará o dashboard pelo navegador.

## Aprendizados

Durante o desenvolvimento deste projeto, pratiquei principalmente:

- manipulação e filtragem de dados com Pandas;
- criação de dashboards interativos com Streamlit;
- construção de gráficos com Plotly;
- criação e interpretação de indicadores;
- exploração de datasets;
- uso de filtros dinâmicos;
- organização e publicação de uma aplicação Python.

## Possíveis evoluções

Algumas funcionalidades que poderiam ser exploradas em versões futuras:

- comparação direta entre cargos;
- comparação salarial entre diferentes países;
- novos indicadores analíticos;
- exportação dos dados filtrados;
- melhoria da experiência visual;
- otimização do carregamento dos dados;
- tornar o projeto independente de fontes externas de dados.

## Autor

Desenvolvido por **Gabriel Furin**.
