# :world_map: Stadtteilrundgang Cottbus-Sandow
:white_check_mark: Karte georeferenzieren und als Web-Map publizieren mit Standortermittlung.

## :computer: Link [https://stadtentwicklung.github.io/map5/)

### :camera_flash: Screenshot:
![Screenshot der GitHub-Pages App](https://raw.githubusercontent.com/stadtentwicklung/map5/master/img/screenshot.PNG)

## :rocket: Kurzbeschreibung Workflow

Der Grundplan (© IÖR DD - siehe Legende/Kartenspiegel) in Illustrator mit Start- und Endpunkt, Route und Richtung sowie "Klebenotiz"-Legende illustriert (inkl. URL zu Github-Pages plus QR-Code-Bild). In QGIS georeferenziert.

![Plan aus Illustrator](https://raw.githubusercontent.com/stadtentwicklung/map4/master/img/plan.PNG)

Über die Funktion **gdal2tiles** eine Leaflet.js-Map-App ausgegeben. In QGIS einen temorären Liniengeometrie-Layer angelegt und die Strecke für den Stadtteilrundgang erstellt. Den Layer als GPX gespeichert. Im Code der Leaflet-App den Pfad zum GPX eingefügt plus Details für mehr "Usebility": Ladeanzeige, Standortermittlung, Start- und Endpunktmarker, Layerbezeichnung und Sichtbarkeit angepasst... Copyrights bereits im **gdal2tiles**-Menü eingefügt.   

### :coffee::coffee::coffee: by [Stefan](https://github.com/stefanstoehr)
