PiadasClient
=
Você pode criar um client usando:
 ```js
const piadasLib = require('piadas-adg')
const PiadasClient = new piadasLib();
const piada = await PiadasClient.randomPiada()
console.log(piada); // randomPiada() = Promise
```