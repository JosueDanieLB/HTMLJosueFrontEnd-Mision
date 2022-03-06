<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Midgard Pastelerías</title>
    <style>

        *{
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
        }

        body{
            background-color: white;
            background-image: url(Imágenes/Fondo1.jpg);
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            background-attachment: fixed;

        }

        .fondoAzul{
            background-color: #1c323d;
        }

        input{
            font-weight: bold;
            font-size: large;
            line-height: 50px;
            width: 300px;
        }

        input.fondoAzul{
            color: white;
        }

        .fondoRosa{
            background-color: #ed2762;
        }

        input.fondoRosa{
            color: white;
        }

        .colorBlanco{
            color: white;
        }

        .fondoAmarillo{
            background-color: #edff9b;
        }

    </style>

    <!-- Encabezado de la pasteleria -->

    <div align="center"><img src="Imágenes/Logo1.png" alt="Midgard" width="500px"></div>
    <br><br>
</head>

<body>

    <!-- Menú de opciones principal para diferenciar al cliente de los pasteleros del negocio -->
    <section>
        <a href="./2-sesionClientePasteleria.html">
            <div align="center"><input type="button" value="Soy cliente" class="fondoRosa"></div>
        </a>
        
        <br><br>

        <a href="./10-sesionPasteleria.html">
            <div align="center"><input type="button" value="Soy pastelero" class="fondoAmarillo"></div>
        </a>
    </section>

    <br><br><br><br><br><br><br><br><br><br><br><br>

    <!-- Sección de información acerca del sitio web -->
    <section>
        <div align="center" class="colorBlanco"><h3>¿Necesitas más información?</h3></div>
        
        <br>

        <a href="./8-sucursalesPasteleria.html">
            <div align="center"><input type="button" value="Nuestras sucursales" class="fondoAzul"></div>
        </a>

        <br>

        <a href="./9-contactoPasteleria.html">
            <div align="center"><input type="button" value="Contáctanos" class="fondoAzul"></div>
        </a>
    </section>

</body>
</html>
