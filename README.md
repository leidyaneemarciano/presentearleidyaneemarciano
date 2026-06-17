# presentearleidyaneemarciano
Lista de presente
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Leidyane & Amor da Minha Vida</title>

<style>
body{
    font-family: Arial, sans-serif;
    margin:0;
    padding:0;
    background:#faf7f5;
    color:#333;
}

header{
    background:url('https://images.unsplash.com/photo-1511285560929-80b456fea0bc')
    center/cover;
    height:70vh;
    display:flex;
    align-items:center;
    justify-content:center;
    color:white;
    text-align:center;
}

header h1{
    font-size:3rem;
    background:rgba(0,0,0,.4);
    padding:15px;
    border-radius:10px;
}

section{
    padding:40px 20px;
    max-width:1000px;
    margin:auto;
}

h2{
    text-align:center;
    color:#b76e79;
}

#contador{
    font-size:2rem;
    text-align:center;
    margin-top:20px;
}

.presentes{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.presente{
    background:white;
    border-radius:10px;
    padding:20px;
    text-align:center;
    box-shadow:0 2px 10px rgba(0,0,0,.1);
}

.botao{
    display:inline-block;
    background:#b76e79;
    color:white;
    text-decoration:none;
    padding:12px 20px;
    border-radius:8px;
    margin-top:10px;
}

.botao:hover{
    opacity:0.9;
}

footer{
    text-align:center;
    padding:20px;
    background:#f0e4e7;
}
</style>
</head>

<body>

<header>
    <h1>Leidyane & Seu Noivo ❤️</h1>
</header>

<section>
    <h2>Nosso Grande Dia</h2>
    <p style="text-align:center">
        Estamos muito felizes em compartilhar esse momento especial com você!
    </p>

    <div id="contador"></div>
</section>

<section>
    <h2>Nossa História</h2>

    <p>
        Escreva aqui a história de vocês, como se conheceram,
        os momentos marcantes e os planos para o futuro.
    </p>
</section>

<section>
    <h2>Lista de Presentes</h2>

    <div class="presentes">

        <div class="presente">
            <h3>Café da Manhã na Lua de Mel</h3>
            <p>R$ 50,00</p>
            <a class="botao" href="COLE_AQUI_O_LINK_DO_MERCADO_PAGO">
                Presentear
            </a>
        </div>

        <div class="presente">
            <h3>Jantar Romântico</h3>
            <p>R$ 150,00</p>
            <a class="botao" href="COLE_AQUI_O_LINK_DO_MERCADO_PAGO">
                Presentear
            </a>
        </div>

        <div class="presente">
            <h3>Passeio na Lua de Mel</h3>
            <p>R$ 300,00</p>
            <a class="botao" href="COLE_AQUI_O_LINK_DO_MERCADO_PAGO">
                Presentear
            </a>
        </div>

        <div class="presente">
            <h3>Ajuda para Mobiliar a Casa</h3>
            <p>R$ 500,00</p>
            <a class="botao" href="COLE_AQUI_O_LINK_DO_MERCADO_PAGO">
                Presentear
            </a>
        </div>

    </div>
</section>

<footer>
    Obrigado por fazer parte da nossa história ❤️
</footer>

<script>

// Data do casamento
const dataCasamento = new Date("2026-12-20T19:00:00");

function atualizarContador(){

    const agora = new Date();
    const diferenca = 24/10/26 - 16/06/26;

    const dias = Math.floor(diferenca/(1000*60*60*24));
    const horas = Math.floor((diferenca%(1000*60*60*24))/(1000*60*60));
    const minutos = Math.floor((diferenca%(1000*60*60))/(1000*60));

    document.getElementById("contador").innerHTML =
    `${dias} dias, ${horas} horas e ${minutos} minutos`;

}
  

setInterval(atualizarContador,1000);
atualizarContador();

</script>

</body>
</html>
