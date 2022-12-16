# Projeto Final Cloud Computing

Você foi contratado por uma empresa de desenvolvimento de software que possui uma demanda para seu cliente de criação de uma Prova de Conceito (POC) sobre o uso de cloud no projeto. 
Para que essa POC funcione, o cliente pediu para que fossem criados 3 ambientes de desenvolvimento, onde ele possa garantir que nesse projeto temos ambiente de produção, homologação e de desenvolvimento. 
Nessa POC, foi pedido para que utilizemos uma API onde o usuário irá mandar um endpoint chamado /PING e o resultado da API será PONG. 
Você foi alocado para realizar essa POC. Seu líder técnico passou as instruções abaixo: 

Primeira Parte: 

Criar uma API usando a linguagem/framework que você se sentir mais à vontade
Nessa API, deve-se criar um endpoint chamado /ping como uma requisição GET
O protocolo desta comunicação deverá ser REST
A resposta do /ping deverá ser um JSON no formato {"ping": "pong"}

Segunda Parte:

Criar o projeto no Github, considerando a criação de 3 branches: prod, staging e dev.
Cada branch deverá conter um ambiente de desenvolvimento específico. 

Terceira Parte:

Criar na branch dev um projeto usando Heroku
Nessa branch, deve-se considerar que, para cada commit, o sistema deve ser executado automaticamente via Heroku e disponibilizado URL para uso.

Quarta Parte:

Criar na branch staging e prod a mesma API usando Docker
Inserir a API num container e deixar disponível nas branches dentro do Heroku
Configurar os projetos de prod e staging usando Github Actions
