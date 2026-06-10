# Imersão Alura - dados_python

Dashboard interativo desenvolvido com os conhecimentos adquiridos na **Imersão Alura - dados_python**. O projeto foi construído em **Python** com **Streamlit**, **Pandas** e **Plotly**, com foco na análise visual de salários na área de dados.

A aplicação permite explorar diferentes recortes do dataset por meio de filtros laterais e exibe métricas e gráficos interativos de forma simples e intuitiva.

## Preview

### Dashboard principal:

<p align="center">
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c311efcd-6c69-4e6e-bce5-f28bde1fc484" />
</p>

### Rodando o sistema:

[Acesse o projeto em funcionamento](https://imersao-alura-dadospython-by-gabrielfurin.streamlit.app/)

## Funcionalidades

* Filtros interativos por ano, senioridade, contrato e tamanho da empresa
* Exibição de métricas gerais como salário médio, salário máximo e total de registros
* Gráfico com o top 10 cargos por salário médio
* Histograma da distribuição salarial
* Gráfico de proporção entre tipos de trabalho
* Mapa com a média salarial por país para o cargo de Data Scientist
* Visualização tabular dos dados filtrados

## Tecnologias utilizadas

* Python
* Streamlit
* Pandas
* Plotly
* VS Code

## Estrutura do projeto

```bash
imersao-alura-dados_python/
├── app.py
├── df_limpo.csv
└── requirements.txt
```

## Como executar o projeto

### 1. Pré-requisitos

Antes de executar o projeto, tenha certeza de que sua máquina atende aos seguintes requisitos:

* Python 3.10 ou superior
* Um terminal (CMD, PowerShell, Git Bash ou terminal do VS Code)
* Sistema operacional Windows, Linux ou macOS

Para verificar a instalação do Python, utilize:

```bash
python --version
```

### 2. Clone o repositório

```bash
git clone https://github.com/gabrielbfurin/imersao-alura-dados_python.git
```

### 3. Acesse a pasta do projeto

```bash
cd imersao-alura-dados_python
```

### 4. Crie e ative um ambiente virtual

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

### 6. Execute o projeto

```bash
streamlit run app.py
```

## Aprendizados

* Criação de dashboards interativos com Streamlit
* Manipulação e análise de dados com Pandas
* Construção de gráficos com Plotly
* Filtragem e exploração de datasets
* Organização de uma aplicação Python para visualização de dados

## Possíveis melhorias

* Adicionar mais filtros analíticos
* Criar comparações entre cargos e países
* Melhorar o design visual do dashboard
* Incluir exportação dos dados filtrados
* Expandir a análise com novos gráficos e indicadores

## Autor

Desenvolvido por **Gabriel B. Furin**

⭐ Se você gostou do projeto, considere deixar uma estrela no repositório!
