# Projeto Langflow: Semana2 Campeão

## Visão Geral

Este projeto é um pipeline feito em Langflow projetado para funcionar como uma solução RAG (Retrieval Augmented Generation). O fluxo faz a ingestão de dados utilizando RecursiveTextSpliting, processamento, embedding e gravação no banco vetorial ChomaDB. Este README fornece uma visão geral da construção do fluxo, detalhes sobre cada nó e instruções sobre como executar o projeto.

## Componentes dos Flows

1. **Flow de ingestão de dados**
   - File Uploader
   - Text Split
   - ChromaDB

2. **Flow de Chat**
   - Chat Input
   - Open AI Embedding
   - Chroma DB
   - Parse Data
   - Prompt
   - OpenAI
   - Langwatch Evaluator
   - Chat Output


## Como Executar o Projeto

1. **Importar o flow no Langflow (`SEMANA2_CAMPEAO.json`) 

2. **Configurar as API KEYS**

3. **Executar os Componentes**:
   - Siga as conexões entre os nós para entender o fluxo de dados.
   - Comece com o Carregador de Arquivos para ingerir os arquivos necessários. Na competição usamos o livro Cosmos de Carl Sagan. Mas pode subir qualquer conteúdo em PDF que deve funcionar.
   - Faça a ingestão de dados processando o nó Chroma Vector Store
   - Execute o flow no playground ou executando o nó Chat Output

## Contribuição

Sinta-se à vontade para fazer fork deste repositório e contribuir enviando pull requests. Para mudanças significativas, por favor, abra uma issue para discutir o que você gostaria de mudar.

## Licença

Este projeto é licenciado sob a Licença MIT. Consulte o arquivo LICENSE para mais detalhes.
