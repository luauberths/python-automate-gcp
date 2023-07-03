# python-automate-gcp
Automação de tabelas do GCP utilizando Python e API do Google Sheets

O projeto consistiu em criar uma função capaz de realizar atualização de dados do Google Big Query de forma automática.

Para isso, foram criadas duas funções.

A primeira função é responsável por realizar a integração do Google Sheets com o Google Cloud Storage através de uma biblioteca do Google Sheets (gspread) e a partir de uma planilha, gerar um arquivo csv em um bucket do Storage.

A segunda função utiliza o arquivo do Storage para criação de uma tabela no Google BigQuery de acordo com os critérios do usuário.

Para criar uma rotina de automação vinculando a planilha com o Cloud Functions, o Google Apps Script se tornou uma ferramenta de extrema importância para desenvolver um gatilho de ativação a partir da alteração da planilha.


