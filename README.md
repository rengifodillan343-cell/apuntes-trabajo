<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurante Sabor Gourmet</title>

    <!-- Conecta el CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Barra de navegación -->
    <nav>
        <h1>Sabor Gourmet</h1>

        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#menu">Menú</a></li>
            <li><a href="#galeria">Galería</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>

    <!-- Sección inicio -->
    <section id="inicio">
        <h2>Bienvenido a Sabor Gourmet</h2>
        <p>
            Disfruta de los mejores platos, postres y bebidas
            en un ambiente único.
        </p>
    </section>

    <!-- Sección menú -->
    <section id="menu">
        <h2>Nuestro Menú</h2>

        <div class="platos">
            <div class="card">
                <img src="https://via.placeholder.com/250" alt="Hamburguesa">
                <h3>Hamburguesa Especial</h3>
                <p>$18.000</p>
            </div>

            <div class="card">
                <img src="https://via.placeholder.com/250" alt="Pizza">
                <h3>Pizza Italiana</h3>
                <p>$25.000</p>
            </div>

            <div class="card">
                <img src="https://via.placeholder.com/250" alt="Pasta">
                <h3>Pasta Alfredo</h3>
                <p>$20.000</p>
            </div>
        </div>
    </section>

    <!-- Sección galería -->
    <section id="galeria">
        <h2>Galería</h2>

        <img src="https://via.placeholder.com/300" alt="Restaurante">
        <img src="https://via.placeholder.com/300" alt="Comida">
        <img src="https://via.placeholder.com/300" alt="Postre">
    </section>

    <!-- Formulario contacto -->
    <section id="contacto">
        <h2>Reserva tu mesa</h2>

        <form>
            <input type="text" placeholder="Tu nombre">
            <input type="email" placeholder="Tu correo">
            <textarea placeholder="Mensaje"></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Pie de página -->
    <footer>
        <p>© 2026 Sabor Gourmet - Todos los derechos reservados</p>
    </footer>

</body>
</html>


CSS---------------------//////--------------------------------------------------------////////////////------------------------------------------------------------
body{
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4f4f4;
    text-align: center;
}

/* Barra superior */
nav{
    background-color: black;
    color: white;
    padding: 20px;
    display: flex;
    justify-content: space-between;
}

nav ul{
    list-style: none;
    display: flex;
    gap: 20px;
}

nav a{
    color: white;
    text-decoration: none;
}

/* Secciones */
section{
    padding: 40px;
}

/* Cards del menú */
.platos{
    display: flex;
    justify-content: center;
    gap: 20px;
}

.card{
    background: white;
    padding: 20px;
    border-radius: 10px;
    width: 250px;
}

.card img{
    width: 100%;
}

/* Formulario */
input, textarea{
    display: block;
    margin: 10px auto;
    width: 300px;
    padding: 10px;
}

button{
    padding: 10px 20px;
}

/* Footer */
footer{
    background-color: black;
    color: white;
    padding: 15px;
}
////////-------------------------------------------///////////////////////////////////////////////-------------------------------------------------------------------------
========================================
        CHULETA RÁPIDA HTML Y CSS
========================================

HTML = estructura de la página
CSS = diseño y estilos

========================================
            ESTRUCTURA BÁSICA
========================================

<!DOCTYPE html>  → indica que es HTML5
<html>           → contiene toda la página
<head>           → configuración
<body>           → contenido visible

Ejemplo:

<!DOCTYPE html>
<html>
<head>
    <title>Mi página</title>
</head>
<body>
    <h1>Hola</h1>
</body>
</html>

========================================
          ETIQUETAS IMPORTANTES
========================================

<h1> Título principal </h1>
<p> Párrafo o texto </p>
<div> Contenedor / separador </div>
<ul> Lista desordenada </ul>
<li> Elemento de lista </li>
<a href=""> Enlace </a>
<img src=""> Imagen </img>
<form> Formulario </form>
<input> Caja para escribir
<button> Botón </button>
<nav> Barra de navegación </nav>
<section> Sección de la página </section>
<footer> Pie de página </footer>

========================================
         RESPUESTAS PARA LA PRUEBA
========================================

¿Para qué sirve DIV?
→ Sirve para agrupar y organizar elementos
  para aplicar estilos con CSS.

¿Para qué sirve UL?
→ Sirve para crear listas.

¿Para qué sirve LI?
→ Sirve para cada elemento dentro de la lista.

¿Para qué sirve NAV?
→ Sirve para la barra de navegación.

¿Para qué sirve A?
→ Sirve para crear enlaces.

¿Para qué sirve IMG?
→ Sirve para insertar imágenes.

========================================
              CSS
========================================

color: white;
→ cambia color del texto

background-color: black;
→ cambia color del fondo

font-size: 20px;
→ tamaño de letra

margin: 20px;
→ espacio por fuera

padding: 20px;
→ espacio por dentro

text-align: center;
→ centra texto

display: flex;
→ pone elementos en fila

========================================
       FRASE CLAVE PARA DECIR
========================================

HTML crea la estructura.
CSS organiza y da diseño.
apunte--------------------////////////////////////////////////////////--------------------------------------------------------------/////////////////////////////////
✨ 1) Íconos flotantes / elementos decorativos

Una forma fácil es usar círculos flotando en el fondo.

HTML

Pon esto dentro del <body>, preferiblemente arriba:

<div class="decoracion"></div>
<div class="decoracion decoracion2"></div>
<div class="decoracion decoracion3"></div>
CSS
.decoracion{
    position: fixed;
    width: 100px;
    height: 100px;
    background: rgba(255,255,255,0.1);
    border-radius: 50%;
    top: 100px;
    left: 50px;
    animation: flotar 4s infinite ease-in-out;
}

.decoracion2{
    top: 300px;
    left: 80%;
    width: 70px;
    height: 70px;
}

.decoracion3{
    top: 500px;
    left: 20%;
    width: 120px;
    height: 120px;
}
🎥 2) Animación flotante

Esto hace que suban y bajen.

@keyframes flotar{
    0%{
        transform: translateY(0px);
    }
    50%{
        transform: translateY(-20px);
    }
    100%{
        transform: translateY(0px);
    }
}
🧠 Cómo funciona
position: fixed

Lo deja fijo en la pantalla.

position: fixed;
border-radius: 50%

Lo vuelve círculo.

border-radius: 50%;
animation

Le aplica movimiento.

animation: flotar 4s infinite;
flotar = nombre de la animación
4s = dura 4 segundos
infinite = nunca para
🌟 3) Sombra bonita en tarjetas
.card{
    box-shadow: 0px 4px 15px rgba(0,0,0,0.3);
    border-radius: 15px;
}
Explicación
box-shadow

Sombra.

box-shadow: 0px 4px 15px rgba(0,0,0,0.3);

Hace que se vea elegante.

🎯 4) Efecto hover en botones
button:hover{
    transform: scale(1.1);
}

Cuando pasas el mouse, el botón crece.

💎 5) Borde brillante
img{
    border: 3px solid white;
    border-radius: 10px;
}
🔥 Consejo

Si quieres que se vea moderno tipo tienda, usa:

sombras
bordes redondos
hover
círculos flotantes

Eso impresiona mucho en pruebas 👌

Si quieres, te hago una 
plantilla completa con todas estas decoraciones ya puc



























