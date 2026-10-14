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

Publique a imagem com o comando abaixo:

```bash
docker tag fullcycle-challenge julianepires/fullcycle:latest
docker push julianepires/fullcycle:latest
```

Execução esperada pelo avaliador:

```bash
docker run julianepires/fullcycle:latest
```
