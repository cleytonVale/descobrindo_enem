# Descobrindo ENEM

## 📌 Sobre o Projeto
O **Descobrindo ENEM** é um projeto de análise e transformação de dados utilizando **DBT (Data Build Tool), Snowflake e Apache Hop**. O objetivo é explorar os microdados do ENEM para extrair insights sobre a prova e o público participante, proporcionando análises que possam contribuir para o entendimento do desempenho dos alunos e padrões educacionais.

## 🛠️ Tecnologias Utilizadas
- **Snowflake** → Armazenamento e processamento dos microdados do ENEM.
- **DBT (Data Build Tool)** → Transformação e modelagem dos dados.
- **Apache Hop** → Pipeline de extração, carga e transformação de dados.
- **Python** → Scripts auxiliares para análise e automação.

## 🔍 Objetivos do Projeto
- Criar uma estrutura otimizada para análise dos microdados do ENEM.
- Aplicar boas práticas de engenharia de dados para transformação e modelagem.
- Explorar padrões nos dados para compreender melhor o exame e os candidatos.
- Desenvolver painéis e relatórios para visualização dos insights extraídos.

## 📂 Estrutura do Repositório
```
📂 descobrindo_enem
 ├── 📁 models/           # Modelos DBT
 ├── 📁 scripts/          # Scripts auxiliares (Python, SQL, etc.)
 ├── 📁 pipelines/        # Pipelines do Apache Hop
 ├── 📁 data/             # Arquivos de amostra dos microdados
 ├── dbt_project.yml      # Configuração do projeto DBT
 ├── requirements.txt     # Dependências do projeto
 ├── README.md            # Documentação do projeto
```

## 🚀 Como Rodar o Projeto
1. **Clone o repositório:**
   ```sh
   git clone https://github.com/seu-usuario/descobrindo_enem.git
   cd descobrindo_enem
   ```
2. **Instale as dependências:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Configure a conexão com o Snowflake no DBT (`profiles.yml`).**
4. **Execute o pipeline de ETL com Apache Hop.**
5. **Rode as transformações DBT:**
   ```sh
   dbt run
   ```
6. **Analise os dados e gere insights!**

## 📊 Contribuições
Sinta-se à vontade para abrir issues e pull requests para contribuir com o projeto! 😃

---
📌 **Mantenedor:** Cleyton Vale



