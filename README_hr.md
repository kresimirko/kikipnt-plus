<p align="right">
    <a href="./README.md">English</a> | hrvatski
</p>

<p align="center">
    <img src="./logo_std.svg" width=360>
    <br><br>
    <b>kikipnt+</b>
    <br>
    održavana verzija projekta <a href="https://github.com/kresimirko/kikipnt">kikipnt</a>
</p>

---

:link: **Pogledajte stranicu live:** [kikipnt+](https://kresimirko.github.io/kikipnt-plus/#/)

---

:pushpin: **kikipnt+** (eng. izgovor "kiki point plus") **je web aplikacija za traženje mjesta na svijetu**. Pokrenuta [OpenStreetMapom](https://www.openstreetmap.org/).

![kikipnt+ screenshot](./screenshots/latest.png)

Inspiriran [ovime](https://github.com/ful1e5/Bibata_Cursor#what-does-bibata-mean), odlučio sam uzeti "kiki" iz "kikiriki" i dodati "pnt", skraćenu verziju engleske riječi "point" (točka). Tako sam dobio ime **kikipnt**. Na kraju sam dodao i plus.

Same datoteke projekta su u [kikipnt](./kikipnt/) mapi.

**Note:** Za obojane komentare u izvornom kodu, preporučujem "[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)" Visual Studio Code proširenje.

## :keyboard: Buildanje i pokretanje

(Radna mapa treba biti [kikipnt](./kikipnt/).)

`npm install` - instalirajte sve potrebne packageve (pogledajte [dependency graph](https://github.com/kresimirko/kikipnt/network/dependencies) za listu)

`npm run dev` - buildaj i pokreni "development" verziju

`npm run prod` - buildaj i pokreni "production" verziju

### Ručno

#### "Development"

`npx parcel --no-hmr`

#### "Production"

`npx parcel build --no-source-maps --public-url ./`

## :page_with_curl: Resursi repozitorija

[:page_facing_up: Changelog](./CHANGELOG.md)

[:memo: Todo](./TODO.md)

[:framed_picture: Screenshotovi](./screenshots/)

## :hammer_and_wrench: Atribucije

### Dependencyjevi

Pogledajte [dependency graph](https://github.com/kresimirko/kikipnt/network/dependencies).

### Resursi aplikacije

[Ubuntu font](https://fonts.google.com/specimen/Ubuntu/)

[Gantari font](https://fonts.google.com/specimen/Gantari)

[Material Symbols](https://fonts.google.com/icons/)

[SVG spinners](https://github.com/n3r4zzurr0/svg-spinners/)

### Alati

[Visual Studio Code](https://code.visualstudio.com/)

[Inkscape](https://inkscape.org/)

[Adobe Illustrator](https://www.adobe.com/products/illustrator.html)

### Ostali resursi

Odgovori sa [Stack Overflowa](https://stackoverflow.com/) (potrebne atribucije su u izvornom kodu kao komentari)

[MDN Web Docs](https://developer.mozilla.org/en-US/)

## Licence

MIT i BSD 2-Clause

Pogledajte [LICENSE datoteku](./LICENSE.txt) za više detalja.

---

<p align="center">
    Napravio <a href="https://kresimirko.github.io">Luka Krešimir Mihovilović</a> sa &#128156;
</p>
