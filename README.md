<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initi
    <title>eFashion - Ropa y Accesorios</title>
    <link rel="stylesheet" href="estilos.css">
</head>


<body>


  
    <header>
        <div class="logo">eFashion</div>


        <nav>
            <a href="#inicio">Inicio</a>
            <a href="galeria.html">Galería</a>
            <a href="#productos">Productos</a>
            <a href="reserva.html">Reservas</a>
            <a href="#reseñas">Reseñas</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>


  
    <section id="inicio" class="inicio">
        <div>
            <h1>Bienvenido a eFashion</h1>
            <p>Ropa y accesorios directamente hasta tu puert
            <a href="#productos" class="boton">Ver productos
            <a href="galeria.html" class="boton">Ver product
            <a href="galeria.html" class="boton">Ver galería
        </div>
    </section>


   
    <section id="productos">
        <h2>Nuestros productos</h2>


        <div class="productos">


            <div class="producto">
                <div class="imagen"></div>
                <h3>Camiseta urbana</h3>
                <p>Camiseta moderna y cómoda.</p>
                <strong>$45.000</strong>
                <button onclick="window.location.href='reser
                    Reservar
                </button>
            </div>


            <div class="producto">
                <div class="imagen"></div>
                <h3>Jean clásico</h3>
                <p>Jean cómodo para cualquier ocasión.</p>
                <strong>$90.000</strong>
                <button onclick="window.location.href='reser
                    Reservar
                </button>
            </div>


            <div class="producto">
                <div class="imagen"></div>
                <h3>Gorra</h3>
                <p>Accesorio ideal para complementar tu esti
                <strong>$30.000</strong>
                <button onclick="window.location.href='reser
                    Reservar
                </button>
            </div>


            <div class="producto">
                <div class="imagen"></div>
                <h3>Bolso</h3>
                <p>Bolso moderno y práctico.</p>
                <strong>$70.000</strong>
                <button onclick="window.location.href='reser
                    Reservar
                </button>
            </div>


        </div>
    </section>


 
    <section id="reservas" class="seccion">
        <h2>Reserva tu pedido</h2>
        <p>Elige tu producto y completa tus datos para reali
        <a href="reserva.html" class="boton">Reservar produc
    </section>


    <section id="reseñas">
        <h2>Reseñas de nuestros clientes</h2>


        <div class="reseñas">


            <div class="reseña">
                <h3></h3>
                <p>"La ropa llegó rápido y en muy buen estad
                <strong>— María</strong>
            </div>


            <div class="reseña">
                <h3></h3>
                <p>"Muy buenos precios y excelente atención.
                <strong>— Carlos</strong>
            </div>


            <div class="reseña">
                <h3></h3>
                <p>"Me gustaron mucho los accesorios."</p>
                <strong>— Laura</strong>
            </div>


        </div>


        <h3 class="titulo-formulario">Déjanos tu reseña</h3>


        <form id="formResena">


            <input type="text" id="nombreResena"
                   placeholder="Tu nombre" required>




    
    




    
    


            <textarea id="comentario"
                      placeholder="Escribe tu opinión..."
                      required></textarea>


            <button type="submit" class="boton">
                Publicar reseña
            </button>


        </form>


        <div id="nuevasResenas"></div>


    </section>




    <section id="contacto" class="contacto">


        <h2>Contáctanos</h2>


        <p>📞 Teléfono: 300 123 4567</p>
        <p>📧 Correo: contacto@efashion.com</p>
        <p>📍 Servicio a domicilio</p>
        <p>📱 Instagram: @efashion</p>


        <h3>Horario de atención</h3>
        <p>Lunes - Sábado: 8:00 AM - 7:00 PM</p>


    </section>


  
    <footer>
        <p>© 2026 eFashion - Ropa y Accesorios</p>
        <p>Todos los derechos reservados.</p>
    </footer>


    <script src="script.js"></script>


