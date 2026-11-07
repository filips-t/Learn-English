# Snakk engelsk – app for hjemskjermen

## Legg ut på GitHub Pages
1. Opprett et nytt repository på github.com (f.eks. `snakk-engelsk`).
2. Last opp alle filene i denne mappen (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`) til roten av repoet.
3. Gå til **Settings → Pages**. Velg **Deploy from a branch**, branch `main`, mappe `/ (root)`, og trykk Save.
4. Etter et minutt er siden live på `https://BRUKERNAVN.github.io/snakk-engelsk/`.

## Legg på hjemskjermen
- **iPhone (Safari):** Del-knappen → **Legg til på Hjem-skjerm**.
- **Android (Chrome):** Meny (⋮) → **Installer app** / **Legg til på startskjermen**.

## AI-nøkkel (for samtale, tilbakemelding og nye ord)
Samtaledelen bruker Claude. Første gang du sender en melding, ber appen om en Anthropic API-nøkkel (lages på console.anthropic.com).
- Nøkkelen lagres bare i nettleseren på din enhet, ikke i GitHub-repoet.
- Du bruker din egen API-kreditt. Sett en månedlig utgiftsgrense i konsollen.
- Bytt eller slett nøkkelen med 🔑-knappen øverst.
- Øvelsene (uttale, ordforråd, diktat, repetisjon) fungerer uten nøkkel, bortsett fra «Nye ord med AI».

## Oppdatere appen
Last opp ny `index.html`. Endre `snakk-v1` i `sw.js` til `snakk-v2` hvis hjemskjerm-appen viser gammel versjon.

## Kjente begrensninger
- Talegjenkjenning (mikrofonen) fungerer best i Chrome på Android. På iPhone kan den mangle eller være ustabil når appen åpnes fra hjemskjermen. Skriving i tekstfeltet fungerer alltid.
- Fremgang lagres lokalt per enhet og nettleser.
