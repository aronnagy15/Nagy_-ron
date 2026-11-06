# NB1 Watch

Weboldal készülése: Az MLSZ egy pályázatot hirdetett ki egy olyan weboldalra, ami a magyar első osztályt mutatja be, tartja számon az eredményeket, a tabellát és a csapatokat.

## Felépítése:
- Főoldal
    - Carousel néhány hírrel
    - Tabella
    - Naptár a következő forduló meccseivel
- Csapatok
    - Csapatok logója, teljes neve
    - Eredményeik
- Webshop
    - Az összes csapat webshopjára irányító card-ok

## Elkészülése:

### Főoldal

1. Egy navbar bekerült, ami mindhárom oldalon látható természetesen.
2. Mind a három oldal egy containerben van, emögött van egy háttérfotó.
3. Egy jó nagy carousel a lap első eleme, ez felhívja a figyelmét a személynek, aki megtekinti a weboldalt. A carouselen 4 kép van, ezekhez van egy rövid szöveg az adott képpel kapcsolatban.
4. Bekerült a tabella és a naptár, mindketto egy Bootstrap table. A két táblázat a Bootstrap Grid segítségével került egymás mellé. Mindkét táblázatban az összes csapat neve mellé bekerült az adott klub logója.
5. Végül a containeren kívülre került egy footer az összes szponzorral. Ez ugyanúgy látszik mindhárom oldalon, mint a navbar.

### Csapatok

Ezen az oldalon ugyanúgy containerbe került 12 Bootstrap card. A card-okban van egy kép az adott klub logojával, egy 5-ös címsor a klub teljes nevével és egy unordered list a csapatok eredményeivel.

### Webshop

Egy griddel el van választva 12db kártya. 4db nagyobb card van felül, a négy nagyobb csapattal. Ezek a kártyák, a képekkel együtt, magasabbak és szélesebbek, mint a másik 8. A maradék 8 card 3 sorban van elrendezve. Az első 2 sorban 3 kártya van, az utolsó sorban 2.
Mindegyik kártyán egy csapatkép van, a klub neve és egy button, ami az adott klub webshopjára irányít.

## Minta:
- https://adatbank.mlsz.hu/