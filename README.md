<<<<<<< HEAD
# PROJETO MULTINÍVEL DE INDICAÇÕES

`ANÁLISE E DESENVOLVIMENTO DE SISTEMAS`

`PROJETO EIXO 4`

`QUARTO SEMESTRE`

<!-- Descrever resumidamente, em um ou dois parágrafos, o projeto que está sendo desenvolvido. -->



## Integrantes

* Khaio Henrique De Oliveira Camargos
* Arthur Emanoel Coelho De Paula
* Giovanna Dantas Almeida da Silva
* Luiz Guilherme Martins Franchim

## Orientador

* Felipe Augusto Lara Soares

## Instruções de utilização

## Documentação da API de Usuários

### Introdução

Essa API permite realizar operações CRUD (Criar, Ler, Atualizar e Deletar) em registros de usuários. Ela utiliza o protocolo HTTP e responde em formato JSON.

### Configuração Inicial

Antes de começar a usar a API, certifique-se de:

- Ter um servidor Apache rodando e um banco de dados MySQL configurado.
- O arquivo `conexao.php` deve estar no mesmo diretório e configurado corretamente para conectar-se ao seu banco de dados.
- O banco de dados deve ter uma tabela `usuarios` com colunas `id`, `demo_balance` `password` `revshare` e `email`.

### Endpoints

A API fornece os seguintes endpoints:

1. *Listar todos os usuários*
   
   - *Método*: GET
   - *URL*: `/api.php`
   - *Resposta*: Lista de usuários em formato JSON.
   
2. *Adicionar um novo usuário*

   - *Método*: POST
   - *URL*: `/api.php`
   - *Corpo da Requisição*: JSON com email, password e demo_balance do usuário. Exemplo:
     json
     {
       "email": "joao@email.com"
       "password": "jaodograu123"
       "demo_balance": "100000"
     
     }
     
   - *Resposta*: Mensagem de sucesso ou erro em formato JSON.

3. *Atualizar um usuário*

   - *Método*: PUT
   - *URL*: `/api.php`
   - *Corpo da Requisição*: JSON com id, nome e email do usuário a ser atualizado. Exemplo:
     json
     {
       "id": "3",
       "nome": "João Atualizado",
       "email": "joao_atualizado@email.com"
     }
     
   - *Resposta*: Mensagem de sucesso ou erro em formato JSON.

4. *Deletar um usuário*

   - *Método*: DELETE
   - *URL*: `/api.php`
   - *Corpo da Requisição*: JSON contendo o id do usuário a ser deletado. Exemplo:
     json
     {
       "id": "3"
     }
     
   - *Resposta*: Mensagem de sucesso ou erro em formato JSON.

### Ferramentas Recomendadas

- *Postman*: Uma ferramenta gráfica que permite testar e interagir facilmente com APIs.
- *cURL*: Uma ferramenta de linha de comando para fazer requisições HTTP.

### Notas

- A função `sanitize` é utilizada para prevenir SQL Injection. Certifique-se de sempre usar essa função ao lidar com entradas de usuários.
- Sempre que fizer alterações no código, certifique-se de testar a funcionalidade em um ambiente seguro antes de implantar em produção.

Espero que essa documentação seja útil! Se você planeja expandir essa API ou criar APIs adicionais, recomendo explorar frameworks PHP específicos para desenvolvimento de API, como Lumen ou Slim, que fornecem muitas ferramentas e recursos para facilitar esse processo.

# Documentação

<ol>
<li><a href="docs/01-Documentação de Contexto.md"> Documentação de Contexto</a></li>
<li><a href="docs/02-Especificação do Projeto.md"> Especificação do Projeto</a></li>
<li><a href="docs/03-Metodologia.md"> Metodologia</a></li>
<li><a href="docs/04-Projeto de Interface.md"> Projeto de Interface</a></li>
<li><a href="docs/05-Arquitetura da Solução.md"> Arquitetura da Solução</a></li>
<li><a href="docs/06-Template Padrão da Aplicação.md"> Template Padrão da Aplicação</a></li>
<li><a href="docs/07-Programação de Funcionalidades.md"> Programação de Funcionalidades</a></li>
<li><a href="docs/08-Plano de Testes de Software.md"> Plano de Testes de Software</a></li>
<li><a href="docs/09-Registro de Testes de Software.md"> Registro de Testes de Software</a></li>
<li><a href="docs/10-Plano de Testes de Usabilidade.md"> Plano de Testes de Usabilidade</a></li>
<li><a href="docs/11-Registro de Testes de Usabilidade.md"> Registro de Testes de Usabilidade</a></li>
<li><a href="docs/12-Apresentação do Projeto.md"> Apresentação do Projeto</a></li>
<li><a href="docs/13-Referências.md"> Referências</a></li>
</ol>

# Código

<li><a href="src/README.md"> Código Fonte</a></li>

# Apresentação

