<!DOCTYPE html> 
<html lang="es"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>GRUPO KIWI - Tienda de Donas</title> 
    <style> 
        body { 
            font-family: sans-serif; 
            margin: 0; 
            padding: 0; 
            color: #333; 
            background-color: #f4f4f4; 
            line-height: 1.6; 
        } 
 
        header { 
            background-color: #eee; 
            padding: 20px; 
            display: flex; 
            justify-content: space-between; 
            align-items: center; 
        } 
 
        header div { /* Logo area */ 
            font-size: 1.5em; 
            font-weight: bold; 
        } 
 
        header nav ul { 
            list-style: none; 
            padding: 0; 
            margin: 0; 
            display: flex; 
        } 
 
        header nav ul li { 
            margin-left: 20px; 
        } 
 
        header nav ul li a { 
            text-decoration: none; 
            color: #555; 
        } 
 
        main > section { 
            padding: 20px; 
            background-color: #fff; 
            margin-bottom: 20px; 
            text-align: center; 
        } 
 
        main > section:last-child { 
            margin-bottom: 0; 
        } 
 
        main > section > div:first-child { /* Image container in the first section */ 
            background-color: #ddd; 
            width: 80%; 
            margin: 20px auto; 
            padding: 50px 0; 
            border-radius: 5px; 
        } 
 
        main > section h1 { 
            color: #000; 
            margin-bottom: 10px; 
        } 
 
        main > section a { /* Buttons */ 
            display: inline-block; 
            background-color: #ccc; 
            color: #fff; 
            padding: 10px 20px; 
            text-decoration: none; 
            border-radius: 5px; 
            margin-top: 15px; 
        } 
 
        main > section:nth-child(2) { /* Second section with two images and text */ 
            display: flex; 
            flex-direction: column; 
            align-items: center; 
        } 
 
        main > section:nth-child(2) > div { 
            width: 80%; 
            margin-bottom: 20px; 
        } 
 
        main > section:nth-child(2) > div:first-child, 
        main > section:nth-child(2) > div:nth-child(2) { /* Small image containers */ 
            background-color: #ddd; 
            padding: 30px; 
            border-radius: 5px; 
        } 
 
        main > section:nth-child(2) > div:last-child { /* Text and button area */ 
            text-align: center; 
        } 
 
        main > section:nth-child(3) { /* Section with three equal boxes from original HTML, adapted 
to current wireframe structure */ 
            display: flex; 
            flex-direction: column; 
        } 
 
        main > section:nth-child(3) > div { 
            padding: 20px; 
            text-align: center; 
            border-bottom: 1px solid #eee; 
        } 
 
        main > section:nth-child(3) > div:last-child { 
            border-bottom: none; 
        } 
 
        main > section:nth-child(4) { /* Contact section, assuming the two column layout of the last 
wireframe image applies here */ 
            display: flex; 
            flex-direction: column; 
            text-align: left; 
        } 
 
        main > section:nth-child(4) > div { 
            margin-bottom: 15px; 
            padding: 20px; 
            background-color: #fff; /* Ensure it matches section background */ 
            border-radius: 5px; 
        } 
 
        main > section:nth-child(4) h3 { 
            color: #555; 
            margin-bottom: 5px; 
        } 
         
        main > section:nth-child(4) > div:last-child { /* The right-side "image" placeholder in the 
wireframe */ 
            background-color: #ddd; 
            width: 80%; /* Adjusted for mobile view */ 
            margin: 20px auto; 
            padding: 50px 0; 
            border-radius: 5px; 
        } 
 
        footer { 
            background-color: #333; 
            color: #fff; 
            text-align: center; 
            padding: 15px; 
            font-size: 0.9em; 
        } 
 
        /* Responsive design adjustments */ 
        @media (min-width: 768px) { 
            header nav ul { 
                display: flex; 
            } 
            main > section:nth-child(2) { 
                flex-direction: row; 
                justify-content: space-around; 
                align-items: flex-start; 
            } 
            main > section:nth-child(2) > div { 
                width: 45%; 
                margin-bottom: 0; 
            } 
            main > section:nth-child(3) { /* Promotions, Sucursales, Eventos */ 
                flex-direction: row; 
            } 
            main > section:nth-child(3) > div { 
                width: 33.33%; 
                border-right: 1px solid #eee; 
                border-bottom: none; 
            } 
            main > section:nth-child(3) > div:last-child { 
                border-right: none; 
            } 
            main > section:nth-child(4) { /* Contact section */ 
                flex-direction: row; 
                justify-content: space-between; 
                align-items: flex-start; 
            } 
            main > section:nth-child(4) > div { 
                width: 48%; /* Adjust width for two columns */ 
                margin-bottom: 0; 
            } 
            main > section:nth-child(4) > div:last-child { 
                width: 48%; 
                margin: 0; 
            } 
        } 
    </style> 
</head> 
<body> 
    <header> 
        <div>LOGO</div> 
        <nav> 
            <ul> 
                <li><a href="503.html">inicio</a></li> 
                <li><a href="503.html">productos</a></li> 
                <li><a href="503.html">nosotros</a></li> 
                <li><a href="503.html">sucursales</a></li> 
            </ul> 
        </nav> 
    </header> 
    <main> 
        <section> 
            <div> 
                <img src="" alt="Imagen de fondo"> 
            </div> 
            <h1>NECESITAS UNA DONA!</h1> 
            <a href="503.html">BOTON</a> 
        </section> 
        <section> 
            <div> 
                <img src="" alt="Imagen grande"> 
            </div> 
            <div> 
                <h2>NUESTROS SABORES</h2> 
                <p>explosion de chocolate, fresa con crema, arequipe, bombon de nutella.</p> 
                <a href="503.html">BOTON</a> 
            </div> 
        </section> 
        <section> 
            <div> 
                <h3>PROMOCIONES</h3> 
                <p>lunes de 2x1, promo dia del padre, compra 5 y lleva 6.</p> 
                <a href="503.html">BOTON</a> 
            </div> 
            <div> 
                <h3>CONOCE NUESTRAS SURCUSALES</h3> 
                <p>LA VELA, PLAYA EL ANGEL, SAMBIEL MGTA, PARQUE COSTAZUL.</p> 
                <a href="503.html">BOTON</a> 
            </div> 
            <div> 
                <h3>EVENTOS PARA TI</h3> 
                <p>bodas, cumpleaños, ferias.</p> 
                <a href="503.html">BOTON</a> 
            </div> 
        </section> 
        <section> 
            <div> 
                <h3>Contacto</h3> 
                <p>Nos encantaria conocer tus sugerencias.</p> 
            </div> 
            <div> 
                <h3>CORREO ELECTRONICO</h3> 
                <p>Lorem ipsum dolor sit amet, consectetur adipisci elit, sed eiusmod tempor incidunt 
ut labore et dolore magna aliqua.</p> 
                <a href="503.html">Contactar</a> 
            </div> 
            <div> 
                <h3>NUMERO DE TELEFONO</h3> 
                <p>Lorem ipsum dolor sit amet, consectetur adipisci elit, sed eiusmod tempor incidunt 
ut labore et dolore magna aliqua.</p> 
                <a href="503.html">Llamar</a> 
            </div> 
        </section> 
    </main> 
    <footer> 
        <p>&copy; 2025 Mi Empresa. Todos los derechos reservados.</p> 
    </footer> 
</body> 
