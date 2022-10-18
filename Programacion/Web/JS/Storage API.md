`localStorage` 
Guarda datos de forma local sin fecha de expiración.

`sessionStorage` 
Guarda los datos de forma local pero son eliminados al cerrar el navegador.
---
## Uso 

```js
localStorage.setItem("clave1", "valor1");

localStorage.getItem("valor1");

localStorage.removeItem("clave1");

// Para borrar todos los valores: 
localStorage.clear();
```

> El uso de `sessionStorage` es el mismo.