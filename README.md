# Lista de erros <img src="https://cdn.worldvectorlogo.com/logos/nodejs.svg" alt="NodeJS" style="height: 14%; width: 14%;"/>

- [Lista de erros <img src="https://cdn.worldvectorlogo.com/logos/nodejs.svg" alt="NodeJS" style="height: 5%; width: 5%;"/>](#lista-de-erros-)
    - [1 - Cannot find module](#1---cannot-find-module)
        - [Como resolver](#como-resolver)
    - [2 - Is not defined](#2---is-not-defined)
        - [Como resolver](#como-resolver-1)
    - [Is not a function](#is-not-a-function)
        - [Como resolver](#como-resolver-2)
    - [Unexpected token](#unexpected-token)
        - [Como resolver](#como-resolver-3)
    - [Is not a constructor](#is-not-a-constructor)
        - [Como resolver](#como-resolver-4)
    - [Mais Informações](#mais-informações)

### 1 - Cannot find module

Esse erro significa que o node não conseguiu encontrar tal módulo.

##### Como resolver

> Caso seja de um módulo do npmjs

- Instale o módulo usando `npm i módulo`

> Caso não seja

- Mude o caminho no require

### 2 - Is not defined

Significa que certa property, variável não foi definida.

##### Como resolver

> Caso seja de uma certa variável

- Definina ela usando const/let/var

> Caso seja uma property

- Faça um if para verificar se a property não é do tipo undefined. (Exemplo: if (typeof property !== 'undefined') // seu código)


### 3 - Is not a function
Significa que tal property/variável não é uma função

##### Como resolver
Remova os ()/.call()/.bind() dessa property/variável

### 4 - Unexpected token
Siginifica que tal token/caráctere não foi esperado

##### Como resolver
Remova esse caráctere

### 5 - Is not a constructor
Significa que tal função/classe não é um constructor

##### Como resolver
Adicione um constructor à ela ou remova o new


### [Mais Informações](https://github.com/nodejs/node/blob/master/doc/api/errors.md)
