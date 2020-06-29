# Desafio 1 - Maratona Full Cycle

## Informações do desafio

O primeiro desafio dessa maratona consiste em criar um "Hello Full Cycle" utilizando a linguagem Golang.
Basicamente quando o arquivo compilado for executado, deverá ser exibido: Hello Full Cycle.
Se tudo estiver funcionando de forma adequada, gere uma imagem docker que quando executada deva rodar o programa criado em Golang. 
This project uses Quarkus, the Supersonic Subatomic Java Framework.

## Como executar o programa em Go Lang

```
git clone
go run hello-fullcycle.go
```

## Como criar a imagem docker e executá-la

```
docker build -t fandrade/hello-fullcycle:latest .
docker run -it --rm --name hello-cullcycle fandrade/hello-fullcycle
```

## Executando a imagem direto do Docker Hub

```
docker run -it --rm --name hello-cullcycle fandrade/hello-fullcycle
```