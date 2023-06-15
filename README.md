# Projeto-Web-Site-Pet










<!DOCTYPE html>

<html lang="pt-br">
<head>
	<meta charset="UTF-8"/>
	<title>PETSHOOP</title>
	<style>
  		@import url('https://fonts.googleapis.com/css2?family=Cherry+Bomb+One&family=Rubik+Puddles&family=Titillium+Web:wght@200&display=swap');
		h1 {
			font-family: Arial;
			font-size: 30pt;
			color: blue;
			text-shadow: 2px 2px 2px black;
		}
		h2 {
			font-family: Arial;
			font-size: 20pt;
			color: black;
			display: inline-block;
		}
		h3 {
			font-family: Arial;
			font-size: 13pt;
			color: rgba(0,0,0,.7);
		}
		h4 {
			font-family: Arial;
			font-size: 13pt;
			color: rgba(0,0,0,.7);
		}
		h5 {
			font-family: Arial;
			font-size: 10pt;
			color: rgba(0,0,0.1);
		}
		h6 {
			font-family: Arial;
			font-size: 11pt;
			color: rgba(0,0,0.7);
		}
		p {
			text-align: justify;
			text-indent: -50px;
		}
		body {
			background-color: seagreen;
			color: rgba(0, 0, 0, 1);
			padding: 150px;
			margin: 145px 130px;
			width: -50px;
		}
		div#interface {
			background-color: white;
			margin: -300px -210px -1468px -210px;
			padding: 10px 0px 1095px;
			box-shadow: 0px 0px 10px black;
			border-radius: 10px;
		}
		div#cabecalho2 {
			position: absolute;
			top: 1486px;
			left: 990px;
		}
		div#cabecalho2 h6 {
			position: relative;
			color: rgba(0, 0, 0, .8);
			margin-bottom: -96px;
			left: 20px;
			right: 100px;
			top: -90px;
		}
		div#cabecalho2 a {
			text-decoration: none;
			color: black;
		}
		div#cabecalho2 a:hover {
			text-decoration: underline;
		}
		header#cabecalho img#icone {
			display: inline-block;
			width: 90px;
			top: -52px;
			left: 1047px;
			border-radius: 10px;
			position: relative;
		}
		header#cabecalho img#icone2 {
			position: relative;
			border-bottom: 1px black solid;
			height: 100px;
			left: 273px;
			top: 30px;
			background: url("_imagens3/logo.JPG") no-repeat 240px -30px;
		}
		header#cabecalho {
			border-bottom: 1px black solid;
			height: 130px;
			margin: -20px auto 100px;			
		}
		header#cabecalho h1 {
			font-family: 'Cherry Bomb One', cursive;
			font-size: 50pt;
			color: lightgreen;
			text-shadow: 2px 2px 2px rgba(0,0,0,.6);
			padding: 0px;
			margin-top: -80px;
			margin-bottom: 50px;
		}
		header#cabecalho h2 {
			font-family: Arial, sans-serif;
			font-size: 20pt;
			color: gray;
			padding: 0px;
			margin-top: -10px;
			margin-bottom: 10px;
		}
		header#cabecalho h3 {
			font-family: Arial, sans-serif;
			font-size: 12pt;
			color: black;
			padding: 10px;
			position: absolute;
			top: 70px;
			left: 63px;
		}
		main h2 {
			position: relative;
			display: inline-block;
			font-family: Arial, sans-serif;
			font-size: 13pt;
			color: green;
			left: -30px;
			top: -80px;
		}
		main h3 {
			display: inline-block;
			position: relative;
			font-family: Arial, sans-serif;
			font-size: 10pt;
			color: rgba(0, 0, 0, .7);
			padding: 30px;
			left: -230px;
			top: -10px;
			margin-left: 50px;
			margin-right: -70px;
			margin-top: 10px;
			margin-bottom: 50px;
		}	
		main h4 {
			position: relative;
			display: inline-block;
			font-family: Arial, sans-serif;
			font-size: 10pt;
			background-color: green;
			color: white;
			padding: 4px;
			top: -35px;
			left: -150px;
			margin-right: -70px;
			border-radius: 10px;
		}
		main h5 {
			position: relative;
			display: inline-block;
			font-family: Arial, sans-serif;
			font-size: 10pt;
			color: black;
			padding: 4px;
			top: -35px;
			left: -87px;
			margin-right: -70px;
			border-radius: 10px;
		    text-decoration: line-through;
	    }	
		main img#icone {
			display: inline-block;
			width: 150px;
			top: 1px;
			left: -0.3px;
			border-left: 100px;
			border-radius: 10px;
			position: relative;
		}
		main img#icone3 {
			display: inline-block;
			width: 392px;
			height: 285px;
			top: 370px;
			left: 15px;
			border-radius: 10px;
			position: relative;
		}
		main#cabecalho {
			position: relative;
			background-color: lightgreen;
			text-align: justify;
			text-align: 50px;
			padding: 150px;
			height: 150px;
			padding-top: -100px;
			bottom: -450px;
			top: 780px;
			left: 60px;
			margin: -340px -150px -100px -270px;
			
		}
		main#cabecalho p {
			margin-bottom: 25px;
		}
		main#cabecalho2 {
			position: relative;
			padding: 100px;
			top: 100px;
		}
		p {
			position: relative;
			margin: 10px -140px;
			top: -150px;
			left: 70px;

		}
		figure.fonte {
			display: inline-block;
			position: relative;
			border: 4px solid white;
			box-shadow: 1px 1px 4px black;
			border-radius: 10px;
		}
		figure.fonte img {
			width: 100%;
			height: 100%;
		}
		figure.fonte figcaption {
			opacity: 0;
			position: absolute;
			top: 0;
			background-color: white;
			color: black;
			box-sizing: border-box;
			padding: 10px;
			width: 100%;
			height: 100%;
			transition: 1s;
		}
		figure.fonte figcaption:hover {
			opacity: 1;
		}
		nav#menu ol {
			list-style: none;
			text-transform: uppercase;
			position: absolute;
			margin: -2px;
			top: 2px;
			left: 745px;
		}
		nav#menu li {
			display: inline-block;
			background-color: gray;
			padding: 10px;
			margin: 2px;
			border-radius: 10px;
		}
		nav#menu li:hover {
			background-color: #606060;
		}
		nav#menu {
			display: block;
		}
		nav#menu h2 {
			display: none;
		}
		nav#menu a {
			color: black;
			text-decoration: none;
		}
		nav#menu a:hover {
			color: white;
		}
		nav#menu2 ol {
			list-style: none;	
			text-transform: uppercase;
			position: absolute;
			background-color: lightgreen;
			padding: 30px 263px 25px 418px;
			margin: -33px 30px;
			top: 150px;
			left: 40px;		
		}
		nav#menu2 li {
			position: relative;
			display: inline-block;
			background-color: lightgreen;
			padding: 10px;
			margin: 15px;
			top: -13px;
			left: -120px; 
			border-radius: 10px;
		}
		nav#menu2 li:hover {
			background-color: lightgreen;
		}
		nav#menu2 {
			display: block;
		}
		nav#menu2 b {
			color: black;
			text-decoration: none;
		}
		nav#menu2 b:hover {
			color: black;
			text-decoration: underline;
		}
		nav#menu2 b {
			color: black;
			text-decoration: none;
		}
		nav#menu2 b:hover {
			color: black;
		}
		input {
			position: absolute;
			background-color: lightgray;
			padding: 1px 50px;
			height: 25px;
			width: 200px 100px;
			margin: 100px 650px;
			top: 52px;
			border-radius: 20px;
	    }
		footer#rodape {
			position: absolute;
			bottom: -1205px;
			left: 965px;
			clear: both;
		}
		footer#rodape i {
			text-align: center;
		}
	</style>
