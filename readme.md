# Projeto API no NodeJS

Arquivo de leitura para facilitar o entendimento futuro dessa api em nodejs que, basicamente, faz um CRUD com MongoDB.

## Antes de começar, é necessário instalar:

- [NodeJS: Necessário para as funcionalidades do back-end](https://nodejs.org/en/)

## Começar a desenvolver a api:

Crie uma pasta e dê um nome para ela, exemplo utilizando o cmd : 

``` shell
mkdir "node-api"
```

## Comandos: 

Comandos para começar a aplicação

### Package.json
``` shell
npm init -y
```
O package.json tem algumas instruções de como a aplicação deve se comportar, tendo como principal funcionalidade guardar a informação da versão das dependências do nosso projeto.

Dependências a serem instaladas:

* Express - É basicamente um micro framework, ele vai nos ajudar a lidar com rotas e views:
``` shell
npm install express
```
* CORS: 
``` shell
npm install cors
```
* Mongoose: 
``` shell
npm install mongoose
```

* Mongoose-paginate: 
``` shell
npm install mongoose-paginate
```

* Require-dir: npm install require-dir
``` shell
npm install require-dir
```

Dev Dependencies

* Mongoose: 
``` shell
npm install -d mongoose
```


## Comando para clonar o repositorio remoto
``` shell 
git clone https://github.com/robertkoch117/repository-rs-nodejs
```
#### [Robert Koch](https://github.com/robertkoch117)
