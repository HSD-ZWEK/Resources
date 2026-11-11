# OpenCode mit KI:connect.nrw

Lehrende legen einen kleinen Wissensordner an und lassen die KI daraus Antworten an Studierende entwerfen. OpenCode läuft als Programm auf dem eigenen Rechner. Die Anfragen gehen an KI:connect.nrw, die Plattform der Hochschulen in Nordrhein-Westfalen.

## Dateien

| Datei | Beschreibung |
|---|---|
| [`Anleitung-OpenCode-einrichten/`](Anleitung-OpenCode-einrichten/) | Anleitung für Lehrende: installieren, Ordner anlegen, Schlüssel eintragen, Testfrage |
| [`starterordner-ki-wissen.zip`](starterordner-ki-wissen.zip) | Starterordner zum Herunterladen (Schritt 3 der Anleitung) |
| [`Starterordner-ki-wissen/`](Starterordner-ki-wissen/) | derselbe Inhalt zum Ansehen im Browser |

## Was im Starterordner liegt

| Datei oder Ordner | Inhalt |
|---|---|
| `opencode.json` | KI:connect als einziger Anbieter, Modell GPT-OSS 120B, keine Befehle, kein Internet, Schreiben nur im Ordner. Ohne Schlüssel. |
| `AGENTS.md` | Regeln für die KI: Deutsch, Sie-Form, Fakten nur aus `wissen/` |
| `wissen/` | Wissensspeicher: `INDEX.md` als Übersicht, zwei erfundene Beispiele, eine Vorlage für das eigene Modul, dazu Wissen für die eigene Lehre (siehe unten) |
| `anfragen/` | Testfrage und drei erfundene Anfragen von Studierenden |
| `entwuerfe/` | hier legt die KI ihre Antwortentwürfe ab |
| `.opencode/` | Skills `antwortbaustein`, `aufgabenstellung`, `methodenwahl` und `barrierefrei-check`, Prüf-Agent `pruefer` |

Alle Personen, Fristen und Anfragen im Starterordner sind erfunden.

## Wissen für die eigene Lehre

| Datei | Inhalt |
|---|---|
| `lehre-planen.md` | 3Z-Formel, sieben Schritte der Seminarkonzeption, Lernziele nach WAS–WOMIT–WOZU, Verben nach Taxonomiestufen, Lernrhythmus, Feedback und Evaluation |
| `methoden.md` | Methodenkartei des ZWEK mit 12 Methoden für eine Sitzung, darunter Fishbowl, Tandem-Rollenspiel und Anonymisierungsübung |
| `barrierefreiheit.md` | Handreichung Barrierefreiheit: Word, PowerPoint, Bilder, Videos, Aufgaben, Moodle, Sofort-Checkliste |
| `lehrmaterial-und-lizenz.md` | Arbeitsmaterial, CC BY 4.0, Quellenangabe nach TULLU |
| `ki-regeln.md` | Pflichten aus der KI-Richtlinie Nr. 1060 der HSD (Auszug) |
| `ki-in-der-lehre.md` | wofür KI in der Lehre nützt, etwa erfundene Fallvignetten, Selbsttests im GIFT-Format, Bewertungsraster |
| `moodle.md` | welches Hilfsblatt des ZWEK welche Moodle-Frage beantwortet |

Regeln stehen getrennt von Empfehlungen. Jeder Fakt nennt Quelle und Datum. Was im Ordner fehlt, nennt `INDEX.md`: Praxisphasen, Diversität, belastende Fallschilderungen, Nachteilsausgleich, Prüfungsrecht.

## Regeln für den eigenen Wissensordner

- Keine Namen, Mailadressen oder Matrikelnummern. Aus dem Namen wird `[NAME]`.
- Nichts Vertrauliches: keine Prüfungsleistungen, Gutachten, Protokolle.
- Jeder Fakt bekommt Quelle und Datum.
- Den eigenen KI:connect-Schlüssel nie in eine Datei schreiben.

## Lizenz

CC BY 4.0, Christian-Maximilian Steier, ZWEK, Hochschule Düsseldorf. [creativecommons.org/licenses/by/4.0/deed.de](https://creativecommons.org/licenses/by/4.0/deed.de)
