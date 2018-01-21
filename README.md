# lliurex-www
Adaptació de la pàgina principal del servidor de Lliurex 16 a un centre

## Contingut

- Hi ha tres directoris: `error`, `share` i `srv`.
- Els directoris: `error` i `srv` han d'estar a `/usr/share/lliurex-www/`.
- El contingut del directori: `share`, és a dir, `pmb-doc` ha de romandre dins del directori `/net/server-sync/share/`.

```
.
├── error
│   ├── 404.html
│   ├── css
│   │   ├── base.css
│   │   └── jquery.parallax.css
│   ├── images
│   │   ├── 404.png
│   │   ├── corner_white_bl.png
│   │   ├── corner_white_br.png
│   │   ├── corner_white_tl.png
│   │   ├── corner_white_tr.png
│   │   ├── forbidden.png
│   │   ├── llx-pandora-desktop.png
│   │   ├── server.png
│   │   ├── valentinguard.png
│   │   └── valentin.png
│   ├── index.php
│   ├── js
│   │   ├── jquery.event.frame.js
│   │   ├── jquery.js
│   │   ├── jquery.parallax_1.0.js
│   │   ├── jquery.parallax.js
│   │   └── jquery.parallax.min.js
│   └── quietor.jpg
├── LICENSE
├── README.md
├── share
│   └── pmb-doc
│       ├── css
│       │   ├── bootstrap.css
│       │   ├── bootstrap.css.map
│       │   ├── bootstrap-grid.css
│       │   ├── bootstrap-grid.css.map
│       │   ├── bootstrap-grid.min.css
│       │   ├── bootstrap-grid.min.css.map
│       │   ├── bootstrap.min.css
│       │   ├── bootstrap.min.css.map
│       │   ├── bootstrap-reboot.css
│       │   ├── bootstrap-reboot.css.map
│       │   ├── bootstrap-reboot.min.css
│       │   └── bootstrap-reboot.min.css.map
│       ├── index.html
│       └── js
│           ├── bootstrap.bundle.js
│           ├── bootstrap.bundle.js.map
│           ├── bootstrap.bundle.min.js
│           ├── bootstrap.bundle.min.js.map
│           ├── bootstrap.js
│           ├── bootstrap.js.map
│           ├── bootstrap.min.js
│           └── bootstrap.min.js.map
└── srv
    ├── awesome-font
    │   ├── css
    │   │   └── font-awesome.css
    │   └── font
    │       ├── FontAwesome.otf
    │       ├── fontawesome-webfont.eot
    │       ├── fontawesome-webfont.svg
    │       ├── fontawesome-webfont.ttf
    │       └── fontawesome-webfont.woff
    ├── css
    │   ├── feedek.css
    │   ├── img
    │   │   └── rss.png
    │   └── index.css
    ├── fonts
    │   ├── glyphicons-halflings-regular.eot
    │   ├── glyphicons-halflings-regular.svg
    │   ├── glyphicons-halflings-regular.ttf
    │   ├── glyphicons-halflings-regular.woff
    │   └── glyphicons-halflings-regular.woff2
    ├── get_locale.php
    ├── getRemoteResources.php
    ├── getResources.php
    ├── icons
    │   ├── admincenter.png
    │   ├── admin.png
    │   ├── easysite.png
    │   ├── jclic.png
    │   ├── links.png
    │   ├── lliurexlab.png
    │   ├── lliurex_.png
    │   ├── mac_.png
    │   ├── pmb_doc.jpeg
    │   ├── pmb_doc.png
    │   ├── resources.png
    │   ├── sai_.png
    │   └── sharedFolders.png
    ├── imagen
    │   ├── background_blanco.jpg
    │   ├── background_blanco.png
    │   ├── background.png
    │   ├── bg_pagina_clara.png
    │   ├── google-bak.png
    │   ├── google.png
    │   ├── icon-block.png
    │   ├── lliurex-banner.png
    │   ├── lliurex.jpg
    │   ├── llx16
    │   │   ├── google.png
    │   │   └── logo.png
    │   ├── logo_lliurex_naranja.png
    │   ├── logo_.png
    │   ├── logo.png
    │   ├── mestreacasa.jpg
    │   ├── noimg.png
    │   ├── portal_projectes.gif
    │   ├── raton_lupa.png
    │   ├── sai.gif
    │   ├── search.png
    │   ├── sprite.png
    │   └── valentin.png
    ├── incluyesitios.php
    ├── index_antes_html5.php
    ├── index.old.php
    ├── index.php
    ├── js
    │   ├── index.js
    │   └── lliurex.js
    ├── lib
    │   ├── bootstrap
    │   │   ├── css
    │   │   │   ├── bootstrap.css
    │   │   │   ├── bootstrap.css.map
    │   │   │   ├── bootstrap.min.css
    │   │   │   ├── bootstrap.min.css.map
    │   │   │   ├── bootstrap-theme.css
    │   │   │   ├── bootstrap-theme.css.map
    │   │   │   ├── bootstrap-theme.min.css
    │   │   │   └── bootstrap-theme.min.css.map
    │   │   ├── fonts
    │   │   │   ├── glyphicons-halflings-regular.eot
    │   │   │   ├── glyphicons-halflings-regular.svg
    │   │   │   ├── glyphicons-halflings-regular.ttf
    │   │   │   ├── glyphicons-halflings-regular.woff
    │   │   │   └── glyphicons-halflings-regular.woff2
    │   │   └── js
    │   │       ├── bootstrap.js
    │   │       ├── bootstrap.min.js
    │   │       └── npm.js
    │   ├── feedek.js
    │   ├── isotope.pkgd.min.js
    │   ├── jquery-2.0.0.min.js
    │   ├── jquery-3.1.1.min.js
    │   └── moment-with-locales.min.js
    ├── links
    │   ├── admin-center.json
    │   ├── jclic-aula.json
    │   ├── json_notation_for_resources.txt
    │   ├── pmb_doc.json
    │   └── share.json
    ├── lliurex.css
    ├── loader.gif
    ├── plugins -> ../../../lib/firefox-addons/plugins
    ├── preg_find.php
    ├── srv.title
    └── srv.title.es
```
