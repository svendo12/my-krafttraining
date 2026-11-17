# My Krafttraining – iPhone-Web-App

## Was enthalten ist
- 8 Trainingsstationen wie besprochen
- Einträge mit Datum, Gewicht, Sätzen, Wiederholungen und Notiz
- Status je Station: grün (0–2 Tage), orange (3–4 Tage), rot (ab 5 Tagen)
- Kalender, Verlauf und JSON-Export/-Import
- Lokale Speicherung im Browser; keine Push-Benachrichtigungen

## Wichtig: Installation auf dem iPhone
Diese Dateien sind die fertige App-Webdatei. Damit Safari sie als installierbare Web-App anbieten kann, müssen sie einmalig auf einer HTTPS-Webadresse veröffentlicht werden. Das kann z. B. über einen Webhosting-Anbieter oder einen statischen Hosting-Dienst erfolgen. Ich kann die Veröffentlichung nicht direkt aus diesem Chat heraus übernehmen.

1. Alle Dateien aus diesem Ordner auf einen HTTPS-Webhost hochladen.
2. Die Adresse auf dem iPhone in Safari öffnen.
3. Teilen → „Zum Home-Bildschirm“ → „Als Web-App öffnen“ aktivieren (falls angeboten) → Hinzufügen.
4. App starten und unter „Verlauf“ regelmäßig „Daten exportieren“ nutzen.

## Datenspeicherung
Trainingsdaten liegen lokal im Safari-/Web-App-Speicher dieses iPhones. Sie werden nicht automatisch zwischen Geräten synchronisiert. Browserdaten löschen kann lokale Daten entfernen. Deshalb regelmäßig eine JSON-Sicherung exportieren und sicher ablegen.

## Hinweise
- Die Statusanzeige richtet sich nach dem letzten Eintrag pro Station.
- Noch nie erfasste Stationen zeigen „Noch kein Eintrag“.
- Liegestützen/Klimmzüge können ohne Gewicht erfasst werden.
