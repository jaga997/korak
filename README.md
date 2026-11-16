# Korak · Tekaški načrti

Osebni tekaški trener v brskalniku – brez namestitve, brez strežnika. Izbereš razdaljo, svojo pripravljenost in datum tekme, Korak pa sestavi načrt treningov in ga sproti prilagaja.

## Funkcije

- **Načrti od 5 km do maratona** – 5, 10, 12, 15, 18, 21,1, 25, 30 in 42,2 km; 4 nivoji pripravljenosti; 3–5 treningov na teden; faze osnova → gradnja → vrhunec → zaključek → teden tekme.
- **Vodeni trening** – štoparica čez cel zaslon, piski, vibracija in glasovna navodila v slovenščini.
- **Dnevnik in prilagodljiv načrt** – vpis občutka, časa, razdalje in bolečin; načrt se samodejno olajša ali okrepi.
- **Statistika in značke** – koledar aktivnosti, grafi po tednih, osebni rekordi, niz zaporednih treningov, 18 značk.
- **Vodnik** – kalkulator tempa, prehrana in geli, svetovalec za oblačila, časovnica dneva tekme, vodeno ogrevanje, raztezanje in krog moči, knjižnica vaj, pomočnik pri bolečini, metronom za kadenco, slovar pojmov.
- **Koledar** – dodajanje v Google Koledar ter izvoz CSV in `.ics`.
- **Več uporabnikov** – ločeni profili z neobveznim PIN-om, izvoz in uvoz varnostne kopije.
- **Svetli in temni način** – samodejno po nastavitvi naprave.

## Uporaba

Odpri `index.html` v brskalniku ali obišči objavljeno stran na GitHub Pages. Na telefonu izberi **Dodaj na začetni zaslon**, da dobiš ikono kot pri aplikaciji.

## Podatki in zasebnost

Vsi podatki se shranjujejo **samo v brskalniku na tvoji napravi** (`localStorage`). Nič se ne pošilja na strežnik. Za prenos na drugo napravo uporabi **Profili → Izvozi / Uvozi**. Brisanje podatkov brskalnika izbriše tudi podatke aplikacije.

## Objava na GitHub Pages

1. V repozitoriju odpri **Settings → Pages**.
2. Pod **Build and deployment** izberi **Deploy from a branch**, vejo `main` in mapo `/ (root)`.
3. Shrani. Čez minuto ali dve bo aplikacija dostopna na `https://<uporabnik>.github.io/<repozitorij>/`.

## Tehnično

Ena sama datoteka `index.html` (HTML, CSS, JavaScript), brez knjižnic in brez gradnje. Pisave se naložijo z Google Fonts.

## Opozorilo

Načrti so splošni in ne nadomeščajo zdravniškega nasveta. Pomočnik pri bolečini ni diagnoza.
