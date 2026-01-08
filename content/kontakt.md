---
title: "Kontakt"
date: 2023-10-27T12:00:00+01:00
draft: false
featured_image: "/images/contact.jpg"
description: "Kontaktieren Sie den Förderverein der Nordschule Neureut e.V. - Adresse, Telefon, E-Mail und Kontaktformular."
---

<script type="text/javascript">
  function onSubmit(token) {
    const form = document.getElementById('contact-form');
    const formData = new FormData(form);
    
    fetch(form.action, {
      method: 'POST',
      body: formData
    }).then(response => {
      if (response.ok) {
        alert('Nachricht erfolgreich gesendet!');
        form.reset();
      } else {
        alert('Fehler beim Senden der Nachricht.');
      }
    }).catch(() => {
      alert('Fehler beim Senden der Nachricht.');
    });
  }

function validate(event) {
  event.preventDefault();
  hcaptcha.execute();
}

function onLoad() {
  var element = document.getElementById('submit-btn');
  element.onclick = validate;
}
</script>
<script src="https://js.hcaptcha.com/1/api.js?onload=onLoad" async defer></script>

## Adresse & Kontakt

**Förderverein der Nordschule Neureut e.V.**  
Friedhofstr. 1  
76149 Karlsruhe

**Telefon:** +49 721 709695  
**Fax:** +49 721 782584  
**E-Mail:** service@die-foerderer.net

### Bankverbindung

**Bank:** Volksbank Karlsruhe/Neureut  
**IBAN:** DE94 6619 0000 0000 9430 02  
**BIC:** GENODE61KA1

## Kontaktformular

Haben Sie Fragen? Schreiben Sie uns!

<form id="contact-form" method="post" action="https://form.jaehrig.de/foerderverein">
    <input type="email" name="from" placeholder="Sender's email address"/>
    <input type="text" name="firstName" placeholder="First name" />
    <input type="text" name="lastName" placeholder="Last name" />
    <input type="hidden" name="subjectPrefix" value="[App-Question] " />
    <input type="text" name="subject" placeholder="Subject" />
    <textarea name="body" placeholder="Your message"></textarea>
    <div
      id="hcaptcha"
      class="h-captcha"
      data-sitekey="fffc11b2-beac-4058-87b6-fca822ae4516"
      data-callback="onSubmit"
      data-size="invisible"
    ></div>    
    <button id="submit-btn">Abschicken</button>    
</form>

*Hinweis: Mit der Nutzung dieses Formulars erklären Sie sich mit der Speicherung und Verarbeitung Ihrer Daten zur Bearbeitung Ihrer Anfrage einverstanden. 

Das Formular nutzt hCaptcha und die hCaptcha
<a href="https://www.hcaptcha.com/privacy">Privacy Policy</a> und
<a href="https://www.hcaptcha.com/terms">Terms of Service</a>.

Weitere Informationen finden Sie in unserer Datenschutzerklärung.*
