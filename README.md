# Bootcamp-Code-Girls---AWS-Cloud-Foundations

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
