---
title: "Kontakt"
date: 2023-10-27T12:00:00+01:00
draft: false
featured_image: "/images/contact.jpg"
---

<style>
.frmtx {
  --font-size: 100%;
  --font-family: inherit;
  --font-color: inherit;
  --background-color: #FFF;
  --border-color: #AAA;
  --border-width: 1px;
  --border-radius: 5px;
  margin: 0; min-width: 240px;
}
.frmtx * {color: var(--font-color);font-family: var(--font-family);font-size: var(--font-size);margin: 0;padding: 0;appearance: auto;outline: none;box-sizing: border-box}
.frmtx label {padding: 0;margin: 1em 0 .3em;display: block;line-height: 1.3}
.frmtx label:first-child {margin-top: 0}
.frmtx input, .frmtx textarea, .frmtx button {border: var(--border-width) solid var(--border-color);border-radius: var(--border-radius);background-color: var(--background-color)}
.frmtx input, .frmtx textarea {width: 100%;resize: none;padding: .5em;line-height: 1.3}
.frmtx input[name="_gotcha"] {display:none}
.frmtx input[type="checkbox"] {display: inline;width: 1.1em;height: 1.1em;appearance: auto;margin-right: .2em}
.frmtx button {display: block;padding: .5em 1.5em;margin: 1.5em 0 0;line-height: 1.5;font-weight: bold;cursor: pointer; background-color: #00449E; color: white; border: none;}
.frmtx button:hover {background-color: #003377;}
</style>

## Wir freuen uns auf Ihre Nachricht!

Haben Sie Fragen zu unserer Arbeit oder Ideen für neue Projekte? Zögern Sie nicht, uns anzusprechen.

<div class="flex flex-column flex-row-l mt4">
<div class="w-100 w-50-l pr4-l">
<div class="bg-near-white pa4 br3 mb4 ba b--black-10">
<h3 class="mt0 mb3 dark-blue f4">Adresse & Kontakt</h3>
<p class="f5 lh-copy mt0 mb2"><strong>Förderverein der Nordschule Neureut e.V.</strong><br>Friedhofstr. 1<br>76149 Karlsruhe</p>
<p class="f5 lh-copy mt0 mb2"><strong>Telefon:</strong> +49 721 709695</p>
<p class="f5 lh-copy mt0 mb2"><strong>Fax:</strong> +49 721 782584</p>
<p class="f5 lh-copy mt0 mb0"><strong>E-Mail:</strong> <span id="mail"></span></p>
</div>
<div class="bg-near-white pa4 br3 mb4 ba b--black-10">
<h3 class="mt0 mb3 dark-blue f4">Bankverbindung</h3>
<p class="f5 lh-copy mt0 mb2"><strong>Bank:</strong> Volksbank Karlsruhe/Neureut</p>
<p class="f5 lh-copy mt0 mb2"><strong>IBAN:</strong> DE94 6619 0000 0000 9430 02</p>
<p class="f5 lh-copy mt0 mb0"><strong>BIC:</strong> GENODE61KA1</p>
</div>
</div>
<div class="w-100 w-50-l bg-near-white pa4 br3 ba b--black-10">
<h3 class="mt0 mb3 dark-blue f4">Kontaktformular</h3>
<form action="https://form.taxi/s/046cj7p1" class="frmtx" method="POST" accept-charset="utf-8">
<label for="name">Name</label>
<input type="text" name="Name" id="name" required>
<label for="mail_input">E-Mail-Adresse</label>
<input type="email" name="E-Mail" id="mail_input" required>
<label for="msg">Ihre Nachricht</label>
<textarea rows="5" name="Nachricht" id="msg" required></textarea>
<label class="f6 mt3"><input type="checkbox" name="Datenverarbeitung bestätigt" value="Ja" required> Ich bin mit der Verarbeitung meiner Eingaben zum Zwecke der Anfragebearbeitung einverstanden.</label>
<input type="text" name="_gotcha" value="">
<button type="submit" class="br3">Absenden</button>
</form>
</div>
</div>

<script>
const u = 'service', d = 'die-foerderer.net';
document.getElementById('mail').innerHTML = `<a href="mailto:${u}@${d}" class="link blue hover-dark-blue">${u}@${d}</a>`;
</script>
