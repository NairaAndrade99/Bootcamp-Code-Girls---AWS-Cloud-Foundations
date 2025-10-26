# Bootcamp-Code-Girls---AWS-Cloud-Foundations
<img width="900" height="250" alt="image" src="https://github.com/user-attachments/assets/4b72ec13-405f-4370-afa7-f19befc3e709" />

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/60be57a8-3053-4ede-b757-01a82a4dc10a" /> IMA -> Identity and Access Management 
<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/46f8d8e3-e549-411d-998a-9a78152fe30d" /> EC2 -> Elastic Compute Cloud 
<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/70b1f1f4-26e7-4e5c-a1b9-e240338d779b" /> EBS -> Elastic Block Store 
<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/be49f31e-5eed-4b8c-95e0-559e6436934c" /> S3 -> Simples Storage Service 


## Primeiro desafio 
Descrição do Desafio
Este laboratório tem como objetivo consolidar seus conhecimentos em gerenciamento de instâncias EC2 na AWS. O entregável é um repositório organizado contendo anotações e insights adquiridos durante a prática, servindo como material de apoio para os seus estudos e futuras implementações.

🏗️ Descrição da Arquitetura
1. Amazon EC2 (Compute)
Crie uma instância EC2 (Linux) para hospedar uma aplicação web simples (ex: uma página PHP ou Python Flask).
A aplicação permite cadastrar e listar usuários.
Ela se conecta a um banco de dados RDS para gravar as informações.

2. Amazon RDS (Database)
Crie um banco de dados relacional (ex: MySQL ou PostgreSQL) no serviço RDS.
Configure:
Nome do banco: usersdb
Tabela: usuarios (id, nome, email, data_criacao)
A aplicação na EC2 se conecta ao RDS usando o endpoint e as credenciais fornecidas.

3. AWS Lambda (Automação)
Crie uma função Lambda (em Python, por exemplo) que:
Conecta-se ao banco RDS.

Deleta registros com mais de 30 dias na tabela usuarios.

Configure a Lambda para ser executada automaticamente 1 vez por dia usando o EventBridge (CloudWatch Events).


<img width="730" height="398" alt="image" src="https://github.com/user-attachments/assets/242c5fd2-af6b-41a0-ab6c-0012fdc7812e" />

