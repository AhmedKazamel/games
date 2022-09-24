# games
Project of price for games
<!-- Contenedor -->
<head>
<style>
* {
	margin: 0;
	padding: 0;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}
body {
	background: #2e2a2a;
	color: #FFF;
	font-size: 62.5%;
	font-family: 'Roboto', Arial, Helvetica, Sans-serif, Verdana;
}

ul {
	list-style-type: none;
}

a {
	color: #e95846;
	text-decoration: none;
}

.pricing-table-title {
	text-transform: uppercase;
	font-weight: 700;
	font-size: 2.6em;
	color: #FFF;
	margin-top: 15px;
	text-align: left;
	margin-bottom: 25px;
	text-shadow: 0 1px 1px rgba(0,0,0,0.4);
}

.pricing-table-title a {
	font-size: 0.6em;
}

.clearfix:after {
	content: '';
	display: block;
	height: 0;
	width: 0;
	clear: both;
}
/** ========================
 * Contenedor
 ============================*/
.pricing-wrapper {
	width: 960px;
	margin: 40px auto 0;
}

.pricing-table {
	margin: 0 10px;
	text-align: center;
	width: 300px;
	float: left;
	-webkit-box-shadow: 0 0 15px rgba(0,0,0,0.4);
	box-shadow: 0 0 15px rgba(0,0,0,0.4);
	-webkit-transition: all 0.25s ease;
	-o-transition: all 0.25s ease;
	transition: all 0.25s ease;
}

.pricing-table:hover {
	-webkit-transform: scale(1.06);
	-ms-transform: scale(1.06);
	-o-transform: scale(1.06);
	transform: scale(1.06);
}

.pricing-title {
	color: #FFF;
	background: #e95846;
	padding: 20px 0;
	font-size: 2em;
	text-transform: uppercase;
	text-shadow: 0 1px 1px rgba(0,0,0,0.4);
}
.war{
	color: #FFF;
	background: #258139;
	padding: 20px 0;
	font-size: 2em;
	text-transform: uppercase;
	text-shadow: 0 1px 1px rgba(0,0,0,0.4);
}

.pricing-table.recommended .pricing-title {
	background: #2db3cb;
}

.pricing-table.recommended .pricing-action {
	background: #2db3cb;
}

.pricing-table .price {
	background: #403e3d;
	font-size: 3.4em;
	font-weight: 700;
	padding: 20px 0;
	text-shadow: 0 1px 1px rgba(0,0,0,0.4);
}

.pricing-table .price sup {
	font-size: 0.4em;
	position: relative;
	left: 5px;
}

.table-list {
	background: #FFF;
	color: #403d3a;
}

.table-list li {
	font-size: 1.4em;
	font-weight: 700;
	padding: 12px 8px;
}

.table-list li:before {
	content: "\2714 \FE0F";
	font-family: 'FontAwesome';
	color: #3fab91;
	display: inline-block;
	position: relative;
	right: 5px;
	font-size: 16px;
} 

.table-list li span {
	font-weight: 400;
}

.table-list li span.unlimited {
	color: #FFF;
	background: #e95846;
	font-size: 0.9em;
	padding: 5px 7px;
	display: inline-block;
	-webkit-border-radius: 38px;
	-moz-border-radius: 38px;
	border-radius: 38px;
	margin-left:5px;
}


.table-list li:nth-child(2n) {
	background: #F0F0F0;
}

.table-buy {
	background: #FFF;
	padding: 15px;
	text-align: left;
	overflow: hidden;
}

.table-buy p {
	float: left;
	color: #37353a;
	font-weight: 700;
	font-size: 2.4em;
}

.table-buy p sup {
	font-size: 0.5em;
	position: relative;
	left: 5px;
}

.table-buy .pricing-action {
	float: right;
	color: #FFF;
	padding: 10px 16px;
	-webkit-border-radius: 2px;
	-moz-border-radius: 2px;
	border-radius: 2px;
	font-weight: 700;
	font-size: 1.4em;
	text-shadow: 0 1px 1px rgba(0,0,0,0.4);
	-webkit-transition: all 0.25s ease;
	-o-transition: all 0.25s ease;
	transition: all 0.25s ease;
}
.volt{float: right;
	color: #FFF;
	background: #e95846;
	padding: 10px 16px;
	-webkit-border-radius: 2px;
	-moz-border-radius: 2px;
	border-radius: 2px;
	font-weight: 700;
	font-size: 1.4em;
	text-shadow: 0 1px 1px rgba(0,0,0,0.4);
	-webkit-transition: all 0.25s ease;
	-o-transition: all 0.25s ease;
	transition: all 0.25s ease;
}
.about{float: right;
	color: #FFF;
	background: #e95846;
	padding: 6px 16px;
	-webkit-border-radius: 2px;
	-moz-border-radius: 2px;
	border-radius: 2px;
	font-weight: 700;
	font-size: 1.4em;
	text-shadow: 0 1px 1px rgba(0,0,0,0.4);
	-webkit-transition: all 0.25s ease;
	-o-transition: all 0.25s ease;
	transition: all 0.25s ease;
	margin-right:82px;
	margin-top:20px;
}

