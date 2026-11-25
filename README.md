# Wedstrijdanalyses ASC Nieuwland 3

Homepage met alle tegenstanders van ASC Nieuwland 3 (5e klasse 10). Elke tegenstander krijgt een eigen analysepagina.

## Mappen

```
index.html            ← homepage met de tegels
wasmeer/index.html    ← analyse Wasmeer 2
```

Alle logo's, foto's en de grafiekbibliotheek zitten ín de html-bestanden zelf.
Er zijn dus geen losse afbeeldingen nodig.

## Online zetten met GitHub Pages

1. Maak op github.com een nieuwe repository aan, bijvoorbeeld `nieuwland-analyses`.
2. Klik op **Add file → Upload files** en sleep de **inhoud** van deze map erin
   (`index.html`, `README.md` en de map `wasmeer`). Klik op **Commit changes**.
3. Ga naar **Settings → Pages**. Kies bij *Source* **Deploy from a branch**,
   branch **main** en map **/(root)**, en klik op **Save**.
4. Na een minuut staat de site op
   `https://<jouw-gebruikersnaam>.github.io/nieuwland-analyses/`.

Let op: een GitHub Pages-site is openbaar. Iedereen met de link kan hem bekijken.

## Een nieuwe analyse toevoegen

1. Zet de nieuwe analyse in een eigen map, bijvoorbeeld `huizen/index.html`.
2. Open `index.html` (de homepage) en zoek het blok **Pas hier de gegevens aan**.
3. Zet bij die tegenstander `status: 'klaar'` en `map: 'huizen/'`, en eventueel `info: 'Za 5 dec · thuis'`.
4. Pas ook `VOLGENDE` aan (team, logo, datum, plek, thuis/uit, verwachting en map),
   en werk `NIEUWLAND` (positie, punten, vorm) en de standen van de tegenstanders bij.
5. Upload de gewijzigde bestanden opnieuw naar GitHub.

Na een gespeelde wedstrijd zet je `status: 'gespeeld'` met `uitslag` (Nieuwland eerst) en `resultaat` (`'W'`, `'G'` of `'V'`).