</body>
</html>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initia


    <title>eFashion - Galería</title>


    <link rel="stylesheet" href="estilos.css">
    <style>
        .galeria .foto img {
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
    </style>
</head>


<body>


   
    <header>


        <div class="logo">
            eFashion
        </div>


        <nav>
            <a href="index.html">Inicio</a>
            <a href="galeria.html">Galería</a>
            <a href="index.html#productos">Productos</a>
            <a href="index.html#reservas">Reservas</a>
            <a href="index.html#reseñas">Reseñas</a>
            <a href="index.html#contacto">Contacto</a>
        </nav>


    </header>




    
    <section class="titulo-galeria">


        <h1>Galería eFashion</h1>


        <p>
            Conoce algunos de nuestros productos y encuentra
            el estilo que más te guste.
        </p>


    </section>




    
    <section class="galeria">


        <div class="foto">


            <img src="https://images.unsplash.com/photo-15215
                 alt="Camiseta">


            <h3>Camisetas</h3>


            <p>Diseños modernos y cómodos.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15422
                 alt="Jeans">


            <h3>Jeans</h3>


            <p>Estilo para cualquier ocasión.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15233
                 alt="Ropa">


            <h3>Moda</h3>


            <p>Las últimas tendencias.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15530
                 alt="Bolso">


            <h3>Bolsos</h3>


            <p>Accesorios para complementar tu look.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15213
                 alt="Gorra">


            <h3>Gorras</h3>


            <p>Accesorios modernos y casuales.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15480
                 alt="Accesorios">


            <h3>Accesorios</h3>


            <p>Detalles que completan tu estilo.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-14904
                 alt="Moda femenina">


            <h3>Moda femenina</h3>


            <p>Prendas para diferentes estilos.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15158
                 alt="Outfit">


            <h3>Outfits</h3>


            <p>Combina nuestras prendas y crea tu estilo.</p>


        </div>


    </section>




    <!-- LLAMADO A LA ACCIÓN -->
    <section class="galeria-final">


        <h2>¿Te gustó algún producto?</h2>


        <p>
            Reserva tu pedido y recibe tus productos
            directamente en tu domicilio.
        </p>


        <a href="reserva.html" class="boton">
            Hacer una reserva
        </a>


    </section>




    <!-- PIE DE PÁGINA -->
    <footer>


        <p>
            © 2026 eFashion - Ropa y Accesorios
        </p>


        <p>
            Todos los derechos reservados.
        </p>


    </footer>


</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initia


    <title>eFashion - Galería</title>


    <link rel="stylesheet" href="estilos.css">
    <style>
        .galeria .foto img {
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
    </style>
</head>


<body>


   
    <header>


        <div class="logo">
            eFashion
        </div>


        <nav>
            <a href="index.html">Inicio</a>
            <a href="galeria.html">Galería</a>
            <a href="index.html#productos">Productos</a>
            <a href="index.html#reservas">Reservas</a>
            <a href="index.html#reseñas">Reseñas</a>
            <a href="index.html#contacto">Contacto</a>
        </nav>


    </header>




    
    <section class="titulo-galeria">


        <h1>Galería eFashion</h1>


        <p>
            Conoce algunos de nuestros productos y encuentra
            el estilo que más te guste.
        </p>


    </section>




    
    <section class="galeria">


        <div class="foto">


            <img src="https://images.unsplash.com/photo-15215
                 alt="Camiseta">


            <h3>Camisetas</h3>


            <p>Diseños modernos y cómodos.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15422
                 alt="Jeans">


            <h3>Jeans</h3>


            <p>Estilo para cualquier ocasión.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15233
                 alt="Ropa">


            <h3>Moda</h3>


            <p>Las últimas tendencias.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15530
                 alt="Bolso">


            <h3>Bolsos</h3>


            <p>Accesorios para complementar tu look.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15213
                 alt="Gorra">


            <h3>Gorras</h3>


            <p>Accesorios modernos y casuales.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15480
                 alt="Accesorios">


            <h3>Accesorios</h3>


            <p>Detalles que completan tu estilo.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-14904
                 alt="Moda femenina">


            <h3>Moda femenina</h3>


            <p>Prendas para diferentes estilos.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15158
                 alt="Outfit">


            <h3>Outfits</h3>


            <p>Combina nuestras prendas y crea tu estilo.</p>


        </div>


    </section>




    <!-- LLAMADO A LA ACCIÓN -->
    <section class="galeria-final">


        <h2>¿Te gustó algún producto?</h2>


        <p>
            Reserva tu pedido y recibe tus productos
            directamente en tu domicilio.
        </p>


        <a href="reserva.html" class="boton">
            Hacer una reserva
        </a>


    </section>




    <!-- PIE DE PÁGINA -->
    <footer>


        <p>
            © 2026 eFashion - Ropa y Accesorios
        </p>


        <p>
            Todos los derechos reservados.
        </p>


    </footer>


</body>
</html>


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initia


    <title>eFashion - Galería</title>


    <link rel="stylesheet" href="estilos.css">
    <style>
        .galeria .foto img {
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
    </style>
</head>


<body>


   
    <header>


        <div class="logo">
            eFashion
        </div>


        <nav>
            <a href="index.html">Inicio</a>
            <a href="galeria.html">Galería</a>
            <a href="index.html#productos">Productos</a>
            <a href="index.html#reservas">Reservas</a>
            <a href="index.html#reseñas">Reseñas</a>
            <a href="index.html#contacto">Contacto</a>
        </nav>


    </header>




    
    <section class="titulo-galeria">


        <h1>Galería eFashion</h1>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initia


    <title>eFashion - Galería</title>


    <link rel="stylesheet" href="estilos.css">
    <style>
        .galeria .foto img {
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
    </style>
</head>


<body>


   
    <header>


        <div class="logo">
            eFashion
        </div>


        <nav>
            <a href="index.html">Inicio</a>
            <a href="galeria.html">Galería</a>
            <a href="index.html#productos">Productos</a>
            <a href="index.html#reservas">Reservas</a>
            <a href="index.html#reseñas">Reseñas</a>
            <a href="index.html#contacto">Contacto</a>
        </nav>


    </header>




    
    <section class="titulo-galeria">


        <h1>Galería eFashion</h1>


        <p>
            Conoce algunos de nuestros productos y encuentra
            el estilo que más te guste.
        </p>


    </section>




    
    <section class="galeria">


        <div class="foto">


            <img src="https://images.unsplash.com/photo-15215
                 alt="Camiseta">


            <h3>Camisetas</h3>


            <p>Diseños modernos y cómodos.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15422
                 alt="Jeans">


            <h3>Jeans</h3>


            <p>Estilo para cualquier ocasión.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15233
                 alt="Ropa">


            <h3>Moda</h3>


            <p>Las últimas tendencias.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15530
                 alt="Bolso">


            <h3>Bolsos</h3>


            <p>Accesorios para complementar tu look.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15213
                 alt="Gorra">


            <h3>Gorras</h3>


            <p>Accesorios modernos y casuales.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15480
                 alt="Accesorios">


            <h3>Accesorios</h3>


            <p>Detalles que completan tu estilo.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-14904
                 alt="Moda femenina">


            <h3>Moda femenina</h3>


            <p>Prendas para diferentes estilos.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15158
                 alt="Outfit">


            <h3>Outfits</h3>


            <p>Combina nuestras prendas y crea tu estilo.</p>


        </div>


    </section>




    <!-- LLAMADO A LA ACCIÓN -->
    <section class="galeria-final">


        <h2>¿Te gustó algún producto?</h2>


        <p>
            Reserva tu pedido y recibe tus productos
            directamente en tu domicilio.
        </p>


        <a href="reserva.html" class="boton">
            Hacer una reserva
        </a>


    </section>




    <!-- PIE DE PÁGINA -->
    <footer>


        <p>
            © 2026 eFashion - Ropa y Accesorios
        </p>


        <p>
            Todos los derechos reservados.
        </p>


    </footer>


</body>
</html>








        <p>
            Conoce algunos de nuestros productos y encuentra
            el estilo que más te guste.
        </p>


    </section>




    
    <section class="galeria">


        <div class="foto">


            <img src="https://images.unsplash.com/photo-15215
                 alt="Camiseta">


            <h3>Camisetas</h3>


            <p>Diseños modernos y cómodos.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15422
                 alt="Jeans">


            <h3>Jeans</h3>


            <p>Estilo para cualquier ocasión.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15233
                 alt="Ropa">


            <h3>Moda</h3>


            <p>Las últimas tendencias.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15530
                 alt="Bolso">


            <h3>Bolsos</h3>


            <p>Accesorios para complementar tu look.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15213
                 alt="Gorra">


            <h3>Gorras</h3>


            <p>Accesorios modernos y casuales.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15480
                 alt="Accesorios">


            <h3>Accesorios</h3>


            <p>Detalles que completan tu estilo.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-14904
                 alt="Moda femenina">


            <h3>Moda femenina</h3>


            <p>Prendas para diferentes estilos.</p>


        </div>




        <div class="foto">


            <img src="https://images.unsplash.com/photo-15158
                 alt="Outfit">


            <h3>Outfits</h3>


            <p>Combina nuestras prendas y crea tu estilo.</p>


        </div>


    </section>




    <!-- LLAMADO A LA ACCIÓN -->
    <section class="galeria-final">


        <h2>¿Te gustó algún producto?</h2>


        <p>
            Reserva tu pedido y recibe tus productos
            directamente en tu domicilio.
        </p>


        <a href="reserva.html" class="boton">
            Hacer una reserva
        </a>


    </section>




    <!-- PIE DE PÁGINA -->
    <footer>


        <p>
            © 2026 eFashion - Ropa y Accesorios
        </p>


        <p>
            Todos los derechos reservados.
        </p>


    </footer>


</body>
</html>












