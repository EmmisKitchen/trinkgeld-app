TRINKGELDABRECHNUNG – PROTOTYP

Funktion:
- Monatsmatrix mit Tagen 1–28/29/30/31
- Umsatz und Kartentrinkgeld je Tag
- Küche = 1,5 % des Umsatzes
- Service = Kartentrinkgeld minus Küchenanteil
- Verteilung beider Töpfe nach Tagesstunden
- Bis 15 Service- und 10 Küchenmitarbeiter
- Neuer Monat übernimmt Mitarbeiter des Vormonats; Namen können dann geändert werden
- Enter springt bei Stunden nach unten; nach Service weiter zur Küche; danach nächster Tag
- Daten werden lokal im Browser gespeichert
- Sicherung/Laden über JSON-Datei

Für iPad/PWA:
Die Dateien müssen über HTTPS gehostet werden (z.B. GitHub Pages). Danach in Safari öffnen und „Zum Home-Bildschirm“ wählen. Der Service Worker ermöglicht danach Offline-Nutzung.

Wichtig:
Dies ist ein erster Prototyp. Vor produktiver Nutzung die Berechnungen mit der bestehenden Excel-Abrechnung für einen vollständigen Monat gegenprüfen.
