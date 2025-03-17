# Meu-primeiro-Projeto
Esté codigo e sobre a compra e aluguéis de casas

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale= 1.0">
    <title>Seja Bem vindo!</title>
    <link rel="stylesheet" href="./style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">

</head>
<body>
    <section class="inicio">

    <h1 class="m1">Seja bem vindo!</h1>
    <h2 class="m1">O Melhor Lugar para Encontrar Seu Novo Lar</h2>
    </section>

    <section class="info">
                <h1 class="img1"></h1>
                <img class="img1" src="Mouse.png" width="50" height="40">
                <h2 class="m6">AQUI SEU SONHO SE TORNA</h2>
                <h2 class="m6">REALIDADE!</h2>
                <p>Com +250 imóveis selecionados </p>
                <p>temos a opção perfeita para você</p>
                <button class="m2"><a href="#contact">VENDA</a></button>
                <h1 class="m8">OU</h1>
                <button class="m2"><a href="#contact">Alugue</a></button>
                <h2 class="m7">Agenda sua Visita.</h2>
                <h2 class="m7">(12) 3456-7890</h2>
            </div>
            <div>
                <img class="img2" src="casas.png", width="500", height="500" >
                
            </div>
        </div>
    </section>
    
     <section id="contact" class="py-5">
        <div class="container">
            <h2 class="m4">ENTRE EM CONTATO</h2>
            <form class="mt-4">
                <div class="mb-3">
                    <label for="name" class="m11">Seu Nome</label>
                    <input  class="m13" type="text" class="form-control" id="name" placeholder="Digite seu nome" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="m5">Seu E-mail</label>
                    <input class="m10" type="email" class="form-control" id="email" placeholder="Digite seu e-mail" required>
                </div>
                <div>
                    <label for="telefone" class="m12">Telefone</label>
                    <input class="m14" type="tel" id="telefone" class="input-padrao" required placeholder="(xx) xxxxx-xxxx">
                    <div>
                        <label for="telefone" class="m15">Endereço</label>
                        <input class="m16" type="tel" id="endereço" class="input-padrao" required placeholder="Digite seu endereço">
                </div>
                <button  class="m3" type="submit" class="btn btn-primary w-500" >Enviar</button>
                
            </form>
        </div>
    </section>

    
</body>

</html>


#CSS

body{
 background:url(Fundo2.png) no-repeat;
 background-size: cover;
 color: #463f3a;

}
 p{
    font-size: 14.5px;
    position: relative;
    bottom: 0px;
    position: relative;
    top: 80px;
    color: #127bcb;
 }

 p{
    font-size: 14px;
 }


 .img1{
    position: relative;
    top: 100px;
 }

.img2{
    position: relative;
    left: 700px;
    position: relative;
    bottom: 400px;
    position: relative;
    height: 1000px;
    position: relative;
    width: 900px;
}

.m1{
    text-align: center;
    font-size: 56px;
    
}

.m2{
    color: #fff;
    height: 30px;
    width: 100px;
    cursor: pointer;
    position: relative;
    bottom: 0px;
    position: relative;
    top: 150px;
}

.m2:hover{
 color: #fff;
 position: relative;
 left: 1150px;
 
}

.m2{
 font-size: 22px;
}

.m3{
    color: #fff;
    cursor: pointer;
    position: relative;
    bottom: 20px;
    position: relative;
    left: 1130px;
    height: 30px;
    width: 100px;
}

.m3:hover{
    color: #127bcb;
    position: relative;
    left: 0px;
 }

.m5{  
    position: relative;
    bottom: 120px;
    position: relative;
    left: 800px;
    width: 900px;
    height: 100px;
}

.m4{
    text-align: center;
    position: relative;
    bottom: 100px;
}

.m4{
    font-size: 40px;
}

.m6{
    position: relative;
    bottom: 0px;
    position: relative;
    top: 100px;
}

.m7{
    position: relative;
    bottom: 0px;
    position: relative;
    top: 200px;
}

.m8{
    position: relative;
    bottom: 0px;
    position: relative;
    top: 150px;
    
}

input{
    position: relative;
    bottom: 100px;
}

label{
    font-size: 35px;
    position: relative;
    left: 0px;
}
button{
    background-color: #463f3a;
    text-decoration: none;
    color: #fff;
}

 button a{
    text-decoration: none;
    color: #fff;
}

button :hover{
    text-decoration: none;
    color: #127bcb;
}

.m10{
    position: relative;
    bottom: 140px;
}

.m10{
    position: relative;
    height: 15px;
    width: 200px;
    position: relative;
    right: 200px;
    position: relative;
    left: 640px;
    position: relative;
    bottom: 90px;
}

.m11{
    position: relative;
    bottom: 2px;
    position: relative;
    left: 800px;
}



.m13{
    position: relative;
    bottom: 0px;
    position: relative;
    left:650px;
    position: relative;
    top: 24px;
}

.m13{
    height: 15px;
    width: 200px;
}

.m13{
    font-size: 12px;
}

.m14{
    position: relative;
    bottom: 130px;
    position: relative;
    left: 1180px;
}

.m14{
    height: 15px;
    width: 200px;
}

.m12{
    position: relative;
    bottom: 160px;
    position: relative;
    left: 1300px;
}

.m15{
    position: relative;
    left: 1300px;
    position: relative;
    bottom: 120px;
}

.m16{
    position: relative;
    left: 1170px;
    position: relative;
    bottom: 90px;
}


.m16{
    height: 15px;
    width: 200px;
}

.inicio{
    margin: 150px ;
}
