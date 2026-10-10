# Mein Linienfahrplan – Version 1.0.0x2

## Installation / Veröffentlichung
Lade die fünf Dateien in das Stammverzeichnis deines GitHub-Pages-Repositories und bestätige den Commit. Die App verwendet ein dunkles Design als Standard.

## Änderungen
- Dunkles Design als Standard.
- Klarer Status: an Haltestelle, unterwegs, Wendezeit, pausiert.
- Nächster Halt bleibt während der Fahrt das Ziel und wechselt erst nach bestätigter Ankunft und anschließender Abfahrt.
- Unbegrenzter Umlauf zwischen Hin- und Rückfahrt.
- Einstellbare Fahrzeiten je Abschnitt für beide Richtungen, Haltezeit und Wendezeit.
- Anzeige der Abweichung in Minuten und Sekunden sowie einfache Betriebsstatistik.
- Service-Worker-Cache mit neuer Versionskennung.

## Hinweise zum Prototyp
Dies ist weiterhin eine Testversion. Zeitpläne werden aus den tatsächlichen manuellen Abfahrtsbestätigungen fortgeschrieben; es gibt noch keine automatische GPS-Erkennung. Bitte vor einem längeren Einsatz insbesondere die Übergänge an den Endhaltestellen und die Verspätungsberechnung prüfen. Statistik wird beim Beenden des Betriebs zurückgesetzt.
