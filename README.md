# fullcycle-docker-challenge

Aplicação Go mínima para o desafio Full Cycle Docker.

## Resultado esperado

Ao executar o container, a saída deve ser:

```bash
Full Cycle Rocks!!
```

## Build e execução local

```bash
docker build -t fullcycle-challenge .
docker run --rm fullcycle-challenge
```

## Imagem no Docker Hub

Publique a imagem com o comando abaixo (substitua `<seu-usuario>`):

```bash
docker tag fullcycle-challenge <seu-usuario>/fullcycle:latest
docker push <seu-usuario>/fullcycle:latest
```

Execução esperada pelo avaliador:

```bash
docker run <seu-usuario>/fullcycle:latest
```
