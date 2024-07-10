# CaseFakeStoreAPI
Este projeto envolve a coleta e análise de dados da FakeStoreAPI para entender o comportamento dos usuários relacionado aos carrinhos de compras. O objetivo é extrair insights como as datas mais recentes de atualização dos carrinhos de usuários e as categorias de produtos mais frequentemente adicionadas.

## Principais Funcionalidades
- Coleta de Dados: Utiliza APIs para buscar dados de produtos, usuários e carrinhos de compras.
- Processamento de Dados: Analisa os carrinhos de compras dos usuários para determinar as datas mais recentes de atualização e as categorias de produtos mais frequentes.
- Saída: Gera um arquivo CSV que resume as métricas de comportamento dos usuários com base nos dados coletados.

## Tecnologias Utilizadas
- Python
- Pandas
- Biblioteca Requests para requisições de API

## Uso
- Clone o repositório.
- Instale as bibliotecas necessárias (pandas, requests).
- Execute o script para buscar e processar os dados da FakeStoreAPI.
- Visualize e analise o arquivo CSV gerado (user_cart_data.csv) para obter insights.

## Exemplo de Saída
- O arquivo CSV de saída (user_cart_data.csv) inclui colunas para user_id, latest_date e top_category, proporcionando uma visão do comportamento de compras dos usuários.
