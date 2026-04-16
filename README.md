# Multimedial

## Taller multimedia


# INDICE

1.[Semana 1](#semana-1) <br>
2.[Semana 2](#semana-2) <br>
3.[Semana 3](#semana-3) <br>
4.[Semana 4](#semana-4) <br>




# Semana 1

## Ejemplo 1
```
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: white;
  /* Define que el fondo de toda la página sea blanco */

  color: black;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

MULTIMEDIAL
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```

# Semana 2

## Ejemplo 1
```
<a href="pagina2.html">Ir a la página 2</a>
index.html
```

## Ejemplo 2 (con dos paginas)
```
<!DOCTYPE html>
<html>
<head>
<title>Mi sitio</title>
</head>

<body>

<h1>Página principal</h1>

<a href="pagina2.html">Ir a la segunda página</a>

</body>
</html>
```

pagina2.html
```
<!DOCTYPE html>
<html>
<head>
<title>Página 2</title>
</head>

<body>

<h1>Esta es la segunda página</h1>

<a href="index.html">Volver a la página principal</a>

</body>
</html>
```

## Ejemplo 3 (abrir el link en otra pestaña)
```
<a href="https://www.wikipedia.org" target="_blank">Ir a Wikipedia</a>
```

# Semana 3 (mini sitio, 3 páginas conectadas)

index.html:
Para esta pagina le pedi ayuda a la IA para corregir lo que era la ubicacion y como agregarle links de contacto y obras, por lo que le escribi:

Puedes corregir este codigo, no cambies nada, solamente pon el link de obra y contacto bajo el nombre y mas pequeño y ademas agregar artista Visual bajo el nombre.

y este fue el codigo enviado por la IA:
```
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Multimedial</title>
<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: beige;
  /* Define que el fondo de toda la página sea blanco */

  color: burlywood;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  flex-direction: column;
  /* Organiza los elementos en columna para que los links queden debajo del nombre */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

  text-align: center;
  /* Centra el texto alineado */

}
/* Fin de las reglas de estilo del body */

small {
  font-size: 20px;
  /* Tamaño más pequeño para los links en comparación con los 60px del nombre */
}

a {
  color: burlywood;
  text-decoration: none;
}

</style>
</head>
<body>
Claudia Cuello
  
  <div style="font-size: 25px; margin-bottom: 10px;">Artista visual</div>
  
  <div class="bloque">
      <small>
          <a href="obra.html">Obra</a> | 
          <a href="contacto.html">Contacto</a>
      </small>
  </div>

  <img src="" alt="">

</body>
</html>
```

obra.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estructura con Divisiones</title>

    <style>
        /* Estilo general del cuerpo */
        body {
            font-family: Arial, sans-serif;
            background-color: #ecc5034d;
            margin: 0;
        }

        /* Contenedor principal */
        .contenedor {
            width: 80%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: auto;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }
    </style>
</head>

<body>

    <!-- Contenedor principal -->
    <div class="contenedor">

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <img src="img/IMG_7841.jpeg" alt="Descripción de la imagen">
            <h2>Ausencia del yo</h2>
            <p>
                Grafito sobre
                papel.
                (2.31x1.87cm)
            </p>
        </div>

        <!-- BLOQUE 2 -->
        <div class="bloque">
            <img src="img/IMG_0846.jpeg" alt="Descripción de la imagen">
            <h2>El frio de la calidez</h2>
            <p>
                Óleo sobre tela
                (bastidor de
                1.40x1.00cm)
            </p>
        </div>

        <!-- BLOQUE 3 -->
        <div class="bloque">
            <img src="img/IMG_8007.jpeg" alt="Descripción de la imagen">
            <h2>Vacio</h2>
            <p>
                Óleo sobre tela 
                (bastidor de
                70x70cm)
            </p>
        </div>
        <!-- BLOQUE 3 -->
        <div class="bloque">
            
            <a href="index.html">Inicio</a><br>
            <a href="contacto.html">Contacto</a>
        </div>
    </div>

</body>
</html>
```

contacto.html:
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estructura con Divisiones</title>

    <style>
        /* Estilo general del cuerpo */
        body {
            font-family: Arial, sans-serif;
            background-color: #c6a70e57;
            margin: 0;
        }

        /* Contenedor principal */
        .contenedor {
            width: 80%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: auto;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }
    </style>
</head>

<body>

    <!-- Contenedor principal -->
    <div class="contenedor">
        <h1>Contacto</h1>

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <img src="" alt="">
            <h2></h2>
            <p>
                Correo: Clau.cuello1@gmail.com

            </p>

            <p>

                Telefono: +569 49968052

            </p>
        </div>

            <a href="index.html">Inicio</a><br>
            <a href="obra.html">Obra</a>
       
    </div>

</body>
</html>
```




# Semana 4
