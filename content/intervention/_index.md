---
title: "Intervention"
date: 2019-02-18T19:36:10+01:00
draft: false
---

<div class="contact_form_page">		
    <form name="intervention" method="POST" data-netlify="true" data-netlify-recaptcha="true" action="/intervention/success">
    	<p class="hidden">
   			<label>Contrôle anti-robot, ne pas compléter ce champs : <input name="bot-field" /></label>
  		</p>
	   	<p><input type="text" name="name" id="c_name" placeholder="Nom" value="" class="col-xs-12 transition" required></p>
	   	<p><input type="text" name="name" id="c_address" placeholder="Adresse de l'intervention" value="" class="col-xs-12 transition" required></p>
	   	<p><input type="text" name="name" id="c_phone" placeholder="Numéro de téléphone" value="" class="col-xs-12 transition" required></p>
	   	<p><input type="text" name="name" id="c_nest" placeholder="Position du nid (arbre, sous toiture, cheminée, ...)" value="" class="col-xs-12 transition"></p>
	   	<p><input type="text" name="name" id="c_height" placeholder="Hauteur approximative du nid (hauteur d'homme, 5m, 10m, 15m)" value="" class="col-xs-12 transition"></p>
		<p><textarea name="message" id="c_message" class="col-xs-12 transition" placeholder="Informations complémentaires (dénomination professionnelle, n° de forfait pour les administrations, ...)"></textarea></p>
		<div class="col-xs-12" style="padding-bottom:20px;">
			<div data-netlify-recaptcha="true" ></div>
		</div>
		<p><button type="submit" id="c_send" class="btn btn-block btn-primary">Envoyer</button></p>
	</form>
</div>
