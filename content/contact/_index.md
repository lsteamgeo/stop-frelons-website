---
title: "Contact"
date: 2019-02-18T19:36:10+01:00
draft: false
menu: mainb
weight : 10
---

<div class="contact_form_page">		
    <form name="contact" method="POST" data-netlify="true" data-netlify-recaptcha="true">
    	<p class="hidden">
   			<label>Contrôle anti-robot, ne pas compléter ce champs : <input name="bot-field" /></label>
  		</p>
	   	<input type="hidden" name="_method" value="POST">	        	
	   	<input type="text" name="name" id="c_name" placeholder="Nom" value="" class="col-xs-12 transition">
		<input type="text" name="email" id="c_email" placeholder="Email" value="" class="col-xs-12 transition">
		<input type="text" name="phone" id="c_phone" placeholder="Téléphone" value="" class="col-xs-12 transition">
		<textarea name="message" id="c_message" class="col-xs-12 transition" placeholder="Message"></textarea>
		<div data-netlify-recaptcha="true"></div>
		<button type="submit" id="c_send" class="btn btn-block btn-primary transition">Envoyer</button>
	</form>
</div>