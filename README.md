# HYROX Doubles Weekschema — Roos & Fleur

Een op zichzelf staande web-app met het volledige 12-weken trainingsschema richting de HYROX Doubles op 29 november 2026 (+ HYROX Relay op 27 november). Werkt in elke browser, kan als app-icoon op je telefoon gezet worden, en heeft geen server nodig.

## Online zetten via GitHub Pages (gratis)

1. Maak een GitHub-account als je die nog niet hebt: https://github.com
2. Maak een nieuwe **repository**, bijvoorbeeld genaamd `hyrox-schema` (mag public of private zijn — voor GitHub Pages op een gratis account moet de repo **public** zijn).
3. Upload alle bestanden uit deze map naar die repository, met behoud van de mapstructuur:
   ```
   index.html
   manifest.json
   icons/
     icon-192.png
     icon-512.png
     icon-180-apple.png
     favicon-32.png
   README.md
   ```
   Dit kan via "Add file → Upload files" in de GitHub-webinterface (sleep de hele map erin, GitHub behoudt de submap `icons/` automatisch).
4. Ga naar **Settings → Pages** in de repository.
5. Bij **Source** kies je de branch `main` (of `master`) en map `/ (root)` → **Save**.
6. Na ongeveer 1 minuut staat de site live op:
   ```
   https://[jouw-gebruikersnaam].github.io/hyrox-schema/
   ```
7. Deel die link met Fleur — jullie kunnen 'm allebei openen, ook los van elkaar.

## Als app op je telefoon zetten

Zodra de site live staat, open je de link in Safari (iPhone) of Chrome (Android):
- **iPhone:** Deel-knop → "Zet op beginscherm"
- **Android:** Menu (⋮) → "App installeren" of "Toevoegen aan startscherm"

Dan krijg je een eigen app-icoon en opent hij zonder browserbalk, net als een echte app.

## Belangrijk: voortgang wordt per apparaat/browser opgeslagen

De afvink-vakjes (Roos/Fleur per training) worden lokaal in de browser bewaard (`localStorage`), niet in een gedeelde database. Dat betekent:
- Wat jij afvinkt op jouw telefoon, ziet Fleur niet automatisch op haar telefoon, en andersom.
- Beide kunnen wel gewoon de planning zelf zien — dat is voor iedereen die de link opent hetzelfde.
- Als je de voortgang wél wilt delen, is de simpelste route: samen op één toestel afvinken, of elkaar losstaand even appen wat je gedaan hebt.

## Updates doorvoeren

Zodra er wijzigingen zijn (bijvoorbeeld: de looptempo's na de tests in week 1-2, of aanpassingen in het schema), vervang je gewoon het bestand `index.html` in de repository door de nieuwe versie — de rest (manifest, iconen) hoeft niet opnieuw. GitHub Pages werkt de site automatisch bij, meestal binnen een minuut.
