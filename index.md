# Exemplos com canvas

Edite esta página no [github](https://github.com/vini060911/projetos-canvas/edit/gh-pages/index.md).

### Quadrado

Exemplo de um quadrado usando um canvas html.

Código html:
```html
<!DOCTYPE html>

<html>
  <head>
    <title>Quadrado - canvas</title>
  </head>
  <body>
    <canvas></canvas>
  </body>
</html>
```
Código JavaScript:
```javascript
var canvas = document.querySelector("canvas")
var ctx = canvas.getContext("2d")

ctx.fillRect(50, 50, 10, 10)
```
