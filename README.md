
# DS- DEVELIVER

Projeto  no netlify  > https://sds2biasenario.netlify.app/


# Sobre o Projeto 


Ds Deliver é um aplicativo full stack web, construido durante a 2° edição da **semana DevSuperior** (#sds2), evento organizado pela [DevSuperior]
(https://devsuperior.com "site da DevSuperior"). 

O Projeto consiste em um sistema de registro de pedidos.  

# dsdeliver-sds2## Modelo conceitual
![Image](https://raw.githubusercontent.com/devsuperior/sds2/master/assets/modelo-conceitual.png "Modelo conceitual")

## Padrão camadas adotado

![Image](https://raw.githubusercontent.com/devsuperior/sds2/master/assets/camadas.png "Padrão camadas")

## Checklist

- Setup inicial do projeto
  - Dependências
  - Arquivos .properties
  - Configuração de segurança
- Modelo de domínio
  - Entidades e relacionamentos
  - Mapeamento objeto-relacional
  - Seed
- Criar endpoints
  - [GET] /products
  - [GET] /orders
  - [POST] /orders
  - [PUT] /orders/{id}/delivered
- Validar perfil dev
  - Base de dados Postgres local
  - Testar todos endpoints
- Preparar projeto para implantação
  - Arquivo system.properties
  - Profile prod -> commit
- Implantar projeto no Heroku
  - Criar app e provisionar Postgres
  - Criar base de dados remota
  - Executar comandos no Heroku CLI

**ATENÇÃO: O PROJETO NÃO RODA LOCALMENTE NO PROFILE PROD! Se você quiser rodar o projeto localmente depois, mude para o profile test.**
