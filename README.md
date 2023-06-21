# Desafio Imersão Fullcycle 13 :: Docker

O arquivo Docker file a ser avaliado, encontra-se na pasta .docker. O Dockerfile da raiz é utilizado para configuração do ambiente de
desenvolvimento.

## Build da imagem docker

Execute o comando
``` bash
docker build . -t [nome da imagem] -f ./.docker/Dockerfile
```

## Para executar a imagem

Execute o comando
``` bash
docker run --rm [nome da imagem]
```
