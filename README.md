📈 Plataforma Inteligente de Análise de Risco e Sentimento
Analisando o mercado financeiro com Inteligência Artificial: da coleta de dados ao deploy com MLOps.



🎯 Sobre o Projeto
Este projeto foi desenvolvido como requisito final para a Pós-Graduação em Ciência de Dados da XP Educação.

A análise de investimentos tradicional, embora consolidada, muitas vezes não captura a dinâmica e o impacto de fatores não estruturados, como o sentimento do mercado expresso em notícias e redes sociais.

Esta plataforma foi criada para superar esse desafio, desenvolvendo uma solução end-to-end que:

Coleta e processa dados de múltiplas fontes (preços de ações, notícias);
Utiliza Inteligência Artificial para analisar o sentimento por trás das notícias financeiras;
Gera um score de risco e tendência para ativos de renda variável da B3;
Apresenta os insights em um dashboard interativo;
Automatiza todo o pipeline de dados e modelo usando práticas de MLOps.

✨ Principais Funcionalidades
Análise de Sentimento em Tempo Real: Classificação automática de notícias como positivas, negativas ou neutras usando modelos de linguagem (NLP).
Score de Risco Preditivo: Um modelo de Machine Learning que combina dados técnicos e de sentimento para prever a volatilidade e tendência dos ativos.
Dashboard Interativo: Uma interface amigável (desenvolvida com Streamlit/Dash ou Power BI) para que analistas possam explorar os dados e insights.
Pipeline Automatizada (MLOps): Processos de CI/CD para retreinar e fazer o deploy do modelo automaticamente, garantindo que a plataforma esteja sempre atualizada.

🏛️ Arquitetura da Solução


Fontes de Dados -> Pipeline de ETL -> Data Lake/Warehouse -> Treinamento de Modelo -> API do Modelo -> Dashboard


🛠️ Tecnologias Utilizadas

<details>
  <summary><strong>🐍 Linguagem & Bibliotecas</strong></summary>
  <br>
  <div>
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
    <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
    <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
    <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  </div>
</details>

<details>
  <summary><strong>📊 Coleta de Dados & NLP</strong></summary>
  <br>
  <div>
    <img src="https://img.shields.io/badge/Beautiful_Soup-000000?style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
    <img src="https://img.shields.io/badge/NLTK-30AADD?style=for-the-badge&logo=python&logoColor=white" />
  </div>
</details>

<details>
  <summary><strong>⚙️ MLOps & Deploy</strong></summary>
  <br>
  <div>
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
    <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
    <img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
    <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  </div>
</details>

<details>
  <summary><strong>📈 Visualização & BI</strong></summary>
  <br>
  <div>
    <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
    <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" />
    <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black" />
    <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white" />
  </div>
</details>
<br>

⚙️ Estrutura e Metodologia
O projeto foi dividido em 5 etapas principais, simulando um ciclo de vida completo de um produto de dados:

<details>
  <summary><strong>💾 Coleta de Dados</strong></summary>
  <br>
  <div>
    <img src="https://img.shields.io/badge/Data_Acquisition-blue?style=for-the-badge&logo=database&logoColor=white" alt="Coleta de Dados Badge"/>
  </div>
  <br>
  Extração de dados históricos de cotações da B3 e notícias relevantes de portais financeiros, criando nosso dataset inicial.
</details>

<details>
  <summary><strong>⚙️ Engenharia de Features & Análise de Sentimento</strong></summary>
  <br>
  <div>
    <img src="https://img.shields.io/badge/Feature_Engineering-orange?style=for-the-badge&logo=gear&logoColor=white" alt="Engenharia de Features Badge"/>
    <img src="https://img.shields.io/badge/Sentiment_Analysis-purple?style=for-the-badge&logo=comment-dots&logoColor=white" alt="Análise de Sentimento Badge"/>
  </div>
  <br>
  Limpeza dos dados, criação de indicadores técnicos (médias móveis, volatilidade) e, crucialmente, a aplicação de um modelo de NLP para transformar notícias em um score de sentimento numérico.
</details>

<details>
  <summary><strong>🧠 Modelagem e Treinamento</strong></summary>
  <br>
  <div>
    <img src="https://img.shields.io/badge/Model_Training-brightgreen?style=for-the-badge&logo=brain&logoColor=white" alt="Modelagem e Treinamento Badge"/>
    <img src="https://img.shields.io/badge/Machine_Learning-red?style=for-the-badge&logo=robot&logoColor=white" alt="Machine Learning Badge"/>
  </div>
  <br>
  Desenvolvimento e comparação de modelos de Machine Learning (desde XGBoost até Redes Neurais) para prever o risco/tendência do ativo com base nas features criadas.
</details>

<details>
  <summary><strong>📊 Visualização e Análise Ética</strong></summary>
  <br>
  <div>
    <img src="https://img.shields.io/badge/Data_Visualization-lightgrey?style=for-the-badge&logo=chart-bar&logoColor=black" alt="Visualização Badge"/>
    <img src="https://img.shields.io/badge/Ethical_Analysis-yellow?style=for-the-badge&logo=balance-scale&logoColor=black" alt="Análise Ética Badge"/>
  </div>
  <br>
  Construção de um dashboard interativo para apresentar os resultados de forma clara. Esta etapa também incluiu uma reflexão sobre a governança e os vieses éticos do modelo.
</details>

<details>
  <summary><strong>🚀 Deploy e MLOps</strong></summary>
  <br>
  <div>
    <img src="https://img.shields.io/badge/Deployment-blueviolet?style=for-the-badge&logo=rocket&logoColor=white" alt="Deploy Badge"/>
    <img src="https://img.shields.io/badge/MLOps-9cf?style=for-the-badge&logo=cloud&logoColor=white" alt="MLOps Badge"/>
  </div>
  <br>
  A etapa final e o grande diferencial. O modelo foi containerizado com Docker e um pipeline de CI/CD foi criado para automatizar o retreinamento e o deploy, tornando a solução robusta e escalável.
</details>
<br>
<br>

🚀 Como Executar o Projeto

### ✅ Entregáveis

* 🐙 **Repositório completo no GitHub:** Com todo o código, notebooks e documentação.
* 📊 **Dashboard interativo funcional:** Para visualização dos insights e resultados.
* 🔌 **Endpoint de uma API:** Para consumo do modelo de forma programática.
* 🏆 **Apresentação final do projeto:** Consolidando a jornada e as conclusões.
