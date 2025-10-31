# Bootcamp-Code-Girls---AWS-Cloud-Foundations
<img width="1118" height="438" alt="image" src="https://github.com/user-attachments/assets/72c1beb9-2184-4e7d-ae47-588ddfcc9aa2" />



 <img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/60be57a8-3053-4ede-b757-01a82a4dc10a" /> IMA -> Identity and Access Management 
 <p>  O AWS IAM é o serviço da Amazon que permite gerenciar quem pode acessar seus recursos na nuvem e o que cada pessoa ou serviço pode fazer. Ele é essencial para segurança e controle        de acesso na AWS.</p> 
 
<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/46f8d8e3-e549-411d-998a-9a78152fe30d" /> EC2 -> Elastic Compute Cloud 
<p>O AWS EC2 (Elastic Compute Cloud) é um serviço da Amazon que fornece servidores virtuais na nuvem, conhecidos como instâncias, que você pode usar para rodar aplicações, sites, bancos de dados, entre outros. É basicamente “alugar computadores na nuvem” com alta flexibilidade.</p>

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/70b1f1f4-26e7-4e5c-a1b9-e240338d779b" /> EBS -> Elastic Block Store 
<p>O AWS EBS (Elastic Block Store) é um serviço de armazenamento em blocos para uso com instâncias EC2. Ele fornece discos virtuais persistentes que você pode anexar às suas máquinas na nuvem, funcionando de forma parecida com um HD ou SSD de um computador físico, mas na nuvem.</p>

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/be49f31e-5eed-4b8c-95e0-559e6436934c" /> S3 -> Simples Storage Service 
<p> O AWS S3 (Simple Storage Service) é um serviço de armazenamento de objetos na nuvem, usado para guardar arquivos de qualquer tipo e tamanho, como imagens, vídeos, documentos ou backups. Diferente do EBS, que é um disco ligado a uma instância EC2, o S3 é totalmente independente, acessível via internet ou dentro da AWS.</p>

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/6e20a4e9-00a1-468e-9eff-2333706854d5" /> AMI -> Amazon Machine Image 
<p> O AMI (Amazon Machine Image) é um modelo ou “molde” de uma máquina virtual que você pode usar para criar instâncias EC2 na AWS. Ele contém tudo que é necessário para que a instância funcione: sistema operacional, softwares instalados, bibliotecas e configurações.</p>

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/cf93f3ee-7375-460c-ba88-3f55e7d5e0b7" /> Lambda Function 
<p> O AWS Lambda é um serviço de computação serverless da AWS, que permite executar código sem precisar gerenciar servidores. Em vez de provisionar ou manter máquinas, você só envia o código, define quando ele deve ser executado e paga apenas pelo tempo de execução.</p>

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/fd94a2eb-0e41-4d2b-822e-b8ffc70d16a0" /> VPC-> Virtual Private Cloud
<p>O AWS VPC (Virtual Private Cloud) é um serviço que permite criar uma rede privada isolada na nuvem da AWS, onde você pode executar recursos como EC2, RDS e Lambda de forma segura e controlada, como se fosse sua própria rede local na nuvem.</p>

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/16b675cc-1bf8-4f35-a09b-abd7013b8389" /> Route S3 -> 
<p> No contexto da AWS, “Route S3” geralmente se refere à rota criada em uma VPC para permitir que instâncias EC2 acessem o S3. Não é um serviço separado, mas sim uma configuração de rede dentro da VPC.</p>

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/9cabf3bf-66a4-445d-88f9-a4529f23efa3" /> Elastic Loard Balancer
<p>O AWS Elastic Load Balancer (ELB) é um serviço da AWS que distribui automaticamente o tráfego de entrada entre múltiplas instâncias EC2 ou serviços, garantindo alta disponibilidade e escalabilidade das aplicações. Ele funciona como um “recepcionista inteligente” que direciona os pedidos para os servidores disponíveis.</p>

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/7b72f8c7-1ee2-46bf-98fc-641bde668ab5" /> RDS -> Relational Database Service
<p> O AWS RDS (Relational Database Service) é um serviço gerenciado de banco de dados relacional na nuvem. Ele permite que você crie, opere e escale bancos de dados sem precisar se preocupar com a administração da infraestrutura, backups ou manutenção do servidor.</p>

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/10fe43f3-f4ba-4646-95b8-6771c60f0ab6" /> DynamoDB
<p> O AWS DynamoDB é um serviço de banco de dados NoSQL totalmente gerenciado da AWS. Ele é projetado para oferecer alta performance, escalabilidade automática e baixa latência, ideal para aplicações que precisam de respostas rápidas e acesso massivo a dados.</p>

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/2b7ff3ac-ddbd-41b7-ac68-7213e9eb94ee" /> Glacier S3
<p>O Amazon S3 Glacier é uma camada de armazenamento do S3 voltada para arquivamento de dados a longo prazo, oferecendo baixo custo e alta durabilidade, mas com acesso mais lento aos arquivos em comparação com o S3 padrão.</p>

<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/aa080b91-7d61-4bfa-988f-e11d543496f8" /> CloudFront 
<p>O AWS CloudFront é um serviço de Content Delivery Network (CDN) da Amazon que distribui conteúdos (como sites, vídeos, APIs e arquivos) para usuários finais com baixa latência e alta velocidade, usando uma rede global de servidores chamados edge locations.</p>

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

