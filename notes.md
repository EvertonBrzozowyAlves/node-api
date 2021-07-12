# Node

## Inicializando

Inicializar um novo projeto Node:
```bash
npm init -y
```

Instalando pacotes (separados por espaço):
```bash
npm install http express debug --save
```
>Save para adicionar aos node_modules. Essa pasta fica local, não enviamos ao server.

Quando baixar uma aplicação node, basta executar o comando de install para instalar os pacotes de dependência:
```bash
npm install
```

Para importar módulos no node, usamos a sintaxe abaixo:
```javascript
const express = require('express');
```
>Tudo que passarmos sem um caminho nas aspas, será buscado na pasta node_modules

Caso queira importar algo fora da pasta node_modules:
```javascript
const teste = require('./path/to/file');
```