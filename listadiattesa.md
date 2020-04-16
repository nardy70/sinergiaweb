---
title: Lista di Attesa
layout: generico
tag:
image: /images/pic01.jpg
sitemap:
---

### Modulo di prenotazione

<hr>

<section class="wrapper" style="margin-top: -3em;">
	<div class="inner">
		<header>
			<p>Compila il modulo sottostante e inviaci le tue richieste.</p>
		</header>
    <hr>
		<form method="post" action="https://formspree.io/meqldyjv">
			<div class="row uniform 50%">
				<div class="6u 12u$(xsmall)"><input type="text" name="nome" id="nome" placeholder="Nome" required /></div>
				<div class="6u 12u$(xsmall)"><input type="text" name="cognome" id="cognome" placeholder="Cognome" required /></div>
        <div class="6u 12u$(xsmall)"><input type="email" name="_replyto" id="email" placeholder="Email" /></div>
        <div class="6u 12u$(xsmall)"><input type="text" name="tel" id="tel" placeholder="Telefono" required /></div>
        <div class="12u$"><h4>Servizi:</h4></div>
        <div class="6u 12u$(xsmall)"><input type="checkbox" name="colore" id="colore"/><label for="colore">Colore</label></div>
        <div class="6u 12u$(xsmall)"><input type="checkbox" name="taglio" id="taglio"/><label for="taglio">Taglio</label></div>
        <div class="6u 12u$(xsmall)"><input type="checkbox" name="piega" id="piega"/><label for="piega">Piega</label></div>
        <div class="6u 12u$(xsmall)"><input type="checkbox" name="schiariture" id="schiariture"/><label for="schiariture">Schiariture</label></div>
        <div class="6u 12u$(xsmall)"><input type="checkbox" name="trattcutecapelli" id="trattcutecapelli"/><label for="trattcutecapelli">Trattamento Cute/Capelli</label></div>
        <div class="6u 12u$(xsmall)"><input type="checkbox" name="refilunghie" id="refilunghie"/><label for="refilunghie">Refil Unghie</label></div>
				<div class="12u$" style="margin-top: 1em;"><textarea name="note" id="note" placeholder="Note eventuali" rows="3"></textarea></div>
				<input type="hidden" name="_subject" value="Lista di attesa" />
				<input type="hidden" name="_format" value="plain" />
				<input type="hidden" name="_language" value="it" />
			  <div class="12u$"><input type="submit" class="button" value="Invia" /></div>
			</div>
		</form>
	</div>
</section>