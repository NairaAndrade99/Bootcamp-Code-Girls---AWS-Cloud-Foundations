# Bootcamp-Code-Girls---AWS-Cloud-Foundations
<img width="1118" height="438" alt="image" src="https://github.com/user-attachments/assets/72c1beb9-2184-4e7d-ae47-588ddfcc9aa2" />


<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/60be57a8-3053-4ede-b757-01a82a4dc10a" /> IMA -> Identity and Access Management 
<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/46f8d8e3-e549-411d-998a-9a78152fe30d" /> EC2 -> Elastic Compute Cloud 
<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/70b1f1f4-26e7-4e5c-a1b9-e240338d779b" /> EBS -> Elastic Block Store 
<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/be49f31e-5eed-4b8c-95e0-559e6436934c" /> S3 -> Simples Storage Service 
<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/6e20a4e9-00a1-468e-9eff-2333706854d5" /> AMI -> Amazon Machine Image 
<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/cf93f3ee-7375-460c-ba88-3f55e7d5e0b7" /> Lambda Function 
<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/fd94a2eb-0e41-4d2b-822e-b8ffc70d16a0" /> VPC-> Virtual Private Cloud





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

