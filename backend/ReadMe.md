# Servidor con MongoDB y GraphQL

Traducción del inglés-GraphQL es un lenguaje de manipulación y consulta de datos de código abierto para API, y un tiempo de ejecución para completar consultas con datos existentes. GraphQL fue desarrollado internamente por Facebook en 2012 antes de ser lanzado públicamente en 2015.

El servidor esta elaborado con una API en Graphql en este caso usamos como base de datos MongoDB, la distribucion de los datos es muy simple esta de la siguiente manera;


```js
    .
    ├── node_modules
    ├── src
        ├── graphql
            ├── resolvers
                ├── index.js
                ├── Query.js
                ├── Mutation.js
            ├── schema.graphql
        ├── models
            ├── Messages.js
        ├── index.js
        ├── database.js
        ├── server.js
    ├── package.json
```
Para poder comenzar con el servidor simplemente hacer lo siguiente:

```js
npm install
```
Con esto vamos a cargar todas las dependencias que nuestro servidor ocupa para ejecutarse, una vez ya iniciado vamos a iniciar el servidor con el comando:

```js
npm run dev
```
Y listo vamos a poder ver que nuestro servidor se inicia en el puerto 3100
