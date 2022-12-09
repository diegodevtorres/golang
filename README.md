# Golang Docker Full Cycle

Desafio do módulo Docker do curso Full Cycle 3.0.

## Descrição

Arquivos que compoêm o Dockerfile de uma imagem golang com um tamanho menor que 2 MB.

## Getting Started
### Executando

* Para criar a imagem, no diretório do projeto, execute:
```
docker build . -t docker run diegodevtorres/fullcycle
```

* Após isso, execute o comando abaixo para  execute:
```
docker run -p 8080:8080 diegodevtores/fullcycle
```

* A seguinte mensagem deverá aparecer:
```
Full Cycle Rocks!!
```

* A imagem também já está disponível no docker hub, sendo possível acessá-la executando:
```
docker run diegodevtorres/fullcycle
```

## Autor

[@diegodevtorres](https://github.com/diegodevtorres)
