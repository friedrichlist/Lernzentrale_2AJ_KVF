# Lernzentrale KVF

Training und Prüfungsvorbereitung für alle drei Ausbildungsjahre der Kaufleute für Versicherungen und Finanzanlagen (BbS IV „Friedrich List“, Halle): Startseite mit Prüfungspass je Klasse, Prüfungstrainings (GAP 1, später WISO und GAP 2) und je Lernsituation ein Modul als einzelne HTML-Datei.

**Live:** https://friedrichlist.github.io/Lernzentrale_KVF/ (bis 10.10.2026: `Lernzentrale_2AJ_KVF`)

Der Lernstand bleibt im Browser des jeweiligen Geräts. Kein Backend, keine Anmeldung, keine Datenübertragung. Die Startseite funktioniert nur, wenn alle Seiten in diesem Repository liegen (gleiche Adresse = gemeinsamer Browserspeicher). Die Auswertung der Meldecodes ist nur für die Lehrkraft und wird hier nicht hochgeladen.

| Datei | Zweck |
|---|---|
| `index.html` | Startseite: Klassenwahl, Prüfungen der Klasse mit Terminen, Prüfungspass (Trainingspunkte, Prüfungsreife), Module, Klassen-Challenge – gebaut mit `bau_pass.py` |
| `KVF_LF06_LS06.1_Lernzentrale.html` | LF 6 · LS 06.1 „Kfz versichern – die Kundenakte Brehmer“ (TE 1–5) |
| `GAP1_Pruefungstraining.html` | Prüfungstraining GAP 1 (6 Prüfungsbereiche, 153 Aufgaben, Simulation) |
| `pruefungspass.html` | Weiterleitung auf `index.html` (für Links aus den Modulen) |
| `datenschutz.html` | Datenschutzhinweis |

Mein KVF verlinkt mit `index.html?klasse=KVF26` (Klassenkennung); die Startseite merkt sich die Klasse.

## Neue Fassung einspielen

Die Module werden im OneDrive unter `KVF/Interaktive Lernzentrale` gebaut (`Werkzeug/bau_lz.py`, `Werkzeug/pass/bau_pass.py`, Daten in `Daten/`). Hier wird nur die fertige
Datei aus `Module/` hochgeladen (nie `Module/Pruefungspass/Lehrkraft/`) – nie `Daten/`, `Werkzeug/` oder `Berichte/`. Nach dem Hochladen dauert es ein bis zwei Minuten, bis GitHub Pages
die neue Fassung ausliefert.