</head>	
<body>
	<hgroup>
		<div id="interface">
			<header id="cabecalho">
				<header id="icone2">
					<img id="icone2" src="_imagens3/logo.JPG">
				</header>
				<h1>Petwheel</h1>

					<nav id="menu">
						<ol type="disc">
							<h2>Menu Principal:</h2>
								<li><a href="index.html">Informar CEP</a></li>
								<li><a href="specs.html">Meus pedidos</a></li>
								<li><a href="fotos.html">Login/Cadastrar</a></li>
						</ol>		
					</nav>	
					<h3>ofertas > descontos</h3>			
				</header>

				<nav id="menu2">

					<ol type="disc">
						<li><b href="a">Home</b></li>
						<li><b href="a">Sobre</b></li>
						<li><b href="a">Blog</b></li>
						<li><b href="a">FAQ</b></li>
						<li><b href="a">Contato</b></li>
					</ol>
				</nav>

				<h2>Confira as melhores cadeirinhas para o seu Pet🛒</h2>

				<main>
				<figure class="fonte">
				<img id="icone" src="_imagens3/cadeira5.PNG">
					<figcaption></figcaption>
				</figure>
				<h2><b href="a">&rarr; COMPRAR</b></h2>
				<h5>R$267,88</h5>
				<h4>R$208,23</h4>
				<h3>Cadeirinha Pet Dog Azul</h3>

				<figure class="fonte">
				<img id="icone" src="_imagens3/cadeira6.JPG">
					<figcaption></figcaption>
				</figure>
				<h2><b href="a">&rarr; COMPRAR</b></h2>
				<h5>R$255,67</h5>
				<h4>R$203,20</h4>
				<h3>Cadeirinha Pet Dog Roxa</h3>	

				<figure class="fonte">
				<img id="icone" src="_imagens3/cadeira3.JPG">
					<figcaption></figcaption>
				</figure>
				<h2><b href="a">&rarr; COMPRAR</b></h2>
				<h5>R$201,56</h5>
				<h4>R$152,10</h4>
				<h3>Cadeirinha Pet Dog Verde</h3>

				<figure class="fonte">
				<img id="icone" src="_imagens3/cadeira4.JPG">
					<figcaption></figcaption>
				</figure>
				<h2><b href="a">&rarr; COMPRAR</b></h2>
				<h5>R$245,89</h5>
				<h4>R$210,15</h4>
				<h3>Cadeirinha Pet Dog Preta</h3>						
				</div>
			</main>	

			<main>
			<img id="icone3" src="_imagens3/fundo1.JPG">
			<img id="icone3" src="_imagens3/fundo2.PNG">
			<img id="icone3" src="_imagens3/cadeira1.JPEG">
			<img id="icone3" src="_imagens3/fundo4.JPG">
		    </main>

		    <div class="busca borda-alpha">
              <form id="form-buscar" action="/buscar" method="get">
                <input id="auto-complete" type="text" name="q" placeholder="Busque cadeirinha pet" value="" autocomplete="off" maxlength="255" />
                <i class="fas fa-search"></i>  
              </form>
            </div>

		    <main id="cabecalho">
		    <p>Formas de Pagamento:💲</br>
			• Pix<br />
			• Cartão débito virtual caixa<br />
			• Crédito á vista sem juros <br />
			• Crédito parcelado com juros (Para menores juros feche seu pedido por WhtasApp:(11)**<br />
			• Pagamento na entrega (Feche seu pedido por WhatsApp:(11)**<br/>
			• Mercado Pago<br />
			• PayPal</p>

			<p>--- 🛒 -- COMPRE ONLINE -- 🛍️ ---<br />
			• WhatsApp: (11)**<br />
			• DM Instagram: @**</p>

			<p>----- 🇧🇷 FRETE GRATIS (BRASIL) 🇧🇷 -----<br />
			PARA PEDIDOS ACIMA DE 300 REAIS</p>

			<p>----- 🌇 SÃO PAULO/SP 🌇 -----<br />
			ENTREGAS FEITAS DENTRO DE 24HRS ✔️<br />
			• ACEITAMOS: Espécie, cartões, pix/transferência)</p>
			</main>

			<div id="cabecalho2">
			<main class="cabecalho2">
				<h6>Informações:</h6>
			<ul class="list-unstyled">
				<li><a href="a">Sobre nós</a></li></br>
				<li><a href="a">Como comprar</a></li></br>
				<li><a href="a">Política de privacidade</a></li></br>
				<li><a href="a">Políticas de entrega</a></li></br>
				<li><a href="a">Trocas e devoluções</a></li></br>
				<li><a href="a">Pagamentos e reembolso</a></li></br>
				<li><a href="a">Cookies</a></li></br>
				<li><a href="a">Frete Grátis</a></li></br>
				<li><a href="a">Termos e Condições de Uso</a></li></br>
				<li><a href="a">Campanha</a></li>
			</ul>
			</div>
			</main>

			<footer id="rodape">
				<i>&rarr;Copy&shy;right 2023 &copy; by Matheus Santos Peixoto</i>
			</footer>
</body>
</html>