<li><a href="presentation/README.md"> Apresentação da solução</a></li>
=======
# PROJETO MULTINÍVEL DE INDICAÇÕES

`ANÁLISE E DESENVOLVIMENTO DE SISTEMAS`

`PROJETO EIXO 4`

`QUARTO SEMESTRE`

<!-- Descrever resumidamente, em um ou dois parágrafos, o projeto que está sendo desenvolvido. -->



## Integrantes

* Khaio Henrique De Oliveira Camargos
* Arthur Emanoel Coelho De Paula
* Giovanna Dantas Almeida da Silva
* Luiz Guilherme Martins Franchim

## Orientador

* Felipe Augusto Lara Soares

## Instruções de utilização

## Documentação da API de Usuários

### Introdução

Essa API permite realizar operações CRUD (Criar, Ler, Atualizar e Deletar) em registros de usuários. Ela utiliza o protocolo HTTP e responde em formato JSON.

### Configuração Inicial

Antes de começar a usar a API, certifique-se de:

- Ter um servidor Apache rodando e um banco de dados MySQL configurado.
- O arquivo `conexao.php` deve estar no mesmo diretório e configurado corretamente para conectar-se ao seu banco de dados.
- O banco de dados deve ter uma tabela `usuarios` com colunas `id`, `nome` e `email`.

### Endpoints

A API fornece os seguintes endpoints:

1. *Listar todos os usuários*
   
   - *Método*: GET
   - *URL*: `/api.php`
   - *Resposta*: Lista de usuários em formato JSON.
   
2. *Adicionar um novo usuário*

   - *Método*: POST
   - *URL*: `/api.php`
   - *Corpo da Requisição*: JSON com nome e email do usuário. Exemplo:
     json
     {
       "nome": "João",
       "email": "joao@email.com"
     }
     
   - *Resposta*: Mensagem de sucesso ou erro em formato JSON.

3. *Atualizar um usuário*

   - *Método*: PUT
   - *URL*: `/api.php`
   - *Corpo da Requisição*: JSON com id, nome e email do usuário a ser atualizado. Exemplo:
     json
     {
       "id": "3",
       "nome": "João Atualizado",
       "email": "joao_atualizado@email.com"
     }
     
   - *Resposta*: Mensagem de sucesso ou erro em formato JSON.

4. *Deletar um usuário*

   - *Método*: DELETE
   - *URL*: `/api.php`
   - *Corpo da Requisição*: JSON contendo o id do usuário a ser deletado. Exemplo:
     json
     {
       "id": "3"
     }
     
   - *Resposta*: Mensagem de sucesso ou erro em formato JSON.

### Ferramentas Recomendadas

- *Postman*: Uma ferramenta gráfica que permite testar e interagir facilmente com APIs.
- *cURL*: Uma ferramenta de linha de comando para fazer requisições HTTP.

### Notas

- A função `sanitize` é utilizada para prevenir SQL Injection. Certifique-se de sempre usar essa função ao lidar com entradas de usuários.
- Sempre que fizer alterações no código, certifique-se de testar a funcionalidade em um ambiente seguro antes de implantar em produção.

Espero que essa documentação seja útil! Se você planeja expandir essa API ou criar APIs adicionais, recomendo explorar frameworks PHP específicos para desenvolvimento de API, como Lumen ou Slim, que fornecem muitas ferramentas e recursos para facilitar esse processo.

# Documentação

<ol>
<li><a href="docs/01-Documentação de Contexto.md"> Documentação de Contexto</a></li>
<li><a href="docs/02-Especificação do Projeto.md"> Especificação do Projeto</a></li>
<li><a href="docs/03-Metodologia.md"> Metodologia</a></li>
<li><a href="docs/04-Projeto de Interface.md"> Projeto de Interface</a></li>
<li><a href="docs/05-Arquitetura da Solução.md"> Arquitetura da Solução</a></li>
<li><a href="docs/06-Template Padrão da Aplicação.md"> Template Padrão da Aplicação</a></li>
<li><a href="docs/07-Programação de Funcionalidades.md"> Programação de Funcionalidades</a></li>
<li><a href="docs/08-Plano de Testes de Software.md"> Plano de Testes de Software</a></li>
<li><a href="docs/09-Registro de Testes de Software.md"> Registro de Testes de Software</a></li>
<li><a href="docs/10-Plano de Testes de Usabilidade.md"> Plano de Testes de Usabilidade</a></li>
<li><a href="docs/11-Registro de Testes de Usabilidade.md"> Registro de Testes de Usabilidade</a></li>
<li><a href="docs/12-Apresentação do Projeto.md"> Apresentação do Projeto</a></li>
<li><a href="docs/13-Referências.md"> Referências</a></li>
</ol>

# Código

<li><a href="src/README.md"> Código Fonte</a></li>

# Apresentação

<li><a href="presentation/README.md"> Apresentação da solução</a></li>
>>>>>>> 6020707df67d57b2a08c5c77266ba1c69844049a
