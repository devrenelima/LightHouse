# Análise Preditiva de Notas de Filmes no IMDB

## 📖 Descrição do Projeto

Este projeto realiza uma análise aprofundada sobre os fatores que determinam o sucesso no cinema, examinando a relação entre gênero, duração, diretores, faturamento e a avaliação do público (nota IMDB). A análise culmina na construção de um modelo preditivo de regressão, utilizando LightGBM, capaz de estimar a nota de um filme com base em suas características.

---

## 🚀 Principais Insights da Análise

* **O Dilema Estratégico do Gênero:** Foi revelada uma clara dicotomia entre sucesso comercial e aclamação da crítica. Gêneros de nicho (ex: 'Film-Noir') alcançam as maiores avaliações, enquanto gêneros de massa lideram a bilheteria, indicando uma escolha estratégica entre prestígio e faturamento.

* **A Duração como Fator de Qualidade:** Identificou-se uma forte correlação positiva entre a duração de um filme e sua nota. Produções mais longas (acima de 150 minutos) tendem a receber avaliações mais altas, sugerindo que o público valoriza narrativas com desenvolvimento aprofundado.

* **Dois Perfis de Diretores de Sucesso:** A análise segmentada de diretores revelou dois arquétipos distintos: os mestres clássicos, com alto prestígio crítico e faturamento historicamente modesto, e os diretores de blockbusters contemporâneos, que dominam o mercado global com franquias de enorme sucesso comercial.

---

## 🛠️ Como Baixar e Rodar o Projeto

Siga os passos abaixo para configurar e executar a análise e o modelo preditivo em sua máquina local.

### Pré-requisitos

* Python 3.8 ou superior
* Git (para clonar o repositório)

### Passos para Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO_AQUI]
    cd [NOME_DA_PASTA_DO_PROJETO]
    ```

2.  **Crie e ative um ambiente virtual (Recomendado):**
    * Isso isola as dependências do seu projeto.

    * **Windows:**
        ```bash
        python -m venv venv
        .\venv\Scripts\activate
        ```

    * **macOS / Linux:**
        ```bash
        python3 -m venv venv
        source venv/bin/activate
        ```

3.  **Instale as bibliotecas necessárias:**
    * O arquivo `requirements.txt` contém todas as bibliotecas que o projeto precisa.

    ```bash
    pip install -r requirements.txt
    ```

4.  **Inicie o Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

5.  **Execute os arquivos:**
    * Seu navegador abrirá a interface do Jupyter.
    * Abra o arquivo `.ipynb` principal (ex: `analise_filmes.ipynb`).
    * Execute as células de código em ordem para replicar a análise e o treinamento do modelo.

---

## 📁 Estrutura do Projeto

```
├── dados/
│   └── dados_tratados.csv      # Dataset principal
├── modelo_preditivo_imdb.pkl   # Modelo de machine learning treinado e salvo
├── analise_filmes.ipynb        # Notebook com a análise exploratória e preditiva
├── requirements.txt            # Lista de dependências Python
└── README.md                   # Este arquivo
```

## 💻 Bibliotecas Utilizadas

* **Pandas:** Manipulação e análise de dados.
* **NumPy:** Operações numéricas.
* **Matplotlib & Seaborn:** Visualização de dados.
* **WordCloud:** Criação de nuvens de palavras.
* **Scikit-learn:** Ferramentas de pré-processamento e avaliação de modelos.
* **LightGBM:** Implementação do modelo de Gradient Boosting.
* **Jupyter Notebook:** Ambiente de desenvolvimento interativo.
