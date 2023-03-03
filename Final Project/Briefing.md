# O que é o sistema?

O sistema é um gerenciador de serviços de uma mecanica, no qual será possível
cadastrar serviços ,tipos de serviço, funcionarios, carros, e controlar
os status de cada serviço e gerar relatórios. 


# Dúvidas

Tipo de site: Dashboard
Objetivos do website: Gerenciamento de serviços
Será responsivo? Sim
Imagem a ser transmitida: Moderna
Quais as páginas o site terá? Home, Cadastros e listas
Será multi-language? Não
Terá recursos? Relatórioss


# Requisitos funcionais

1. Cadastrar um serviço
2. Cadastrar Produtos ( Materiais )
    1. Controle de estoque
3. Login and Roles
    1. Funcionário 
    2. Admin
4. Cadastro de Carro?
5. Informações de cliente?
6. Cadastro de ordem de serviço
    - Placa do carro ou info
    - Dados do cliente (nome, …)
    - Qual os serviços
    - Quais as peças ( opcional )
    - Prazo?
    - Descrição
    - Status
    - Urgência
    - Orçamento
    - Pago ?
    
7. Gerar relatório em xlsx
    1. Serviços
    2. Quantidade de cada serviço
    3. Receita e Despesa
    4. Peças compradas
8. Sync opcional com banco de dados e local storage

# Tech Stack

### - Frontend

- Next @latest
- React
- Tailwind

### - Backend

- Fastify
- Prisma
- PostgreSQL