.table-buy .pricing-action:hover {
	background: #cf4f3e;
}
.i{margin-left:20.5px;
background: #2db3cb;
}
.a{background:#258139;
margin-left:20.5px;
}
.s{background:#258139;}
.p{background:#e95846;
margin-left:20.5px;
}

.recommended .table-buy .pricing-action:hover {
	background: #228799;	
}

/** ================
 * Responsive
 ===================*/
 @media only screen and (min-width: 768px) and (max-width: 959px) {
 	.pricing-wrapper {
 		width: 768px;
 	}

 	.pricing-table {
 		width: 236px;
 	}
	
	.table-list li {
		font-size: 1.3em;
	}

 }

 @media only screen and (max-width: 767px) {
 	.pricing-wrapper {
 		width: 420px;
 	}

 	.pricing-table {
 		display: block;
 		float: none;
 		margin: 0 0 20px 0;
 		width: 100%;
 	}
 }

@media only screen and (max-width: 479px) {
	.pricing-wrapper {
		width: 300px;
	}
} 
</style>
</head>
	<div class="pricing-wrapper clearfix">
		<!-- Titulo -->
		<h1 class="pricing-table-title">Volt Store <a href="http://razergold.com">Best Price</a></h1>

		<div class="pricing-table">
			<h3 class="pricing-title">pubg</h3>
			<div class="price">$60<sup>/ month</sup></div>
			<!-- Lista de Caracteristicas / Propiedades -->
			<ul class="table-list">
				<li>1800 UC <span>From Coins</span></li>
				<li>2 Skins <span>From Bundle </span></li>
				<li>25 Epic Skins <span>From Free Arsenal </span></li>
				<li>Legendary Weapon<span class="unlimited">Limited !</span></li>
				<li>Legendary Character <span class="unlimited">limited !</span></li>
				<li>Royal Pass <span>included</span></li>
			</ul>
			<!-- Contratar / Comprar -->
			<div class="table-buy">
		<a class="pricing-action p" href="https://na.battlegrounds.pubg.com/#">Login</a>
				<a class="pricing-action p" href="https://www.midasbuy.com/midasbuy/eg/buy/pubgm">Charge Now</a>
				<a class="volt" href="https://www.pubgmobile.com/ar/home.shtml">Install</a>
				<a class="about" href="https://support.pubg.com/hc/ar/articles/115004198834-%D9%83%D9%8A%D9%81-%D8%AA%D9%84%D8%B9%D8%A8-PUBG-">How To Play</a>
			</div>
		</div>
		
		<div class="pricing-table recommended">
			<h3 class="pricing-title">Call Of Duty Mobile </h3>
			<div class="price">$80<sup>/ month</sup></div>
			<!-- Lista de Caracteristicas / Propiedades -->
			<ul class="table-list">
				<li>5000CP <span>From Coins</span></li>
				<li>5 Skins <span>From Bundle </span></li>
				<li>30 Epic Skins  <span>From Free Arsenal </span></li>
				<li>1 Mythic Weapon  <span class="unlimited"> Limited !</span></li>
				<li>1 Mythic Character<span class="unlimited"> Limited !</span></li>
				<li>Battle Pass <span>included</span></li>
			</ul>
			<!-- Contratar / Comprar -->
			<div class="table-buy">
				<a class="pricing-action i" href="https://s.activision.com/activision/login?redirectUrl=https%3A%2F%2Fwww.activision.com%2F">Login</a>
				<a class="pricing-action i" href="https://www.codashop.com/ar-eg/call-of-duty-mobile">Charge Now </a>
				<a class="pricing-action" href="https://www.callofduty.com/mobile">Install</a>
				<a class="about i" href="https://www.saudigamer.com/call-of-duty-mobile-14-tips-tricks-the-game-doesnt-tell-you/">How To Play</a>
			</div>
		</div>

		<div class="pricing-table">
			<h3 class="war">Apex Legends</h3>
			<div class="price">$75<sup>/ month</sup></div>
			<!-- Lista de Caracteristicas / Propiedades -->
			<ul class="table-list">
				<li>8100 C <span>From Coins</span></li>
				<li>8 Skins <span>From Bundle </span></li>
				<li>40 Epic Skins <span>From Arsenal </span></li>
				<li>2 Mythic Weapons <span class="unlimited">Limited ! </span></li>
				<li>2 Legendary Character<span class="unlimited">Limited !</span></li>
				<li>Ground Force <span>included</span></li>
			</ul>
			<!-- Contratar / Comprar -->
			<div class="table-buy">
				<a class="pricing-action a" href="https://www.ea.com/games/apex-legends">Login</a>
				<a class="pricing-action a" href="https://www.seagm.com/apex-legends-coins?ps=Search-Results:Related-cards">Charge Now</a>
				<a class="volt s" href="https://apex-legends.ar.uptodown.com/android/download">Install</a>
				<a class="about a" href="https://www.ea.com/ar-sa/games/apex-legends/apex-legends-mobile/faq">How To Play</a>
			</div>
		</div>
	</div>
