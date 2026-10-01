# Desafio Técnico – Sistema de Agendamentos

## Entrega
Para entrega enviar no chat do LinkedIn o seu repositório até 07/10.

## Contexto

Uma empresa precisa de uma aplicação para gerenciamento de agendamentos.

O sistema deverá atender dois tipos de usuários:

- **Cliente:** pessoa que deseja realizar um agendamento.
- **Administrador:** pessoa responsável por receber e gerenciar os agendamentos.

## Desafio

Desenvolva uma aplicação Full Stack utilizando:

- React + TypeScript
- Node.js + TypeScript
- Banco de dados de sua escolha
- Docker

Bibliotecas e frameworks adicionais podem ser utilizados livremente.

## Visão do Cliente

O cliente deverá conseguir:

- Consultar horários disponíveis;
- Realizar um agendamento;
- Visualizar seus agendamentos;
- Cancelar seus agendamentos.

A experiência e o fluxo dessas funcionalidades ficam a critério do candidato.

## Visão Administrativa

O administrador deverá possuir uma área para visualizar e gerenciar os agendamentos recebidos.

A forma de organizar essa área, os filtros disponíveis, os status dos agendamentos e as ações administrativas ficam a critério do candidato.

## Regras gerais

O sistema deverá:

- Evitar conflitos de horários;
- Não permitir agendamentos em horários ou datas que já passaram;
- Manter os dados dos agendamentos persistidos;
- Possuir tratamento adequado para operações inválidas.

A partir desses requisitos, o candidato deverá definir e implementar as regras de negócio que considerar necessárias para garantir o funcionamento consistente da aplicação.

## Decisões técnicas

Faz parte do desafio decidir:

- Como modelar os dados;
- Como identificar cliente e administrador;
- Como organizar frontend e backend;
- Como estruturar a API;
- Como tratar disponibilidade de horários;
- Como impedir conflitos de agendamento;
- Como representar os diferentes estados de um agendamento;
- Como realizar validações;
- Como persistir os dados;
- Como executar a aplicação utilizando Docker.

Não existe uma única arquitetura esperada.

As decisões tomadas deverão poder ser explicadas posteriormente durante a etapa técnica.

## Docker

A aplicação deverá ser executável utilizando Docker.

Preferencialmente, o projeto completo deverá poder ser iniciado através do comando:

```bash
docker compose up --build
