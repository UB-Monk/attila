# Attila

A content focused responsive theme for [Ghost](https://github.com/tryghost/ghost/). See a demo at: [attila.peteramende.de](https://attila.peteramende.de/)

## ♥️ Support

You can [buy me a drink](https://paypal.me/zutrinken) if you enjoy using Attila. Cheers 🍻

## 📷 Screenshot

<img src="https://raw.githubusercontent.com/zutrinken/attila/master/src/screenshot.png" />

## ⭐️ Features

* Theme options
* Responsive layout
* Light and Dark Mode
* Search support
* Post reading progress
* Code highlight including line numbers
* Comments and Disqus (Theme option)
* Ghost accent color

## 🌍 Localization

🟩 Up to date  🟧 Missing strings

| Code | Flag | Language | Status | Translator |
| :--: | :--: | :------: | :----: | :--------: |
| `en` | 🇬🇧 | English | 🟩 | |
| `de` | 🇩🇪 | German | 🟩 | |
| `es` | 🇪🇸 | Spanish | 🟩 | [r1p](https://github.com/r1p) |
| `fr` | 🇫🇷 | French | 🟩 | [robink](https://github.com/robink), [alsyia](https://github.com/alsyia) |
| `it` | 🇮🇹 | Italian | 🟩 | [fmaida](https://github.com/fmaida), [undrivendev](https://github.com/undrivendev) |
| `no` | 🇳🇴 | Norwegian | 🟧 | [arthurnoerve](https://github.com/arthurnoerve), [oisann](https://github.com/oisann), [Givemeurcookies](https://github.com/givemeurcookies) |
| `zh` | 🇨🇳 | Chinese | 🟩 | [hao-lee](https://github.com/hao-lee), [izumiko](https://github.com/izumiko), [emperorjoker](https://github.com/emperorjoker) |
| `zh_tw` | 🇨🇳 | Chinese Traditional | 🟩 | [Petingo](https://github.com/Petingo)
| `id` | 🇮🇩 | Indonesian | 🟧 | [simplyeazy](https://github.com/simplyeazy) |
| `ro` | 🇷🇴 | Romanian | 🟧 | [cdorin93](https://github.com/cdorin93) |
| `ru` | 🇷🇺 | Russian | 🟩 | [schamberg97](https://github.com/schamberg97), [atjanov](https://github.com/atjanov), [exeteres](https://github.com/exeteres) |
| `tr` | 🇹🇷 | Turkish | 🟩 | [cgrgrbz](https://github.com/cgrgrbz), [electricalgorithm](https://github.com/electricalgorithm) |
| `sv` | 🇸🇪 | Swedish | 🟩 | [martenj77](https://github.com/martenj77), [LarssonOliver](https://github.com/LarssonOliver) |
| `cs` | 🇨🇿 | Czech | 🟩 | [lunakv](https://github.com/lunakv), [rdolezel](https://github.com/rdolezel) |
| `pt` | 🇵🇹 | Portuguese | 🟧 | [matheusvanzan](https://github.com/matheusvanzan) |
| `vi` | 🇻🇳 | Vietnamese | 🟩 | [JustHmmmm](https://github.com/justhmmmm), [mastoduy](https://github.com/mastoduy) |
| `el` | 🇬🇷 | Greek | 🟧 | [thiodordelis](https://github.com/thiodordelis) |
| `dk` | 🇩🇰 | Danish | 🟩 | [jmayntzhusen](https://github.com/jmayntzhusen), [tmlmt](https://github.com/tmlmt) |
| `ar` | | Arabic | 🟩 | [pop-eax](https://github.com/pop-eax), [tayeh](https://github.com/tayeh)|
| `ca` | | Catalan | 🟧 | [arthurnoerve](https://github.com/arthurnoerve) |
| `lt` | 🇱🇹 | Lithuanian | 🟧 | [arthurnoerve](https://github.com/arthurnoerve) |
| `nl` | 🇳🇱 | Dutch | 🟧 | [gkdp](https://github.com/gkdp) |
| `pl` | 🇵🇱 | Polish | 🟩 | [filipolszewski](https://github.com/filipolszewski), [MrBoombastic](https://github.com/mrboombastic) |
| `eo` | | Esperanto | 🟧 | [ebanDev](https://github.com/ebanDev) |
| `ga` | | Galego | 🟩 | [r1p](https://github.com/r1p) |
| `uk` | 🇺🇦 | Ukrainian | 🟩 | [Rakanskiy](https://github.com/rakanskiy), [krupenik](https://github.com/krupenik), [vadimkin](https://github.com/vadimkin) |
| `ja` | 🇯🇵 | Japanese | 🟩 | [emperorjoker](https://github.com/emperorjoker) |
| `fa` | | Farsi | 🟩 | [ItsAminZamani](https://github.com/ItsAminZamani) |
| `fi` | 🇫🇮 | Finnish | 🟩 | [murtoM](https://github.com/murtoM) |
| `th` | 🇹🇭 | Thai | 🟩 | [GmBeHappy](https://github.com/GmBeHappy) |
| `hu` | 🇭🇺 | Hungarian | 🟩 | [ferivoq](https://github.com/ferivoq) |
| `ge` | 🇬🇪 | Georgian | 🟩 | [kiknaio](https://github.com/kiknaio) |


## 🔠 Setup custom google fonts

1. Go to [fonts.google.com](https://fonts.google.com/) and choose a font.
2. Choose __Embed__ and copy the `<link>` code.
3. Go to __Code injection__.  
4. Add this to __Blog Header__:  
````html
<link href="https://fonts.googleapis.com/css2?family=Mukta&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Crimson+Text&display=swap" rel="stylesheet">
<style>
  :root {
    --font-primary: 'Mukta', sans-serif;
    --font-secondary: 'Crimson Text', serif;
  }
</style>
````

## ⚙️ Development

Install [Grunt](https://gruntjs.com/getting-started/):
````bash
npm install -g grunt-cli
````
Install Grunt dependencies:
````bash
npm install
````
Build Grunt project:
````bash
grunt build
````
The compress Grunt task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.
````bash
grunt compress
````
## ⚖️ Copyright & License

Copyright (C) 2015-2024 Peter Amende - Released under the [MIT License](https://github.com/zutrinken/attila/blob/master/LICENSE).

attila
├── author.hbs
├── default.hbs
├── Gruntfile.js
├── index.hbs
├── LICENSE
├── package-lock.json
├── package.json
├── page.hbs
├── post.hbs
├── README.md
├── tag.hbs
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── font/
│   │   ├── cardo-v9-latin-700.eot
│   │   ├── cardo-v9-latin-700.svg
│   │   ├── cardo-v9-latin-700.ttf
│   │   ├── cardo-v9-latin-700.woff
│   │   ├── cardo-v9-latin-700.woff2
│   │   ├── cardo-v9-latin-italic.eot
│   │   ├── cardo-v9-latin-italic.svg
│   │   ├── cardo-v9-latin-italic.ttf
│   │   ├── cardo-v9-latin-italic.woff
│   │   ├── cardo-v9-latin-italic.woff2
│   │   ├── cardo-v9-latin-regular.eot
│   │   ├── cardo-v9-latin-regular.svg
│   │   ├── cardo-v9-latin-regular.ttf
│   │   ├── cardo-v9-latin-regular.woff
│   │   ├── cardo-v9-latin-regular.woff2
│   │   ├── fira-sans-v8-latin-500.eot
│   │   ├── fira-sans-v8-latin-500.svg
│   │   ├── fira-sans-v8-latin-500.ttf
│   │   ├── fira-sans-v8-latin-500.woff
│   │   ├── fira-sans-v8-latin-500.woff2
│   │   ├── fira-sans-v8-latin-700.eot
│   │   ├── fira-sans-v8-latin-700.svg
│   │   ├── fira-sans-v8-latin-700.ttf
│   │   ├── fira-sans-v8-latin-700.woff
│   │   ├── fira-sans-v8-latin-700.woff2
│   │   ├── fira-sans-v8-latin-regular.eot
│   │   ├── fira-sans-v8-latin-regular.svg
│   │   ├── fira-sans-v8-latin-regular.ttf
│   │   ├── fira-sans-v8-latin-regular.woff
│   │   └── fira-sans-v8-latin-regular.woff2
│   ├── images/
│   │   └── background.png
│   └── js/
│       └── script.js
├── locales/
│   ├── ar.json
│   ├── ca.json
│   ├── cs.json
│   ├── de.json
│   ├── dk.json
│   ├── el.json
│   ├── en.json
│   ├── eo.json
│   ├── es.json
│   ├── fa.json
│   ├── fi.json
│   ├── fr.json
│   ├── ga.json
│   ├── ge.json
│   ├── hu.json
│   ├── id.json
│   ├── it.json
│   ├── ja.json
│   ├── lt.json
│   ├── nl.json
│   ├── no.json
│   ├── pl.json
│   ├── pt.json
│   ├── ro.json
│   ├── ru.json
│   ├── sv.json
│   ├── th.json
│   ├── tr.json
│   ├── uk.json
│   ├── vi.json
│   ├── zh.json
│   └── zh_tw.json
├── partials/
│   ├── loop.hbs
│   ├── navigation-meta.hbs
│   ├── navigation.hbs
│   ├── pagination.hbs
│   ├── subscribe_form.hbs
│   └── icons/
│       ├── icon-arrow-left.hbs
│       ├── icon-arrow-right.hbs
│       ├── icon-facebook.hbs
│       ├── icon-globe.hbs
│       ├── icon-linkedin.hbs
│       ├── icon-mail.hbs
│       ├── icon-menu.hbs
│       ├── icon-rss.hbs
│       ├── icon-search.hbs
│       ├── icon-share.hbs
│       ├── icon-star.hbs
│       └── icon-twitter.hbs
└── src/
    ├── screenshot-desktop.jpg
    ├── screenshot-mobile.jpg
    ├── screenshot.png
    ├── js/
    │   ├── script.js
    │   └── libs/
    │       ├── highlight.pack.js
    │       ├── jquery.fitvids.js
    │       └── jquery.min.js
    └── sass/
        ├── _colors.scss
        ├── _fonts.scss
        ├── _highlight.scss
        ├── _normalize.scss
        └── style.scss
