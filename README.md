# ponderadasemana6jeffaws

# Aplicação Web com AWS - [Kauan Massuia]

Este repositório contém o desenvolvimento de uma aplicação web integrada a um banco de dados no Amazon RDS. O objetivo era criar uma aplicação funcional com a AWS, mas, devido a dificuldades técnicas, a implementação não foi concluída com sucesso. 

## Descrição do Projeto

O projeto consistia em uma aplicação web baseada em **PHP**, com um servidor **Apache** que se conecta a um banco de dados **PostgreSQL** hospedado no **Amazon RDS**. A aplicação visava demonstrar como integrar o EC2 com o RDS da AWS e realizar operações simples de banco de dados.

Infelizmente, problemas técnicos relacionados à **configuração da instância do RDS**, **autenticação de usuários** e **comunicação entre EC2 e RDS** impediram a conclusão da aplicação.

## Estrutura do Repositório

- **templates**: Scripts PHP para a aplicação web
  - `html.index`: Página principal
- **app.py**: Script para criação da tabela de produtos (não executado)
- **create_table.sql**: define uma aplicação web simples (Teste meu)
- **README.md**: Descrição do projeto

## Tecnologias Utilizadas

- **HTML**: Para a interface de usuário
- **PHP**: Lógica de backend
- **MYSQL**: Banco de dados (não configurado corretamente)
- **Apache**: Servidor Web
- **AWS**: Utilização de EC2 e RDS

## Funcionalidades

- Exibir nome e email
- Cadastro de novos usuários com nome e email

## Problemas Não Resolvidos

Durante o desenvolvimento, alguns problemas técnicos impediram a conclusão do projeto:

1. **Erro de Conexão com o Banco de Dados**: Apesar de tentativas de conexão com o RDS, houve falhas na autenticação e configurações da VPC, o que bloqueou a conexão entre a instância EC2 e o banco de dados.
2. **Criação da Tabela de Produtos**: O script `create_table_produto.sql` foi preparado, mas devido ao erro de conexão, não foi possível criar a tabela no banco de dados.
3. **Falta de Dados**: Como a tabela não pôde ser criada, a funcionalidade de cadastro e listagem de produtos não foi possível de ser testada.

## Configuração e Instalação

1. A configuração da instância RDS foi planejada, mas não concluída com sucesso devido a erros técnicos.
2. O script SQL para criação da tabela de produtos está pronto, mas não foi executado devido à falha na conexão com o banco de dados.
3. A aplicação estava configurada para ser acessada via EC2, mas os problemas de comunicação entre EC2 e RDS impediram o acesso completo.


## Link para o vídeo explicativo

[Clique aqui para o vídeo explicativo]([https://youtu.be/THzMKA1IcZY](https://youtu.be/wr6VCTDvCMU))
