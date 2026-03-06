# API-2-Semestre
README — COMEXSTAT Import Data Pipeline
🔍 Sobre o Projeto

Este projeto consiste em um pipeline de tratamento e consolidação de dados de importação do Brasil (anos 2024 e 2025), utilizando Python e a biblioteca Pandas. O objetivo é transformar bases brutas do COMEXSTAT em um conjunto de dados limpo e enriquecido, pronto para análises comerciais e de supply chain.

📌 O que o código faz

O pipeline executa as seguintes etapas:

Conecta ao Google Drive
Utiliza o Google Colab para montar o Drive e acessar as bases de dados CSV.

Importa dados de múltiplos anos
Carrega dois arquivos CSV (importações de 2024 e 2025).

Concatena as bases
Combina as informações em um único DataFrame com milhões de registros.

Insere descrições dos produtos (tabela NCM)
Faz um merge com a tabela NCM para adicionar a descrição oficial dos itens importados.

Limpa dados inconsistentes
Remove registros sem Unidade da Federação definida ou sem valor unitário válido.

Cria um novo indicador — Valor por kg (VA)
Calcula o valor FOB por quilograma, que é uma métrica importante para análises de comércio exterior.

Exporta o resultado final
Salva um CSV limpo e pronto para análises ou visualizações.

📊 Tecnologias Utilizadas

🐍 Python

📊 Pandas

☁️ Google Colab

🗃️ GitHub

🎯 Objetivo

Fornecer uma base robusta e tratada para análises de:

Comércio exterior

Indicadores de preço por peso

Estudos de mercado

Dashboards analíticos

Isso demonstra habilidades em:

ETL (Extração, Transformação e Carga)

Manipulação de grandes volumes de dados

Enriquecimento de dados

Preparação para BI e visualizações

🔗 Código Fonte

🔗 Acesse o código completo aqui:
👉 https://github.com/felipemassa03
👉https://colab.research.google.com/drive/17LFxbX2f-Kul_vj7esDDDb2K3Bzt-4zZ?usp=sharing#scrollTo=IEEhPpqQ8dYT

📝 Como usar

Abra o projeto no Google Colab

Monte o Google Drive

Ajuste os caminhos se necessário

Execute célula por célula

Obtenha o CSV tratado em imp_final.csv
