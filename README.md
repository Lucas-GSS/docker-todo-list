<h1 align="center">
  <p align="center">Docker ToDo List</p>
  <a href="https://www.docker.com/" target="_blank"/>
    <img src="https://cdn.iconscout.com/icon/free/png-512/free-docker-10-1175197.png?f=avif&w=256" alt="Docker Logo">
  </a>
</h1>

<p>
  <img src="https://img.shields.io/badge/Docker-version%2024.0.1-blue" alt="docker version badge">
  <img src="https://img.shields.io/badge/Docker--Compose-version%202.5.0-orange" alt="docker compose version badge">
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-green" alt="status badge">
</p>

## Descrição
Projeto desenvolvido no módulo de BackEnd do Curso de Desenvolvimento Web Full Stack da Trybe. Este projeto tem como objetivo criar e gerenciar containers por meio do Docker, além disso, criar imagens para aplicações de Front(React), Back(NodeJs) e testes(jest) e orquestrar containers por meio do Docker Compose.

A primeira parte do projeto consiste em executar diversos comandos, com diferentes níveis de complexidade, para a criação e manipulação de containers Docker. Tais comandos podem ser encontrados nos arquivos de extensão .dc em: `/docker/docker-commands/`

A parte final do projeto exige a criação de Dockerfiles para cada parte da aplicação FullStack ToDo List. Além disso, foi pedido a criação de um arquivo `docker-compose.yaml` para orquestrar o funcionamento e a comunicação dos containers criados a partir dos Dockerfiles. O Dockerfile de cada parte da aplicação se encontra dentro da pasta correspondente a cada parte em: `/docker/todo-app/`.

## Acesso ao projeto
### Requisitos
Tenha o [Docker](https://docs.docker.com/engine/install/) e o [Docker Compose](https://docs.docker.com/compose/install/) instalados.

### Clone o projeto
- Faça o clone do projeto para sua máquina: `git clone git@github.com:Lucas-GSS/docker-todo-list.git`
- Entre na pasta do projeto: `cd docker-todo-list/docker`
### Interagindo com as funcionalidades
- Você pode copiar os comandos dos arquivos da pasta `docker-commands` no seu terminal e ver os resultados de cada um deles. Exemplo:

<div>
   <img src="https://github.com/Lucas-GSS/docker-todo-list/assets/84993564/a3d54faa-6c5e-4d09-9c0f-c04156d678de" alt="docker-cli-    commands" width="500px">
  <br>
  <sub align="center">Execução dos comandos 1, 2 e 4</sub>
</div> <br>

- Para subir o app ToDo List com o Docker Compose:

<div>
 <img src="https://github.com/Lucas-GSS/docker-todo-list/assets/84993564/7ae3716f-32f6-4a69-8909-e6b5ae160c02" alt="docker-compose-up" width="500px">
</div>

- Acessando o FrontEnd do app no [localhost](http://localhost:3000):

<div>
   <img src="https://github.com/Lucas-GSS/docker-todo-list/assets/84993564/3313b037-efb5-4709-ad7e-deb4c54eb697" alt="todo-list-app" width="500px">
</div>

- Rodando os testes da aplicação (pode levar alguns segundos):
<div>
  <img src="https://github.com/Lucas-GSS/docker-todo-list/assets/84993564/757a9bf6-21c1-4f96-935d-fef4de229828" alt="container-tests-output" width="500px">
</div>

- Encerrando os containers da aplicação e removendo as imagens baixadas:
<div>
  <img src="https://github.com/Lucas-GSS/docker-todo-list/assets/84993564/db188222-28d8-49d7-9069-6931fe1fa979" alt="docker-cli-output" width="500px">
</div>

## Autor
[<img src="https://avatars.githubusercontent.com/u/84993564?v=4" width=115><br><sub>Lucas Gabriel</sub>](https://github.com/Lucas-GSS)
  
