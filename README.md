## ETL com pandas e Matplotlib
|Language: | [![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)|
|-:|:-|
|Libraries: | [![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/docs/) [![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)](https://matplotlib.org/stable/index.html)|
|IDE: | [![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/) [![VSC](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)|
|License: | [![ODbL1.0](https://img.shields.io/badge/Open%20Database%20License%20(ODbL)%201.0-63aa63?style=for-the-badge)](./LICENSE)|


## Índice
- [Sobre](#-sobre)
- [Objetivos](#-objetivos)
- [Etapas](#-etapas)
  - [Extração](#Extração)
  - [Transformação](#Transformação)
- [Gráficos](#-Gráficos)
- [Configurações](#-Configurações)
  - [Instalação](#Instalação)
    - [Local](#para-uso-local)
    - [Colab](#para-uso-em-ambiente-interativo-e-colaborativo)
- [Licença](#-licença)


## 🚀 Sobre

#### ETL com pandas e Matplotlib:
  - Processamento e análise de **mais de 560.000** respostas da pesquisa Stack Overflow (2018-2024), extraindo insights sobre tendências em linguagens de programação.
  - Otimização pipeline ETL (Extração, Transformação, Carregamento), reduzindo inconsistências e facilitando análises futuras.
  - Desenvolvimento de um sistema dinâmico de padronização de dados que se adapta a mudanças estruturais em conjuntos de dados ao longo dos anos, garantindo a integridade dos dados e minimizando a intervenção manual.
  - Utilização do pandas para manipular e analisar eficientemente grandes conjuntos de dados, melhorando a flexibilidade e velocidade da análise de dados.
  - Criação de gráficos detalhados usando Matplotlib, permitindo interpretação clara das tendências de adoção de linguagens e a evolução das respostas ao longo do tempo, facilitando insights baseados em dados.
  - Melhora na tomada de decisões na análise de dados, estruturando os resultados para identificar padrões de crescimento e queda de linguagens de programação.

[(Voltar ao topo)](#índice)
## 📝 Objetivos
Mostrar o uso das bibliotecas `pandas` e `Matplotlib` com o propósito de tratamento de dados.
Analisar os dados de tendências no mercado de trabalho na área de tecnologia, de 2018 a 2023 - principais habilidades, ferramentas e linguagens de programação.


[(Voltar ao topo)](#índice)
## 🪜 Etapas
Para ficar mais intuitivo, as etapas serão mostradas em outro documento, de maneira que podem ser replicadas no Google Colab.

[(Voltar ao topo)](#índice)
## 📈 Gráficos

[![grp](grafico_respostas_porano.png)](grafico_respostas_porano.png)\
[![lu](linguagens_usadas.gif)](linguagens_usadas.gif)
[![[ld](linguagens_desejadas.gif)](linguagens_desejadas.gif)\
[![rnl](respostas_nulas_linguagens.gif)](respostas_nulas_linguagens.gif)
[![grne](grafico_respostas_nulas_empilhadas.png)](grafico_respostas_nulas_empilhadas.gif)

[(Voltar ao topo)](#índice)
## ⚙️ Configurações
Linguagem de programação: Python.
Usei as bibliotecas: `pandas` e `Matplotlib` para coleta, processamento e formatação dos dados e a para gráficos e análise, respectivamente.
Ambiente de Desenvolvimento: Visual Studio Code e Google Colab.

Instalação na próxima seção [Instalação](#instalação).

[(Voltar ao topo)](#índice)
### Instalação
#### Para uso local:
  1. O **Python** pode ser baixado direto de seu [site oficial](https://www.python.org/).
  2. Para **IDE** recomendo o uso do **Visual Studio Code**, baixado direto de seu [site oficial](https://code.visualstudio.com/).
  3. Instalando as bibliotecas:
     ```python
     pip install pandas
     pip install matplotlib
     ```
#### Para uso em ambiente interativo e colaborativo:
  1. O **Google Colab** pode ser utilizado através de seu [site oficial](https://colab.research.google.com/).
  2. Instalando as bibliotecas:
      ```python
      !pip install pandas
      !pip install matplotlib
      ```

[(Voltar ao topo)](#índice)
## 📃 Licença

This database - The Public 2018 Stack Overflow Developer Survey Results - is made available under the Open Database License (ODbL): http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: [http://opendatacommons.org/licenses/dbcl/1.0/](http://opendatacommons.org/licenses/dbcl/1.0/)\
\
TLDR: You are free to share, adapt, and create derivative works from The Public 2018 Stack Overflow Developer Survey Results as long as you attribute Stack Overflow, keep the database open (if you redistribute it), and continue to share-alike any adapted database under the ODbl.\
\
[Open Database License (ODbL) 1.0](https://github.com/ghiordanobruno/Pred_SODeveloperSurvey/blob/main/LICENSE)
