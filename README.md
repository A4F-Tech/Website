# a4f-tech.de

Quellcode der Website unter [a4f-tech.de](https://a4f-tech.de).

Jekyll auf GitHub Pages, Theme `cayman` als `remote_theme`.

| Datei | Zweck |
| --- | --- |
| `index.md` | Startseite |
| `impressum.md` | Impressum, `/impressum/` |
| `datenschutz.md` | Datenschutzerklärung, `/datenschutz/` |
| `_layouts/default.html` | Überschreibt das Theme-Layout: keine Google Fonts, kein GitHub-Button |
| `_includes/head-custom.html` | Systemschriften statt externer Schriftarten |

Das Layout wird bewusst lokal überschrieben. Google Fonts darf nicht wieder eingebunden werden, da dabei die IP-Adresse der Besucher an Google übertragen wird.
