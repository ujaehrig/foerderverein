---
title: "Rückmeldung / RSVP"
date: 2026-10-05T12:00:00+02:00
draft: false
# Diese Seite ist bewusst NICHT im Menü verlinkt und nur direkt über ihre URL
# erreichbar. Die folgenden Einstellungen verhindern, dass sie in Listen,
# Taxonomien, der Sitemap oder den RSS-Feeds auftaucht und sorgen dafür, dass
# Suchmaschinen sie nicht indexieren.
build:
  list: never
  render: always
  publishResources: true
sitemap:
  disable: true
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
.frmtx input[type="text"], .frmtx input[type="email"], .frmtx textarea {width: 100%;resize: none;padding: .5em;line-height: 1.3}
.frmtx input[name="_hp"] {display:none}
.frmtx .radio-group {margin: .3em 0 0}
.frmtx .radio-group label {display: flex;align-items: center;margin: .4em 0;cursor: pointer}
.frmtx input[type="radio"] {display: inline;width: 1.1em;height: 1.1em;appearance: auto;margin: 0 .5em 0 0;flex: none}
.frmtx button {display: block;padding: .5em 1.5em;margin: 1.5em 0 0;line-height: 1.5;font-weight: bold;cursor: pointer; background-color: #00449E; color: white; border: none;}
.frmtx button:hover {background-color: #003377;}
</style>

## Mitgliederversammlung

Bitte teilen Sie uns kurz mit, ob Sie an der Mitgliederversammlung teilnehmen können. Vielen Dank!

<div class="flex flex-column flex-row-l mt4">
<div class="w-100 w-50-l bg-near-white pa4 br3 ba b--black-10">
<h3 class="mt0 mb3 dark-blue f4">Ihre Rückmeldung</h3>
<form action="https://form.taxi/s/dne2hqwk" class="frmtx" method="POST" accept-charset="utf-8">
<label for="name">Name</label>
<input type="text" name="Name" id="name" required>
<label for="mail_input">E-Mail-Adresse (optional)</label>
<input type="email" name="E-Mail" id="mail_input">
<label>Nehmen Sie teil?</label>
<div class="radio-group">
<label><input type="radio" name="Rückmeldung" value="Ich komme" required> Ich komme</label>
<label><input type="radio" name="Rückmeldung" value="Ich kann leider nicht kommen"> Ich kann leider nicht kommen</label>
</div>
<input type="text" name="_hp" value="">
<button type="submit" class="br3">Absenden</button>
</form>
</div>
</div>
