# dbt_northwind

Projeto dbt Core + Postgres na AWS (RDS)

Este projeto demonstra como usar o dbt Core para transformar dados armazenados em um banco PostgreSQL na AWS (RDS).
O objetivo é criar um pipeline de transformações limpo, organizado e versionado seguindo boas práticas de engenharia de dados.

Arquitetura do Projeto
AWS RDS (PostgreSQL)  <--->  dbt Core (local / EC2 / CI/CD)
          ^
          |
      Dados brutos


O dbt se conecta ao Postgres na AWS para:

Criar tabelas e views

Padronizar camadas (staging, intermediate, marts)

Validar modelos com testes

Documentar o projeto


Ferramentas

Python 3.12.1

dbt-postgres

PostgreSQL no AWS RDS

Git (recomendado)