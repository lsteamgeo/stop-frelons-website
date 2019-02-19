---
title: "Contact"
date: 2019-02-18T19:36:10+01:00
draft: false
menu: mainb
weight : 10
---

<div class="contact_form_page">		
    <form name="contact" method="POST" data-netlify="true" data-netlify-recaptcha="true" action="/contact/success">
    	<p class="hidden">
   			<label>Contrôle anti-robot, ne pas compléter ce champs : <input name="bot-field" /></label>
  		</p>
	   	<p><input type="text" name="name" id="c_name" placeholder="Nom" value="" class="col-xs-12 transition"></p>
		<p><input type="text" name="email" id="c_email" placeholder="Email" value="" class="col-xs-12 transition"></p>
		<p><input type="text" name="phone" id="c_phone" placeholder="Téléphone" value="" class="col-xs-12 transition"></p>
		<p><textarea name="message" id="c_message" class="col-xs-12 transition" placeholder="Message"></textarea></p>
		<div class="col-xs-12" style="padding-bottom:20px;">
			<div data-netlify-recaptcha="true" ></div>
		</div>
		<p><button type="submit" id="c_send" class="btn btn-block btn-primary">Envoyer</button></p>
	</form>
</div>