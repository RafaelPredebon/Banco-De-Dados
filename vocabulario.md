# 🖥Banco De Dados

## SGBDs
Data Base Management System ou Sistema de Gerenciamento de Banco de Dados (SGBD) é um conjunto de software utilizado para o gerenciamento de uma base de dados, responsáveis por controlar, acessar, organizar e proteger as informações de uma aplicação, tendo como principal objetivo gerenciar as bases de dados utilizadas por aplicações clientes e remover esta responsabilidade das mesmas.

Muito utilizado por diversas organizações, é uma forma de concentrar toda base de dados empresarial em um único lugar, provendo a facilidade na hora da sua consulta e protegendo assim as informações, que são primordiais e essenciais para toda a organização.

## Restrições em banco de dados
Restrições são regras que limitaem os valores que podem ser inseridos, excluídos ou atualizados em uma tabela. Uma restrição de chave primária é uma coluna ou combinação de colunas que tem as mesmas propriedades de uma restrição exclusiva.

## Modelo relacional
O modelo relacional é um modelo de dados representativo (ou de implementação), adequado a ser o modelo subjacente de um Sistema Gerenciador de Banco de Dados (SGBD), que se baseia no princípio de que todos os dados estão armazenados em tabelas (ou, matematicamente falando, relações).

## Modelagem conceitual
O que é Modelagem Conceitual? É a fase que vem após a análise de requisitos em um projeto de banco de dados. Nesta etapa, traduzimos os requisitos em diagramas e modelos para representar visualmente os conceitos e processos de negócio identificados anteriormente.16 de fev. de 2024

## Modelagem logica
O objetivo é desenvolver um esquema de banco de dados que possa ser implementado em um sistema de gerenciamento de banco de dados específico. Traduz o modelo conceitual para a linguagem do SGBD escolhido (MySQL, PostgreSQL, etc.). Define: Tipos de dados (inteiro, string, etc.).

## Modelagem fisica
A modelagem física de dados é o terceiro de três estágios sequenciais na modelagem de dados. Designers de banco de dados produzem modelos físicos de dados elaborando os modelos criados nas etapas de modelagem conceitual e lógica de dados. Os modelos criados nesta fase permitem a desnormalização gerenciada e levam em consideração a tecnologia alvo para implementação. Eles são completos o suficiente para representar o design do banco de dados como implementado, ou como pretendido para ser implementado

## Linguagem SQL
A Linguagem de consulta estruturada (SQL) é uma linguagem de programação para armazenar e processar informações em um banco de dados relacional. Um banco de dados relacional armazena informações em formato tabular, com linhas e colunas representando diferentes atributos de dados e as várias relações entre os valores dos dados. Você pode usar instruções SQL para armazenar, atualizar, remover, pesquisar e recuperar informações do banco de dados. Também pode usar SQL para manter e otimizar a performance do banco de dados.

## Data Definition Language (DDL)
DDL ou Data Definition Language (Linguagem de Definição de dados) permite ao usuário definir as novas tabelas e os elementos que serão associados a elas. É responsável pelos comandos de criação e alteração no banco de dados, sendo composto por três comandos: CREATE, ALTER e DROP.

## Data Manipulation Language (DML)
O DML é uma sala destinada ao armazenamento correto dos produtos e ferramentas de limpeza. Sua importância é fundamental na organização dos materiais, evitando o desperdício com vencimento de produtos, recompras desnecessárias e promovendo seu fácil acesso

## Boas práticas em modelagem de banco de dados
1- Normalização: Organize os dados em tabelas para evitar redundâncias e dependências desnecessárias.

2- Chaves Primárias: Cada tabela deve ter uma chave primária única para identificar exclusivamente cada registro.

3- Chaves Estrangeiras: Utilize chaves estrangeiras para estabelecer relacionamentos entre tabelas e garantir integridade referencial.

4- Índices: Crie índices em colunas frequentemente usadas em consultas para otimizar o desempenho das operações de busca.

5- Restrições de Integridade: Defina restrições como NOT NULL, UNIQUE, CHECK para manter a consistência e a validade dos dados armazenados.

