# 📊 Dashboard de Análise de Salários na Área de Dados

Este projeto é um dashboard interativo construído com **Streamlit** e **Python**, focado na análise de dados salariais para profissionais da área de dados. O objetivo é fornecer insights sobre salários, cargos, tipos de trabalho e senioridade, permitindo uma exploração detalhada dos dados.

O aplicativo web está disponível publicamente no Streamlit Cloud.

🔗 **Acesse o Dashboard:** https://data-science-salaries-analysis.streamlit.app/

## ✨ Funcionalidades

- **Filtros Interativos:** A barra lateral permite filtrar os dados por ano, senioridade, tipo de contrato e tamanho da empresa.
- **Métricas Chave (KPIs):** Exibe o salário médio, salário máximo, total de registros e o cargo mais frequente.
- **Visualizações Dinâmicas:** Gráficos criados com Plotly para visualizar:
    - Os 10 cargos com a maior média salarial.
    - A distribuição geral dos salários.
    - A proporção de trabalho presencial, remoto e híbrido.
    - Um mapa interativo com o salário médio de Cientistas de Dados por país.
- **Tabela Detalhada:** Exibe a tabela completa com os dados filtrados, permitindo uma análise mais aprofundada.

## 📁 Estrutura do Projeto

A estrutura do projeto é simples e organizada para facilitar a execução e manutenção:
├── .venv/                   # Ambiente virtual do Python
├── .vscode/                 # Configurações do VS Code (opcional)
├── app.py                   # O código principal do dashboard Streamlit
├── dados_limpos.csv         # O conjunto de dados original utilizado
├── requirements.txt         # Lista de bibliotecas necessárias para o projeto
└── .gitignore               # Arquivos a serem ignorados pelo Git (ex: ambiente virtual)
*Note que, no código, o dataset é carregado diretamente de um link no GitHub, garantindo que o aplicativo Streamlit sempre use a versão mais recente dos dados.*

## ⚙️ Como Executar Localmente

Se você deseja rodar o dashboard na sua máquina, siga os passos abaixo:

1.  **Clone o Repositório:**
    ```bash
    git clone [Link do seu repositório]
    cd [Nome do seu repositório]
    ```

2.  **Crie e Ative um Ambiente Virtual:**
    É uma boa prática usar ambientes virtuais para isolar as dependências do projeto.
    ```bash
    # Cria o ambiente virtual
    python -m venv .venv
    
    # Ativa o ambiente virtual (no Windows)
    .venv\Scripts\activate
    
    # Ativa o ambiente virtual (no macOS/Linux)
    source .venv/bin/activate
    ```

3.  **Instale as Dependências:**
    O arquivo `requirements.txt` lista todas as bibliotecas necessárias.
    ```bash
    pip install -r requirements.txt
    ```

4.  **Execute o Aplicativo Streamlit:**
    ```bash
    streamlit run app.py
    ```

O dashboard será aberto automaticamente no seu navegador.

## 🛠️ Tecnologias Utilizadas

- **Python**: A linguagem de programação principal.
- **Streamlit**: Framework para a construção do aplicativo web.
- **Pandas**: Para a manipulação e análise dos dados.
- **Plotly Express**: Para a criação de visualizações de dados interativas.

## 👩‍💻 Autor

Este projeto foi desenvolvido por:

- **Nome:** Leonarda Timm
- **GitHub:** [Link do seu perfil no GitHub]
- **LinkedIn:** https://www.linkedin.com/in/leonarda-timm-9797a5224/?trk=opento_sprofile_topcard

## 📜 Licença

Este projeto está licenciado sob a licença [MIT](https://github.com/vqrca/dashboard_salarios_dados/blob/main/LICENSE). Sinta-se à vontade para usar, modificar e distribuir o código.

---
