# Peloponéz 2026 – mapa plánu

Interaktívna mapa rodinnej dovolenky po Peloponéze (august 2026):
kempy, zastávky a trasy po dňoch. Statické HTML, Leaflet + OSM.

## Aktuálne (v7 · zvyšok cesty 21.–30. 8. 2026)

Dovolenka je rozbehnutá, plán sa 21. 8. prekopal podľa reálne dohodnutých kempov:
Meltemi (do 23. 8.) → Kalogria, Stoupa → Finikes, Finikounda → Erodios, Gialova →
Diana, Antická Olympia → Rolling Turtles camperstop pri letisku.

- **Mapa zvyšku cesty (predvolená stránka):** https://msatala.github.io/peloponez-mapa/
  (aj ako https://msatala.github.io/peloponez-mapa/v7.html)
- **Plán deň za dňom:** https://msatala.github.io/peloponez-mapa/plan.html
- **Sprievodca na čítanie nahlas:** https://msatala.github.io/peloponez-mapa/sprievodca.html

Všetky tri stránky sa navzájom prelinkujú, takže stačí poslať jeden odkaz.

### Staršie verzie

- Alternatívy – rozhodovací nástroj k tvaru trasy: https://msatala.github.io/peloponez-mapa/alternativy.html
- v5 – plán 16.–29. 8.: https://msatala.github.io/peloponez-mapa/v5.html
- v4 – 16.–30. 8., variant s Monemvasiou: https://msatala.github.io/peloponez-mapa/v4.html
- v3 – pôvodná verzia: https://msatala.github.io/peloponez-mapa/v3.html

## Alternatívy – ktorý tvar trasy

Rozhodovací nástroj, nie ďalšia mapa trasy. Porovnáva **14-nocový** okruh
(16. 8. – 30. 8.) v štyroch tvaroch a pri každom ukazuje, čo stojí: pás nocí
zafarbený podľa toho, ako sa dá kemp zabookovať, denný rozpis, počet dní bez
šoférovania, a na mape prečiarknuté zastávky, o ktoré v danom variante prídete.

Postavený je na dvoch zisteniach:

- **S obytným autom je výlet z kempu drahší než presun.** Zbalíte a postavíte sa
  rovnako, ale navyše prejdete tú istú cestu dvakrát. Preto tu nie sú základne
  s výletmi, ale okruh, kde je zážitok vždy po ceste.
- **Voľné státie prestalo byť zálohou.** Grécko v roku 2026 zakázalo voľné
  kempovanie s pokutami od 300 €. Zálohou je vždy iný kemp – preto stránka
  ukazuje, koľko kempov je v okolí každej nerezervovanej noci. Kritická je
  Stoupa: Camping Kalogria je jediný licencovaný kemp v celej západnej Mani
  a má na mape červený rám.

Sú v nej aj kempy **bez online rezervácie** (žlté = mail, oranžové = telefón)
s overenými kontaktmi, a posledná noc priamo v areáli požičovne Rolling Turtles,
ktorá je zároveň camperstop 7 km od letiska.

## Plán deň za dňom

Mobilná verzia plánu (`plan.html`) sa generuje z markdownu v privátnom repozitári
skriptom `build-plan-web.py` – **nikdy sa needituje ručne**. Má obsah, nastaviteľnú
veľkosť písma (pamätá si ju) a široké tabuľky sa posúvajú prstom.

Overené hodiny a ceny k 21. 8. 2026: jaskyne Diros 09:00–17:00 (kasa do 16:15),
hrad Methoni 08:30–19:00 a 5 €, Antická Olympia 08:00–20:00 s posledným vstupom
19:40, Archimedovo múzeum v Olympii 10:00–18:00 a vstup voľný, železničný park
v Kalamate nonstop a zdarma.

## Sprievodca na čítanie nahlas

Sprievodca v štýle Lonely Planet ku každej zastávke aj ku každému presunu —
44 kapitol, 5–12 minút čítania na kapitolu, na čítanie deťom v aute.

- **Sprievodca:** https://msatala.github.io/peloponez-mapa/sprievodca.html

Má vlastný zoznam kapitol (tlačidlo *Kapitoly*), nastaviteľnú veľkosť písma
a nočný režim; nastavenie si pamätá. Kapitoly sú viazané na miesta, nie na
dátumy – ak sa plán posunie, sprievodcovi to nevadí.

## Rozdiel medzi v4 a v5

Obe verzie majú kempy overené priamo v rezervačných systémoch kempov, ale
vychádzajú z iného itinerára:

- **v5** (14 dní, 16.–29. 8.) – Lefka Beach 16.–20. 8. (4 noci v Argolide,
  výlety na Epidaurus, Mykény a do jaskyne Franchthi), Meltemi 20.–22. 8.,
  Erodios v Gialove 22.–24. 8. Prvé štyri noci stoja na jednom mieste preto,
  že celý juh je 18.–19. 8. vypredaný. Noci od 24. 8. sú zatiaľ len návrh.
- **v4** (15 dní, 16.–30. 8.) – Lefka Beach 16.–20. 8., Meltemi 20.–24. 8.,
  celodenný výlet do Monemvasie, ďalej Stoupa, Gialova a Olympia.

Zdrojová verzia plánu je v privátnom repozitári; tento repo obsahuje len mapu,
aby sa dala otvoriť na telefóne bez GitHub účtu. Stránky sú `noindex`.
