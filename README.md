# Curso1-HTML-Alura-Oracle
CARPETAS Y CODIGO 

*CODIGO HTML*
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barberia Alura</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div>
        <header>
            <h1 class="titulo-principal">Barberia Alura</h1>
        </header>

    </div>
    
    <img id="banner" src="/img/banner.jpg" alt="">
    
    <div class="principal">
        <h2 class="titulo-centralizado">Sobre la Barbería Alura</h2>
        <p>Ubicada en el corazón de la ciudad, la <strong>Barbería Alura</strong> trae para el mercado lo que hay de mejor para su cabello y barba. Fundada en 2020, la Barbería Alura ya es destaque en la ciudad y conquista nuevos clientes diariamente.</p>
        <p id="mision"><em>Nuestra misión es: <strong>"Proporcionar autoestima y calidad de vida a nuestros clientes"</strong>.</em></p>
        <p>Ofrecemos profesionales experimentados que están constantemente observando los cambios y movimiento en el mundo de la moda, para así ofrecer a nuestros clientes las últimas tendencias. El atendimiento posee un padrón de excelencia y agilidad, garantizando calidad y satisfacción de nuestros clientes.</p> 
    </div>
    
    <div class="diferenciales">

        <h3 class="titulo-centralizado">Diferenciales</h3>

        <ul>
            <li class="items">Atencion personalizada a alos clientes</li>
            <li class="items">Espacio diferenciado</li>
            <li class="items">Localizacion</li>
            <li class="items">Profesionales calificados</li>
           
        </ul>
        <img src="/img/diferenciales.jpg" class="imagendiferenciales">
    </div>
    
    

</body>
</html>


*CODIGO CSS*
.titulo-principal{
    padding-left: 30px;
}


#banner{
    width: 100%;
}

.principal{
    background-color: #cccccc;
    padding: 20px;

}

p{
    text-align: center;

}

em strong{
    color: red;
}

#mision{
    font-size: 20px;
}

.diferenciales{
    background: #FFFFFF;
    padding: 30px;
}

.titulo-centralizado{
    text-align: center;
    
}

.items{
    font-style: italic;
}

ul{
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
}

.imagendiferenciales{
    width: 50%;
}
