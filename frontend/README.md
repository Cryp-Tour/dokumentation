# Frontend
## Ordnerstruktur und Dateien
### .github/workflows
Enthält die Workflow-Dateien für die Ausführung der Github Actions.

---
### contracts
JSON-Dateien mit Rinkerby Contracts. Für den Kauf benötigt.

---
### fonts
Einige Schriftarten die für die Website verwändet werden.

---
### images/gpx-leaflet
Bilder die für die Darstellung gekaufter Routen in OSM benötigt werden.

### images/*
Sonstige Bilder die auf der Website verwendet werden bspw. Logos, Favicons...

---
### js/boughtTours.js
JS-Funktionen, um gekaufte Touren in der Kontoseite darzustellen und die Interaktion auf der konto.html-Subseite.

### js/config.js
In dieser Konfig-Datei kann zentral die BASE-URL des backends gesetzt werden.

### js/createdTours.js
JS-Funktionen, um alle erstellen Touren in der Kontoseite darzustellen und die Interaktion auf der konto.html-Subseite.

### js/crypto-lib.js
Verlinkung auf die Bibliothek von Benedict.

### js/gpx.js
Externe Library, um die Touren in OSM darzustellen. Es musste jedoch noch im XMLHTTPRequest hinzugefügt werden, dass externe Cookies verwendet werden dürfen. Sonst, alles wie original.

### js/konto.js
JS-Funktionen, um die Benutzerdaten zu aktuallisieren und um zu entscheiden, ob ein User angemeldet ist oder nicht. Dient der Darstellung der konto.html-Seite.

### js/kontotabs.js
JS-Funktionen für die Funktionen der Navigationsleiste auf der konto.html-Seite.

### js/login.js
JS-Funktionen für den Login eines Benutzers und die Interaktion auf der login.html-Seite.

### js/main.js
Allgemeine JS-Funktionen die für mehrere Seiten benutzt werden können.

### js/navbar.js
JS-Funktionen für die allgemeine Navigationsleiste auf allen Seiten.

### js/newTour.js
JS-Funktionen, um eine neue Tour zu erstellen und die Interaktion auf der createTour.html-Seite. (Tokens erstellen und Tour auf den Server hochladen)

### js/register.js
JS-Funktionen, um einen neuen User zu registrieren und die Interaktion auf der register.html-Seite.

### js/search.js
JS-Funktionen, um einzelne Touren zu suchen mit Filtern und die Interaktion auf der suche.html-Seite sicherzustellen.

### js/tour_details.js
JS-Funktionen, um Details zur Tour zu bekommen und die Tour zu kaufen. Falls die Tour gekauft wurde kann die GPX-Datei runtergeladen werden und in einer OSM-Map dargestellt werden. Diese Datei kümmert sich auch um die Interaktion mit der tour.html-Seite.

---
### css/*
CSS-Dateien für spezifische Seiten auf der Website, aber auch allgmeine die für alle Seiten der Website gelten. Name gibt Hinweis auf den Verwendungsort.

---
### Dockerfile
Enthält die Anweisungen, um das Docker-Image für dieses Repo zu erstellen.

---
### package-lock.json & package.json & server.js
Dateien, damit der Nodejs-Webserver läuft, um die Website bereitzustellen.

---
### *.html
Alle Seiten der Website. Name gibt Hinweis auf den Verwendungsort.
