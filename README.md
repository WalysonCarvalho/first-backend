NoteList Backend
Este projeto é uma API backend desenvolvida com Node.js e Express que gerencia um sistema de cadastro de notas, utilizando o banco de dados SQLite. A API permite criar, atualizar e deletar cadastros, além de gerenciar notas vinculadas a links e tags, com suporte a deleção em cascata. A API foi testada usando o Insomnia.

Funcionalidades
Cadastro de Usuário:

Criação de novos usuários com informações de email e senha.
Validação de email e senha no momento do login, retornando erros apropriados em caso de dados incorretos.
Atualização de Cadastro:

Atualização das informações do usuário, incluindo email e senha.
Gestão de Notas:

Criação de notas associadas a links e tags.
Deleção de notas com suporte a deleção em cascata, o que remove automaticamente os links e tags associados.
Verificação de Credenciais:

Validação de credenciais no login, verificando se o email e senha estão corretos e retornando mensagens de erro apropriadas em caso de falha.
Tecnologias Utilizadas
Node.js: Plataforma de desenvolvimento.
Express: Framework web para Node.js, utilizado para criar a API.
SQLite: Banco de dados relacional usado para armazenar as informações de usuários, notas, links e tags.
