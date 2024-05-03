# VLACSS1
Practica CSS 1 

# Apuntes de la clase 02 05 2024

Un Div con 3 parrafos con el texto Cliente 1,2 , 3 
div.pato#cliente>p{Cliente $}*3

Un Div con una clase y un Id hijos lista con  enlaces 5

div.clase#id>ul>li*5>a{texto $}


Hacer 4 Div con la clase Caja cada una con P 
<div class="caja">
    <p>texto 1</p>
</div>
<div class="caja">
    <p>texto 2</p>
</div>
<div class="caja">
    <p>texto 3</p>
</div>
<div class="caja">
    <p>texto 4</p>
</div>   
Hacer un Div y adentro van a crear 3 div con clase caja cada una con P con el texto Hola Mundo 1,2,3
div>div.caja*3>p{Hola mundo $}


Atajo: header.logo>img[src="Img/pikachu.pgg"][alt="logo"]
<header class="logo">
    <img src="Img/pikachu.pgg" alt="logo">
</header>


Atajo: nav>ul>li*4>a[href="#"]{Enlace $}
<nav>
    <ul>
        <li><a href="#">Enlace 1</a></li>
        <li><a href="#">Enlace 2</a></li>
        <li><a href="#">Enlace 3</a></li>
        <li><a href="#">Enlace 4</a></li>
    </ul>
</nav>

Crear un Main con una seccion , 
adentro de la seccion colocar 3 articulos cada uno con h2 texto un parrafo adentro del parrafo un enlace y una imagen 
main>section>article*3>h2{titulo}+p>a[href="#"]+img[src="ruta"]
<main>
    <section>
        <article>
            <h2>titulo</h2>
            <p><a href="#"></a><img src="ruta" alt=""></p>
        </article>
        <article>
            <h2>titulo</h2>
            <p><a href="#"></a><img src="ruta" alt=""></p>
        </article>
        <article>
            <h2>titulo</h2>
            <p><a href="#"></a><img src="ruta" alt=""></p>
        </article>
    </section>

    <aside class="barra">
        <h2>titulo</h2>
        <p>texto</p>
    </aside>
</main>
footer>p+ul>li*3>a{texto}
<footer>
    <p></p>
    <ul>
        <li><a href="">texto</a></li>
        <li><a href="">texto</a></li>
        <li><a href="">texto</a></li>
    </ul>
</footer>