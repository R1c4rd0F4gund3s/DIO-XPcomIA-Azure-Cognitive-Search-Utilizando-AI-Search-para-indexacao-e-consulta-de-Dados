# ☕ Azure AI Search - Knowledge Mining Lab

Este repositório contém os recursos e instruções para o laboratório de mineração de conhecimento utilizando **Azure AI Search**. O projeto simula uma aplicação real para a cadeia nacional fictícia **Fourth Coffee**, com o objetivo de extrair insights de avaliações de clientes.

## 📌 Objetivos do Lab

- Realizar ingestão de dados via Blob Storage
- Enriquecer documentos com habilidades cognitivas (OCR, detecção de sentimentos, extração de palavras-chave etc.)
- Criar e configurar índices e indexadores no Azure AI Search
- Explorar os resultados utilizando o Search Explorer e o Knowledge Store

## 📂 Estrutura

- `data/`: Contém as avaliações em formato `.docx`
- `scripts/`: Scripts auxiliares para automação e exemplos de consulta
- `docs/`: Documentação de apoio ao laboratório

```plaintext
.
azure-ai-search-lab/
│
├── data/
│   └── reviews/                # Contém os arquivos de avaliações dos clientes
│
├── scripts/
│   ├── upload_documents.ps1    # Script para upload dos documentos no Blob Storage
│   └── query_examples.json     # Exemplos de queries para o Search Explorer
│
├── docs/
│   └── instrucoes.pdf          # Arquivo original de instruções do laboratório
│
├── .gitignore
├── README.md
└── LICENSE
```
## 🛠️ Pré-requisitos

- Conta no Microsoft Azure com permissões para criar recursos
- Familiaridade com o portal do Azure
- Recursos a serem criados:
  - Azure AI Search
  - Azure AI Services
  - Storage Account com containers públicos/privados

> ⚠️ Certifique-se de que todos os recursos estão **na mesma região**

## ▶️ Etapas Resumidas

1. Criar os recursos no Azure (Search, AI Services, Storage)
2. Fazer upload dos arquivos de avaliação no Blob Storage
3. Criar o índice e o indexador utilizando o assistente "Import data"
4. Analisar os resultados no Search Explorer
5. Visualizar os dados enriquecidos no Knowledge Store

## 🧠 Tecnologias Utilizadas

- Azure AI Search
- Azure Cognitive Services
- Azure Blob Storage
- JSON para consultas no Search Explorer

## 📄 Licença

Este projeto é apenas para fins educacionais.

