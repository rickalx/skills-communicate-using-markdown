# Header
## h2
### h3
#### h4
![Image of ladscape](https://images.freeimages.com/image/previews/6e4/river-sunset-nature-png-5690483.png)

``` javascript
function imprimirTriangulo(altura) {
  for (let i = 1; i <= altura; i++) {
    // Imprime la i-ésima fila del triángulo
    let fila = "";
    for (let j = 1; j <= i; j++) {
      fila += "*";
    }
    console.log(fila);
  }
}

// Ejemplo de uso
imprimirTriangulo(5);
```
