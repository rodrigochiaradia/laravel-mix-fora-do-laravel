<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://fullcycle.com.br/wp-content/themes/fullcycle-blog/application/img/logo-fullcycle.png"/></a>
</p>

## Descrição

Como usar o Laravel Mix fora do ambiente do Laravel.

Ele pode ser usado com qualquer outro framework e desta vez a integração é o Nest.js.

O Laravel Mix é uma ferramenta que trabalha com o webpack para organizar os assets da aplicação WEB.

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
* Ver no package.json em scripts, todos os gatilhos com prefixo **frontend** para processar os ativos.
