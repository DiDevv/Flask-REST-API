Essas anotações foram feitas no Collab, mas, ao transferir para cá ele deu problema na visualização, então, vou deixar assim mesmo!

# Anotações: API Rest em Python com Flask

## O que será abordado no tópico 1

> O que é uma API
> 
> 
> O que é REST
> 
> O que é uma REST API
> 
> Métodos do Protocolo HTTP
> 
> XML e JSON
> 
> URL, URN, URI
> 
> Framework Flask
> 

## 1. O que é uma API?

Uma API é um conjunto de rotinas que utilizamos para acessar softwares e aplicativos baseados na Web. São importantes para fazer integrações de softwares e serviços.

As APIs podem ser locais, web e baseadas em programas.

## 2. O que é REST?

REST é um modelo de criação de arquitetura de Software baseado em comunicação em comunicação via REDE.

Do inglês Representation State Transfer - Transferência de Estado Representacional.

O REST cria a ideia de que todos os recursos devem responder aos mesmos métodos.

## 3. O que é uma REST API?

É uma API desenvolvida no modelo REST, é utilizado em comunicações com softwares web e é consumido através de requisições HTTP. 

Geralmente seus formatos são em JSON e XML. Também são utilizados páginas PDF, HTML e arquivos de imagem.

Ao implementar uma REST API, cada método tem que ser responsável por uma ação diferente seja ela: ADICIONAR, CONSULTAR, ALTERAR E DELETAR.

## 4. Principais métodos do HTTP

GET - Solicita um recurso ou objeto do servidor por meio da URI

POST - Envia arquivos/dados ou formulários HTML através do servidor

PUT - Aceitar, criar ou modificar um objeto do servidor

DELETE - Informa por meio da URI o objeto que vai ser deletado

## 5. URL vs URN vs URI

URL é um Localizador de Recursos Universal

Exemplo: Host que será acessado; globallabs.academy

URN é o nome do recurso universal

Exemplo: É o recurso que será identificado; /category/blog/

URI é o identificador de Recursos Universal

Exemplo: É o identificador do recurso, podendo ser uma imagem, um arquivo ou uma página; [https://globallabs.academy/category/blog/](https://globallabs.academy/category/blog/) 

URI une Protocolo(https://), URL(globallabs.academy) e a URN(/category/blog)

## 6. XML - Extensible Markup Language e JSON - JavaScript Object Notation

XML: É uma linguagem de marcação utilizada para compartilhamento de informações através de requisições HTTP.

JSON: É um formato de troca de dados entre sistemas independente da linguagem utilizada derivada do JavaScript.

Muitas linguagens possuem suporte nativo a JSON.
