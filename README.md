# site-escola
index.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="cabecalho">
        <img class="cabecalho-imagem" src="alurastart logo.png" alt="logo da alura start">
        <ul class="cabecalho-lista">
            <li class="cabecalho-lista-item">Escola</li>
            <li class="cabecalho-lista-item">Estudante</li>
        </ul>
    </header>


    <section class="escola">
        <div class="escola-div-conteudo">
            <h2 class="escola-titulo">Sobre a Escola</h2>
            <p class="escola-texto-um">A Escola Alura foi fundada em 2010 e tem como objetivo ensinar Pensamento Computacional, através do ensino de  Programação.</p>
            <p class="escola-texto-dois">A turma mais estudiosa e famosa é a Segunda Série A. Nós somos super unidos e a turma favorita por todos os professores e professoras que nos ajudam!</p>
        </div>
        <img class="escola-imagem" src="Formula-bro.png" alt="Professora no quadro">
    </section>
</body>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap" rel="stylesheet">
</head>
   <selection>
    <section class="estudante"
     <h2 class=”estudante-titulo”>Quem são nossos estudantes?</h2>
      <img src=”./img/Marcelo 1.png” alt=”foto do estudante Marcelo”>
      <img class=”estudante-imagem “src=”./img/Marcelo
      1.png” alt=”foto do estudante Marcelo”>
      <h3>Marcelo</h3>
</selection>

</html>

style.css
* {
    margin: 0;
    padding: 0;
}

.cabecalho {
    background-color: #424E61;
    color: white;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 24px 0;
}

.cabecalho-imagem{
    width: 15%;
}

.cabecalho-lista-item{
    display: inline-block;
    margin: 0 16px;
    font-size: 20px;
}

.escola-imagem{
    width: 25%;
}

.escola{
    background-image: linear-gradient(#424E61,#16CFF8);
    color:white;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 24px 0;
}

.escola-div-conteudo{
    width: 35%;
}
.escola-titulo{
    padding: 24px 0;
}
body{
    font-family:’Poppins’,sans-serif;
}
.estudante-imagem{
    width: 120px;
    }
