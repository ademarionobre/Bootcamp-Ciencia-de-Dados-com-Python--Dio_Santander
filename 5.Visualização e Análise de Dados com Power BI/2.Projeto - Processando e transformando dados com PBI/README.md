# Projeto  – Processamento de dados simplificado com Power BI
## Etapas  
1.	Criação de uma instância na Azure para MySQL
2.	Criar o Banco de dados
3.	Integração do Power BI com MySQL no Azure
4.	Verificar problemas na base a fim de realizar a transformação dos dados
5.	Diretrizes para transformação dos dados
6.	Verifique os cabeçalhos e tipos de dados
7.	Modificar os valores monetários para o tipo double preciso
8.	Verificar a existência dos nulos e analise a remoção
9.	Os employees com nulos em Super_ssn podem ser os gerentes. Verificar se há algum colaborador sem gerente
10.	Verificar se há algum departamento sem gerente
11.	Se houver departamento sem gerente, preencha as lacunas
12.	Verificar o número de horas dos projetos
13.	Separar colunas complexas
14.	Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee.
15.	Eliminar as colunas desnecessárias. (como nova consulta)
16.	Realizar a junção dos colaboradores e respectivos nomes dos gerentes . Pode ser feito com consulta SQL ou pela mescla de tabelas com Power Query. No arquivo README estar a query utilizada no processo.
17.	Mesclar as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores
18.	Mesclar os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela.
19.	Explicação por que, neste caso supracitado, utilizado o mesclar e não o atribuir.
20.	Agrupar os dados a fim de saber quantos colaboradores existem por gerente
21.	Eliminar as colunas desnecessárias, que não serão usadas no relatório, de cada tabela
______________
- [ ] Item 16 - script sql utilizado    

- [ ] Item 19 - Explicação por que, neste caso supracitado, utilizado o mesclar e não o atribuir.   
  xpto  

# Fluxo de dados no Power BI  
![image](https://github.com/ademarionobre/Bootcamp-Ciencia-de-Dados-com-Python--Dio_Santander/assets/92057489/d0690301-7b54-41c9-9e54-ba99079d27d7)

# ![image](https://github.com/ademarionobre/Bootcamp-Ciencia-de-Dados-com-Python--Dio_Santander/assets/92057489/67b04c62-8b7e-4cfa-a003-27736130f1de) Azure Database for MySQL DATABASES 

- Serviço gratuito na plaforma azure por 750hrs (estimado para 30 dias)
- [Desafio de Projeto - Processando e Transformando Dados com Power BI - Instruções.docx](https://github.com/ademarionobre/Bootcamp-Ciencia-de-Dados-com-Python--Dio_Santander/files/13061404/Desafio.de.Projeto.-.Processando.e.Transformando.Dados.com.Power.BI.-.Instrucoes.docx)
[Desafio de Projeto - Processando e Transformando Dados com Power BI.pptx](https://github.com/ademarionobre/Bootcamp-Ciencia-de-Dados-com-Python--Dio_Santander/files/13061403/Desafio.de.Projeto.-.Processando.e.Transformando.Dados.com.Power.BI.pptx)
[Implantação-MySqlFlexibleServer_5d6b26a183ee436a86c9acbb6919130d.zip](https://github.com/ademarionobre/Bootcamp-Ciencia-de-Dados-com-Python--Dio_Santander/files/13061402/Implantacao-MySqlFlexibleServer_5d6b26a183ee436a86c9acbb6919130d.zip)
![servico_criado_azuremysql](https://github.com/ademarionobre/Bootcamp-Ciencia-de-Dados-com-Python--Dio_Santander/assets/92057489/a06b766d-a6d5-421c-a73e-f73a3115627e)
- ![servico azure mysql](https://github.com/ademarionobre/Bootcamp-Ciencia-de-Dados-com-Python--Dio_Santander/assets/92057489/70d4dc26-384b-4fcc-9461-756731522c90)
-  ![Bash_conexao_mysql_usuario](https://github.com/ademarionobre/Bootcamp-Ciencia-de-Dados-com-Python--Dio_Santander/assets/92057489/e279cad3-900a-4cfc-8efb-9b4c79200546)



_________
# [Link Dashboard Relatório azure_company]()
