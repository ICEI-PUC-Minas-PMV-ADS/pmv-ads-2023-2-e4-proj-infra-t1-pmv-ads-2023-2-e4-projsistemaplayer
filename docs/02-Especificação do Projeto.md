# Especificações do Projeto

## Problema
Usuários, sejam eles estudantes, instrutores ou instituições educacionais, enfrentam dificuldades em encontrar um espaço centralizado que ofereça uma experiência de aprendizado online semelhante às plataformas de streaming populares.

## Ideias de solução
Desenvolver um software de streaming educacional que combina a facilidade de uso das plataformas de entretenimento com a flexibilidade do aprendizado online, tudo por meio de uma assinatura mensal.

## Personas

### 1.João

Idade: 20 anos.

Descrição: Estudante universitário que busca complementar sua formação.

Necessidade: Conteúdo educacional diversificado e de qualidade.

### 2.Maria

Idade: 35 anos.

Descrição: Professora que deseja expandir seu alcance online.

Necessidade: Plataforma simples para hospedar seus cursos.

### 3.Instituto Mix - Mateus Leme

Descrição: Instituição tradicional buscando inovar no ambiente digital.

Necessidade: Ferramenta que facilite a transição do ensino presencial para o digital.

## Histórias de Usuários

|EU COMO... `PERSONA`               | QUERO/PRECISO ... `FUNCIONALIDADE`                                 |PARA ... `MOTIVO`                                        |
|----------------------------------|---------------------------------------------------------------------|--------------------------------------------------------------|
|João, estudante universitário     | Acessar conteúdo educacional diversificado                          | Complementar minha formação com qualidade                    |
|Maria, professora                 | Ter uma plataforma simples para hospedar meus cursos                | Expandir meu alcance e ensinar online de forma eficiente     |
|Instituto Mix - Mateus Leme       | Utilizar uma ferramenta que facilite a transição para ensino digital| Inovar e adaptar-se às demandas atuais de ensino             |

## Requisitos

### Requisitos Funcionais

|ID    | Descrição do Requisito                                                | Prioridade |
|------|-----------------------------------------------------------------------|------------|
|RF-001| Permitir que o usuário crie sua conta                                 | ALTA      |
|RF-002| Permitir que o usuário faça login                                      | ALTA      |
|RF-003| Oferecer um sistema de busca para o usuário encontrar conteúdo desejado | ALTA      |
|RF-004| Permitir que o usuário acesse apenas uma sessão por vez                | ALTA      |
|RF-005| Permitir que o usuário recupere sua senha                              | MÉDIA     |

### Requisitos não Funcionais

|ID     | Descrição do Requisito                                               |Prioridade |
|-------|----------------------------------------------------------------------|-----------|
|RNF-001| O sistema deve ser responsivo para rodar em dispositivos móveis      | ALTA      |
|RNF-002| O login deve ser seguro e encriptado                                 | ALTA      |
|RNF-003| O sistema de busca deve retornar resultados em no máximo 2 segundos  | ALTA      |
|RNF-004| O sistema deve detectar e encerrar sessões simultâneas do mesmo usuário | MÉDIA |
|RNF-005| Todos os dados de usuário devem ser armazenados de forma segura      | ALTA      |

## Restrições

|ID| Restrição                                               |
|--|---------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre   |
|02| O sistema não deve armazenar senhas em texto puro       |


# documentação da Arquitetura Distribuída do projeto
# documentação da Arquitetura Distribuída do projeto
# documentação da Arquitetura Distribuída do projeto
# documentação da Arquitetura Distribuída do projeto

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)


# Matriz de Rastreabilidade dos Requisitos

| ID Requisito | Descrição                                          | Casos de Uso Associados |
|--------------|----------------------------------------------------|-------------------------|
| RF-001       | Permitir que o usuário crie sua conta              | UC-001                  |
| RF-002       | Permitir que o usuário faça login                  | UC-002                  |
| RF-003       | Permitir que o usuário encontre o conteúdo desejado| UC-003, UC-004          |
| RF-004       | Garantir que o usuário logue em apenas uma sessão | UC-005                  |
| RNF-001      | O sistema deve ser responsivo                      | UC-006                  |
| RNF-002      | Resposta de requisição em no máximo 2s             | UC-007                  |


# Planejamento do Projeto

## Cronograma

| Atividade                             | Início      | Fim         | Duração |
|---------------------------------------|-------------|-------------|---------|
| Planejamento Inicial                  | 01/10/2023  | 07/10/2023  | 7 dias  |
| Design da Interface do Usuário       | 08/10/2023  | 21/10/2023  | 14 dias |
| Desenvolvimento da Base de Dados      | 22/10/2023  | 05/11/2023  | 15 dias |
| Implementação das Funcionalidades    | 06/11/2023  | 20/11/2023  | 15 dias |
| Testes Iniciais                       | 21/11/2023  | 30/11/2023  | 10 dias |
| Feedback e Iteração                   | 01/12/2023  | 10/12/2023  | 10 dias |
| Testes Finais e Ajustes               | 11/12/2023  | 20/12/2023  | 10 dias |

## Custos

| Item                                  | Custo Estimado  |
|---------------------------------------|-----------------|
| Salários da equipe de desenvolvimento | R$24,00/mês        |
| Hospedagem e infraestrutura           | R$100/mês       |
| Licenças de Cursos                    | R$5.000          |
| Marketing e Publicidade               | R$15.000/mês          |
| Outros (imprevistos, taxas, etc.)     | R$800           |
| **Total Estimado**                    | **R$20.924**     |

## Pessoal

| Cargo                        | Quantidade | Descrição                                           |
|------------------------------|------------|-----------------------------------------------------|
| Gerente de Projeto           | 2         | Responsável pela coordenação e supervisão do projeto |
| Desenvolvedor Front-end      | 2          | Criação e design da interface do usuário            |
| Desenvolvedor Back-end       | 2          | Implementação da lógica e gestão da base de dados    |
| Designer UX/UI               | 2          | Projetar a experiência do usuário                    |
| Testador                     | 2          | Responsável pelos testes de qualidade do software    |

---

Reforço que esses valores são fictícios e simplificados para fins ilustrativos. O planejamento real do seu projeto deve ser baseado em informações detalhadas, pesquisas e estimativas mais precisas.



# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
