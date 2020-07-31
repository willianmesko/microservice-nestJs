<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://fullcycle.com.br/wp-content/themes/fullcycle-blog/application/img/logo-fullcycle.png"/></a>
</p>

## Descrição

Como iniciar com projeto Nest.js com Docker

### Para Windows 

Lembrar de instalar o WSL2 e Docker. Vejo o vídeo: [https://www.youtube.com/watch?v=g4HKttouVxA](https://www.youtube.com/watch?v=g4HKttouVxA) 

Siga o guia rápido de instalação: [https://gist.github.com/argentinaluiz/6bff167be40a2bf7a6bb879062cd25cd](https://gist.github.com/argentinaluiz/6bff167be40a2bf7a6bb879062cd25cd) 

## Instalação

* Crie o volume do MySQL
``` bash
docker volume create iniciando-nestjs-dbdata
```
* Execute o projeto com o Docker:
``` bash
docker-compose up
```

## Rodar o projeto

* Acesse http://localhost:3000 para acessar o Nest.js
