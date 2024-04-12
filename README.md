# Trabalhoandroid
Este repositório contém um site com a tematica da origem da historia do android. Foi desenvolvido como parte das atividades da disciplina desenvolvimento web 1 ministrada pelo Professor Márcio na Fatec Franca.

Codigo Fonte:

" <!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
 		<meta lang = "pt-br">
		 <meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Como surgiu o mascote do Android</title>
		<link href="style/style.css" rel="stylesheet">
		<link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon">
 	</head>
	<body>
		<header>	
		   <h1>CURIOSIDADES DE TECNOLOGIA</h1>
		   <p>Tudo aquilo que você sempre quis saber sobre o mundo Tech, em um único lugar</p>
		</header>

		<nav>
			<a href="#principal" target="_self">Home</a>
			<a href="#curiosidade" target="_self">Curiosidade</a>
			<a href="#faleconosco" target="_self">Contato</a>
		</nav>

		<main>
			<article id="noticia">
				<h1>História do Mascote do Android</h1>
				
				<p>Provavelmente você sabe que o sistema operacional <strong>Android</strong>, mantido pelo <strong>Google</strong> é um dos mais utilizados para dispositivos móveis em todo o mundo. Mas tavez você não saiba que o seu simpático mascote tem um nome e uma história muito curiosa? Pois acompanhe esse artigo para aprender muita coisa sobre esse robozinho.</p>

				<h2>A primeira versão</h2>
				
				<p>A primeira tentativa de criar um mascote surgiu em 2007 e veio de um desenvolvedor chamado <a href="https://danmorrill.org" target="_blank">Dan Morrill</a>. Ele conta que abriu o <a href="https://inkscape.org/pt-br/" target="_blank">Inkscape</a> (software livre para vetorização de imagens) e criou sua própria versão de robô. O objetivo era apenas personificar o sistema apenas para a a sua equipe, não existia nenhuma solicitação da empresa para a criação de um mascote.</p>
				
				<picture>
					<source media="(max-width: 670px)" srcset="imagens/dan-droids-pq.png" type="image/png">
					<img class="displayed" src="imagens/dan-droids-pq.png" alt="Primeira versão os Dandroids">
				</picture>
				
				<p>Essa primeira versão bizarra até foi batizada em homenagem ao seu criador: seriam os <strong>Dandroids</strong>.</p>

				<h2>Surge um novo mascote</h2>
				
				<p>A ideia de ter um mascote foi amadurecendo e a missão foi passada para uma profissional da área. A ilustradora Russa <a href="https://www.irinablok.com/" target="_blank">Irina Blok</a>, também funcionária do Google, ficou com a missão de representar o pequeno robô de uma maneira mais agradável.</p>
				
				<picture>
					<source media="(max-width: 670px)" srcset="imagens/irina-blok-pq.jpg" type="image/png">
					<img class="displayed" src="imagens/irina-blok.jpg" alt="Ciradora do novo mascote">
				</picture>
				
				<p>A ideia principal da Irina era representar tudo graficamente com poucos traços e de forma mais chapada. O desenho também deveria gerar identificação rápida com quem o olha. Surgiu então o <strong>Bugdroid</strong>, o novo mascote do Android.</p>
				
				<img class="pequena" src="imagens/bugdroid.png" alt="Ultima versão do mascote">
				
				<p>A principal inspiração para os traços do novo Bugdroid veio daqueles bonequinhos que ilustram portas de banheiro para indicar o gênero de cada porta. Conta a lenda que a artista estava criando em sua mesa no escritório do Google e olhou para o lado dos banheiros e a identificação foi imediata: simples, limpo, objetivo.</p>

				<section class="boxVideo">
					<iframe width="560" height="315" src="https://www.youtube.com/embed/l2UDgpLz20M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
				</section>

				<aside id="curiosidade">
					<h3>Quer aprender mais? </h3>
					<p>Outro assunto curioso em relação ao Android é que cada versão sempre foi nomeada em homenagem a um doce, em ordem alfabética a partir da versão 1.5 até a 9.0.
					</p>
					<ul>
						<li>1.5 - <abbr title="Bolo de Copo">Cupcake</abbr></li>
						<li>1.6 - <abbr title="Rosquinha">Donut</abbr></li>
						<li>3.0 - <abbr title="Bomba">Eclai</abbr>r</li>
						<li>2.2 - <abbr title="Iorgurte Congelado">Froyo</abbr></li>
						<li>2.3 - <abbr title="Biscoito de Gengibre">Gingerbread</abbr></li>
						<li>3.0 - <abbr title="Favo de Mel">Honeycomb</abbr></li>
						<li>4.0 - <abbr title="Sanduíche de Sorvete">Ice Cream Sandwich</abbr></li>
						<li>4.1 - <abbr title="Jujuba">Jelly Bean</abbr></li>
						<li>4.4 - <abbr title="KitKat Nestle">KitKat</abbr></li>
						<li>5.0 - <abbr title="Pirulito">Lolipop</abbr></li>
						<li>6.0 - <abbr title="Marchmallow">Marshmallow</abbr></li>
						<li>7.0 - <abbr title="Torrone">Nougat</abbr></li>
						<li>8.0 - <abbr title="Oreo">Oreo</abbr></li>
						<li>9.0 - <abbr title="Torta">Pie</abbr></li>
					</ul>		
					<p>
						Infelizmente, o Android Q não existiu, pois o Google resolveu pôr fim a essa divertida prática e começou a usar numerações, o que deu origem ao Android 10.
					</p>
					<p>
						Acesse aqui o site <a href="https://www.android.com/intl/en_uk/history/" target="_blank">Android History</a> para conhecer a sequência das versões "adocicadas" e o que cada uma trouxe para o sistema Android.
					</p>

				</aside>
				<p>Então é isso! Espero que você tenha gostado do nosso artigo com essa curiosidade sobre o sistema <strong>Android</strong> e seu simpático mascote.
				</p>
		</article>
		</main>
		
		<footer id="faleconosco">
			<p>Site criado por <a href="https://github.com/Viniciussinc" target="_blank">Viniciussinc</a> para o <a href="https://www.cursoemvideo.com/" target="_blank">Fatec franca</a>.</p>
		</footer>
		
	</body>
</html>"

Imagens utilizadas:

<img src="https://raw.githubusercontent.com/Viniciussinc/Trabalhoandroid/main/imagens/bugdroid.png">
<img src="https://raw.githubusercontent.com/Viniciussinc/Trabalhoandroid/main/imagens/dan-droids-pq.png">
<img src="https://raw.githubusercontent.com/Viniciussinc/Trabalhoandroid/main/imagens/irina-blok.jpg">

Prints do site:
<img src = "[Opera Snapshot_2024-04-12_120731_127.0.0.1.png](https://raw.githubusercontent.com/Viniciussinc/Trabalhoandroid/54489baa3f8be56425d36bcb98aec5e27425fd51/imagens/Opera%20Snapshot_2024-04-12_120731_127.0.0.1.png)">
<img src = "https://raw.githubusercontent.com/Viniciussinc/Trabalhoandroid/54489baa3f8be56425d36bcb98aec5e27425fd51/imagens/Opera%20Snapshot_2024-04-12_120846_127.0.0.1.png">
<img src = "https://raw.githubusercontent.com/Viniciussinc/Trabalhoandroid/54489baa3f8be56425d36bcb98aec5e27425fd51/imagens/Opera%20Snapshot_2024-04-12_120904_127.0.0.1.png">
