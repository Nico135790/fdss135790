(index.html)
html
<!DOCTYPE html>
<html>

    <head>
        <meta charset='UTF-8'>
        <meta name='viewport' content="width=device-width, initial-scale=1.0">
        <title>AluraBooks</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="styles.css">
    </head>

    <body>
        <header class="cabecalho"> 
            <div class="container">
            <span clas="cabecalho_menu-hamburguer container__imagem"></span>
            <img src="img/Logo.svg" alt="Logo da Alurabooks" class="container__imagem" >
            </div>
            <div class="container">
            <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos"></a>
            <a href="#"><img src="img/Compras.svg" alt="Carrinhos de compras"></a>
             <a href="#"><img src="img/Usuarios.svg" alt="Meu perfil"></a>
            </div>
        </header>
       
    </body>

</html>


(styles.css)
 @import url("styles/header.css");

 :root {
    --cor-de-fundo:#EBECEE;
    --branco: #FFFFFF;
}

body{
    background-color: var(--cor-de-fundo);
}

h1 {
    background-color: white;
}
 (header)
 .cabecalho__menu-hamburguer{
    width: 24px;
    height: 24px;
    background-image: url("../img/Menu.svg");
    display: inline-block;
}

.cabecalho {
background-color: var(--branco);
display: flex;
justify-content: space-between;
align-items: center;
}

.container { 
    display: flex;
    align-items: center;
}
