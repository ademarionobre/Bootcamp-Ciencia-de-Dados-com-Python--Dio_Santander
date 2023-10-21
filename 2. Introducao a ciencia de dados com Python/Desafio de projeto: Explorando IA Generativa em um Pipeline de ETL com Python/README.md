# Desafio de projeto: Explorando IA generativa em um pipeline de ETL com Python  
Vamos construir um pipeline ETL (Extração, Transformação e Carregamento), demonstrando a relação entre dados, Inteligência Artificial (IA) e APIs.  
Extração: A aventura começa com uma planilha simples, de onde extrairemos os IDs dos usuários. Depois, usaremos esses IDs para acessar a API da 'Santander Dev Week 2023' e obter dados mais detalhados, um processo que evidencia a versatilidade na coleta de informações em Ciência de Dados.  
Transformação: Adentraremos o universo da IA com o GPT-4 da OpenAI, transformando esses dados em mensagens personalizadas de marketing. Veremos como a IA pode ser empregada de maneira inovadora e prática!  
Carregamento: Finalizaremos o processo enviando essas mensagens de volta para a API da 'Santander Dev Week 2023'.  
Este passo ilustra como dados transformados são reintegrados em sistemas, completando o ciclo de um pipeline ETL.

# Explorando IA Generativa em um Pipeline de ETL com Python

### Proposta para resolução: 

Aprimorar a relação do cliente através da personalização de mensagens de marketing. Dispondo a IA Generativa para criar mensagens exclusivas de acordo com as necessidades de cada cliente.

### Conteúdo Repositório:
- <strong>user_id.csv:</strong> Arquivo **.csv** com os dados utilizados no projeto.
- <strong>notebook:</strong> Jupyter notebook com o script do projeto e etapas.

### Linguagem e bibliotecas utilizada:
- Python
- Pandas
- OpenAI

### Metodologia:

- <strong>Coleta e Aquisição dos Dados:</strong>

  Utilizando um arquivo **.csv**, que contém uma relação de identificações de clientes para obter as informações.  
  
  Através da conexão com a **API**, foi acessado informações detalhadas de cada cliente, tendo como referência os identificadores listados no arquivo **csv**.

- <strong>Utilizando a IA:</strong>

  Utilizado a **API** do **ChatGPT** da **OpenAI** para gerar mensagens de marketing personalizadas para cada cliente. Gerando mensagens alinhadas as necessidades e preferências dos clientes.

- <strong>Carregamento dos dados:</strong>

  Estando as mensagens prontas, são enviadas de volta essas informações a **API**. Isso atualizará a lista de **"news"** de cada usuário, fazendo com que as mensagens sejam entregues.

### Conclusão:

Por meio da utilização e aplicação da **IA Generativa**, o desafio do projeto tem como objetivo modelar e melhorar a forma que a empresa se comunica com seus clientes. Ao criar mensagens de marketing personalizadas os clientes sentirão maior engajamento com seus fornecedores e satisfação com a marca.

---
### Contato:

<div>
  <a href="https://linkedin.com/in/ademario-nobre" target="_blank"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white&color=black" target="_blank"></a>  
  </div>

___________
###
[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](https://opensource.org/licenses/MIT) 
___________
Links de apoio da Dio.me
[colab.research.google.com](https://colab.research.google.com/drive/1SF_Q3AybFPozCcoFBptDSFbMk-6IVGF-?usp=sharing):  
Link do Notebook criado via Google Colab com todo o código-fonte desenvolvido neste Desafio de Projeto (Lab);

[github.com/digitalinnovationone/santander-dev-week-2023-api](https://github.com/digitalinnovationone/santander-dev-week-2023-api):  
GitHub com a API desenvolvida para a Santander Dev Week 2023 com informações úteis (incluindo o link do Swagger e dados importantes sobre a disponibilidade da API).  
Para saber mais sobre o processo de criação da API RESTful deste Lab.
