# hf-widgets

Widgets für mein HF-Dashboard in Notion. Einbetten mit `/embed` und der GitHub-Pages-Adresse.
Standard ist dunkel, für helles Notion `?theme=light` anhängen.

| Widget | Datei | Inhalt |
|---|---|---|
| Heute | `today.html` | Analoguhr, Begrüssung, Datum, Kalenderwoche, Fortschritt von Tag, Woche und Jahr. Optional `?von=JJJJ-MM-TT&bis=JJJJ-MM-TT` für den Semesterfortschritt und `&pruefung=JJJJ-MM-TT&name=Modul` für einen Countdown |
| Uhr | `clock.html` | Analoguhr mit Digitalzeit |
| Fokus-Timer | `focus.html` | Pomodoro mit Auto-Zyklus, Tagesziel, Fokus-Minuten, 5 Farbthemen |
| Security-Toolkit | `toolkit.html` | Port-Quiz, OSI-Quiz, Subnetting-Training mit VLSM, Krypto, Passwort-Check, Subnetzrechner mit CIDR-Spickzettel, chmod-Rechner, Konverter mit Unix-Zeitstempel, Notenrechner, Glossar mit Quiz, Befehlssuche mit Quiz |
| Whiteboard | `whiteboard.html` | Stift, Marker, Linie, Pfeil, Rechteck, Text, Raster, Export als PNG |

Alle Daten (Rekorde, Whiteboard, Timer-Statistik) bleiben lokal im Browser.
