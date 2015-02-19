#Changelog

Das Changelog zur Website der Pfadi Angenstein ([www.pfadiangenstein.ch][homepage]).

##### 2.5.2
- Headerfarbe auf `#FFEB3B`geändert (von `#FFFF00`)

##### 2.5.1
- Schriftfarbe von `#2A2A2A` auf `#333`geändert (ausser `h1`-`h6`)

##### Beta 2.6
- Unter [www.pfadiangenstein.ch/shop][shopurl] ist ein [Webshop][shop] am entstehen

##### 2.5
- Eigene 404-Seite erstellt: [www.pfadiangenstein.ch/404](http://pfadiangenstein.ch/404)

##### 2.4.6
- Chrome for Mobile: Farbe der Statusleiste angepasst - siehe [HTML5Rocks][html5rocks]
```html
<meta name="theme-color" content="#53A6DC">
```

##### 2.4.5
- Bugfixes für [2.4.4][13]

##### 2.4.4
- Design der eingerückten Navigation angepasst wenn diese angewählt ist.

##### 2.4.3
- `blockquotes` und `q` wie folgt angepasst: 
```css
blockquote, q {
	quotes: none;
	font-style: italic;
	border-left: 3px #2A2A2A solid;
	padding-left: 20px;
}
```

##### 2.4.2
- Schriftart von input-Felder usw. mittels ` input, textarea, select { font-family: inherit; }` angepasst.

##### 2.4.1:
- ~~Schriftart gewechselt: neu [Droid Sans][droidsans],  lokal eingebunden~~

##### 2.4:
- Die Website ist jetzt für mobile Endgeräte optimiert!
- Folgende Bugs sind bekannt und werden in den nächsten Tagen behoben:
  - [x] Das Menu sieht teilweise komisch aus
  - [x] Das Pfadi Angenstein-Logo ist im Firefox auf Mac nicht skaliert.

#####~~2.4 BETA~~
- ~~Mobile Internetseite: Momentan auf [www.pfadiangenstein.ch/mobile][mobil] erreichbar.~~

#####2.3.12
- Tabellendesign angepasst

#####2.3.11
- Die Schriftart [Gudea][gudea] ist nicht mehr via Google Web Fonts eingebunden, sondern liegt jetzt auf dem Server.

#####2.3.10
- Wenn ein Modul links oder rechts der Hauptteils angezeigt wurde, hat es die Schriftgrösse der Seite geändert. Problem behobe.

#####2.3.9
- Favicon updated
- Apple Touch Icon hinzugefügt
- MS Application Tile hinzugefügt

#####2.3.8
- Copyright Hinweis "&copy; 2014 Pfadi Angenstein" im Footer hinzugefügt

#####2.3.7
- DNS-Eintrag angepasst: Seite ohne das `www` erreichbar (sobald DNS-Server wieder upgedatet wird)

#####2.3.6
- Auf Version 3.3.3 geupdatet (von 3.2.5)
  - möglich wegen Serverumzug -> neue PHP-Version
- schnellere Ladezeiten

#####2.3.5
- Kleine Code-Anpassungen für Vorbereitung auf ein responsives Design
- Datenbankoptimierungen

#####2.3.4
- Kontaktbox im Footer entfernt
- Ersetzt durch Newsanzeige (jeweils der neuste Artikel wird angezeigt)
- [RSS][11] und [Atom][12]-Feed erstellt für die News

#####2.3.3
- `code { font-family: 'Source Code Pro', 'Conosolas', monospace; }` im CSS hinzugefügt

#####2.3.2
- Datenbankstruktur und damit einhergehende Joomla-Core angepasst für Abfragen durch die [Android-App][10].

#####2.3.1
- `ul, ol { list-style-position: inside; }` in `ul, ol { list-stlye-position: outside; margin-left: 20px }` geändert (behebt das Problem der Version [v2.2.1](#v221)

#####2.3
- Suchfeld im Footer eingefügt

#####2.2.1:
- `ul, ol { list-style-position: outside; }` in `ul, ol { list-style-position: inside; }` geändert (behebt Problem, dass Aufzählungszeichen nicht angzeigt werden)
  - dafür passt der hängende Einzug nicht mehr
 
#####2.2:
- Das Topmenu angepasst: `margin-left: 0;`

#####2.1.6:
- `Iframes` systemweit erlaubt

#####~~2.1.5 BETA:~~
- ~~RSS-Feed der News integriert (Datei nur verlinkt, geplant ist eine Integration im Footer)~~ 

#####2.1.4:
- kleine Änderungen an der Navigation
  - "herumhüpfen" der 2. Ebene unterbunden

#####2.1.3:
- Hover-Farbe ändern (dunkleres Orange, `#FFA400`)
- Kein Hovereffekt in der Navigation sowie bei Buttons
  - Hover-Effekt in der Navigation: Gepunktete Linie unterhalb des `:hover`-Elements (gleiche Hervorhebung wie der aktive Menüpunkt)

#####2.1.2:
- `margin-top` bei den Absätzen geändert (von 8px auf 15px)

#####2.1.1:
- Schriftgrösse geändert

#####2.1:
- Antretorte ([Google Maps Engine Lite][6]) in `iframe` eingebunden ([www.pfadiangenstein.ch/index.php/antretorte][7])
  - Adresse sowie Parkplatzsituation vermerkt

#####2.02
- Schriftart auf [Gudea][gudea] geändert

#####2.01:
- Schriftart auf [Roboto][roboto] geändert

#####2.0:
- Neues Design :sparkles: :tada: :tada: :confetti_ball:
  - Bilder der Startseite vergrössert (1000px x 450px)
  - Gelbes Banner auf Startseite vergrössert
  - Navigation nach oben verschoben
- Neue Schriftart: [Open Sans][3]
- Kontaktformular ([www.pfadiangenstein.ch/index.php/kontakt][4])


#####2.0 Beta ([new.pfadiangenstein.ch][2], nicht mehr aktiv):
- Neues Design

#####1.1:
- Deignanpassungen

#####1.0:
- erster Release (ca. März 2012)

##To Do
- [x] Website responsive machen
- [x] Alert-Messages stylen
- [x] Header bearbeiten
- [x] Website schneller machen
- [x] Datenbank für App anpassen
 
##Info
Die genaue Aufzeichnung des Changelogs begann erst mit dem als [v2.0][8] erfassten Release. Sorry!

##Kontakt
Bei Fragen: Kaa, [webmaster@pfadiangenstein.ch][1]

[homepage]: http://www.pfadiangenstein.ch "www.pfadiangenstein.ch"
[1]: mailto:webmaster@pfadiangenstein.ch "webmaster@pfadiangenstein.ch"
[2]: http://new.pfadiangenstein.ch "new.pfadiangenstein.ch"
[3]: http://www.google.com/fonts/specimen/Open+Sans "Open Sans"
[4]: http://www.pfadiangenstein.ch/index.php/kontakt "Kontaktformular"
[gudea]: http://www.google.com/fonts/specimen/Gudea "Gudea"
[roboto]: http://www.google.com/fonts/specimen/Roboto "Roboto"
[6]: https://mapsengine.google.com/map/ "Google Maps Engine Lite"
[7]: http://www.pfadiangenstein.ch/index.php/antretorte "Antretorte"
[8]: https://github.com/faitnoise/Website/blob/master/changelog.md#20 "Release 2.0"
[9]: https://github.com/faitnoise/Website/blob/master/changelog.md#221 "Release 2.2.1"
[10]: https://github.com/faitnoise/pfadiangenstein "Android App"
[11]: http://www.pfadiangenstein.ch/index.php/news?format=feed&type=rss "RSS Feed"
[12]: http://www.pfadiangenstein.ch/index.php/news?format=feed&type=atom "Atom-Feed"
[mobil]: http://www.pfadiangenstein.ch/mobile "Pfadi Angenstein Mobil"
[droidsans]: https://www.google.com/fonts/specimen/Droid+Sans "Droid Sans"
[13]: https://github.com/faitnoise/Website/blob/master/changelog.md#244 "Release 2.4.4"
[html5rocks]: http://updates.html5rocks.com/2014/11/Support-for-theme-color-in-Chrome-39-for-Android "HTML5Rocks"
[shop]: https://github.com/faitnoise/WebshopAngenstein "Webshop Repo"
[shopurl]: http://www.pfadiangenstein.ch/shop "Webshop"
