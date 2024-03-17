<p><strong> Visualizar Pagina Web : </strong><a href="https://alex030396.github.io/Primer-proyecto-web.github.io/">Front End Store</a> </p>
<h1 align="center">Segundo proyecto de programación</h1>

<p>En este proyecto se realizará una pagina web para ventas de unas camisas de programación, llevando a cabo los aprendizajes que eh adquirido. <strong>Usan HTML y CSS.</strong> </p>
</p>En la página web podrá visualizar todas las imágenes de todas las camisas de una tienda online que vende camisas de programación. Y al seleccionar cada imagen de las camisas podrás acceder a un pagina donde puedes seleccionar la cantidad de camisas que puedes solicitar. Y un segundo enlace de nosotros donde muestra los métodos de pagos e información relevante. </p>

<h2 align="center">Index.html</h2>
<p> En este índex usamos un icono que al hacer clic en el te envía directamente a la página principal </p>
  
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Front End</title>
    <link rel="stylesheet" href="CSS/normalize.css">
    <link href="https://fonts.googleapis.com/css2?family=Staatliches&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="CSS/style.css">
</head>
<body>
    <header class="header">
        <a href="index.html">
            <img class="header__logo" src="img/logo.png" alt="logotipo">
        </a>
```

<img  src="https://github.com/Alex030396/Segundo-Proyecto/raw/main/img/Portada.png" alt="alex" width="70%">

<h2 align="center">Style.css</h2>
<p> El estilo del CSS más usado en este proyecto fue el GRID, que su significado en español es red. En la programación hace que los iconos, imágenes o párrafos pueda se posicionados como si fuera una red o como una tabla de cuadriculas. </p>
<p> También se usó un media query para poder ajustar la página web para una Tablet. </p>

```css
/**Grid**/
.grid { 
    display: grid;   
    grid-template-columns: repeat(2 , 1fr);
    column-gap: 3rem;
    row-gap: 3rem;
}
@media (min-width: 768px){
    .grid {
        grid-template-columns: repeat(3, 1fr);
    }
```
<img  src="https://github.com/Alex030396/Segundo-Proyecto/raw/main/img/Portada_baja.png" alt="alex" width="90%" align="center" >


<h2 align="center">Visualización del proyecto</h2>
<p> Aquí se muestra el enlace de nosotros y de un producto del proyecto. Si visualizas la página web en el siguiente enlace podrás ver que cada camisa tiene su enlace personalizado.  # https://alex030396.github.io/Segundo-Proyecto/ </p>

<img  src="https://github.com/Alex030396/Segundo-Proyecto/raw/main/img/Nosotros.png" alt="alex" width="45%" align="left" ><img  src="https://github.com/Alex030396/Segundo-Proyecto/raw/main/img/Producto.png" alt="alex" width="45%" align="right" >
