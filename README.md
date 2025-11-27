#🚗SISTEMA DE GERENCIAMENTO DE CONCESSIONÁRIA (SGC) *****

>⚠️**ATENÇÃO:**Este projeto encontra-se em fase ativa de DESENVOLVIMENTO!

Este é um sistema web robusto, projetado para gerenciar todas as operações de uma concessionária de veículos, abrangendo o controle de clientes, funcionários, inventário (marcas e modelos) e operações de vendas.
A solução é construída com PHP, MySQL e o framework Bootstrap, rodando em um ambiente local XAMPP.

-------------------------------------------------------------

## ⚙️ Tecnologias Utilizadas

- **PHP** — Lógica de programação e manipulação de dados  
- **MySQL** — Banco de dados relacional  
- **HTML / CSS / JavaScript**  
- **Bootstrap** — Interface visual responsiva  
- **XAMPP** — Servidor local (Apache + MySQL)

-------------------------------------------------------------

##🚀FUNCIONALIDADES PRINCIPAIS (CRUD)

O sistema implementa o ciclo completo do CRUD (Create, Read, Update, Delete) nos seguintes módulos:

✅ Clientes: Cadastro, listagem, edição e exclusão de registros.

✅ Funcionários: Cadastro, listagem, edição e exclusão de colaboradores.

✅ Inventário: Gestão de marcas e modelos de veículos.

✅ Vendas: Registro e consulta de todas as transações de vendas.

✅ Integração: Conectividade total e nativa com o servidor MySQL.

-------------------------------------------------------------

##🧠CONCEITOS TÉCNICOS APLICADOS

CRUD: Aplicação rigorosa dos princípios de manipulação de dados.

Conexão Segura: Uso da biblioteca mysqli para comunicação entre PHP e BD.

Arquitetura: Estrutura modular de código com páginas dinâmicas.

Interação Web: Utilização correta dos métodos HTTP (POST e GET) para o manuseio de formulários.

-------------------------------------------------------------

##💾GUIA DE EXECUÇÃO E INSTALAÇÃO LOCAL

Instalação do XAMPP:
Instale o XAMPP e confirme que os módulos Apache e MySQL estão ativos.

Cópia do Projeto (Deployment):
Copie a pasta do projeto para o diretório do servidor:

C:\xampp\htdocs\projeto-concessionaria


Acesso ao MySQL:
Abra o painel de administração do MySQL (via Shell do XAMPP).

Criação da Base de Dados:
Crie o banco de dados conforme o nome definido no arquivo de configuração:

CREATE DATABASE concessionaria;
USE concessionaria;


Importação de Dados (SQL):
No terminal Shell do XAMPP, importe o arquivo de estrutura e dados:

SOURCE C:/xampp/htdocs/projeto-concessionaria-main/banco.sql;


Acesso Final:
Execute a aplicação no seu navegador:

http://localhost/projeto-concessionaria-main/index.php
