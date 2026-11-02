# Nutzungserlaubnis

Copyright © 2026 Bös, ARS

## Erlaubt

Der **ARS-ER-Editor** darf von jeder Person und jeder Bildungseinrichtung

- kostenlos genutzt,
- unverändert weitergegeben und
- im Unterricht, in der Ausbildung und zum Selbststudium eingesetzt

werden. Eine Anmeldung oder Rückmeldung ist nicht nötig; über einen
Hinweis, wo das Programm eingesetzt wird, freue ich mich trotzdem.

Bei Weitergabe bitte das vollständige Paket zusammen mit dieser Datei
und der `LIESMICH.txt` weitergeben.

## Nicht erlaubt

- **Kommerzielle Nutzung**: Verkauf, Vermietung, Bündelung mit
  kostenpflichtigen Angeboten oder Nutzung in kostenpflichtigen
  Schulungen ohne vorherige Absprache.
- **Veränderung des Programms** und Weitergabe veränderter Fassungen.
  Der Quelltext ist nicht Teil dieser Veröffentlichung. Gemeint ist der
  **eigene** Teil des Programms; für die mitgelieferte Bibliothek
  FlatLaf gilt deren eigene, weitergehende Lizenz — siehe unten.

## Warum der Quelltext fehlt

Drei Funktionen — das automatische Überführen ins Relationenmodell, die
textuelle Schreibweise und die CREATE-Befehle — sind durch ein Kennwort
geschützt. Sie sind Prüfungsstoff: Wenn das Werkzeug die Überführung auf
Knopfdruck erledigt, übt sie niemand mehr.

Läge der Quelltext offen, wäre diese Sperre in wenigen Minuten entfernt.
Das ist der einzige Grund. Lehrkräfte, die den Quelltext für ihren
eigenen Unterricht ansehen möchten, dürfen mich gerne fragen.

## Mitgelieferte Fremdsoftware

Seit V2.0 steckt in der JAR-Datei eine fremde Bibliothek:

**[FlatLaf](https://www.formdev.com/flatlaf/) 3.7.2**, © Karl Tauber /
FormDev Software GmbH, **Apache License 2.0**. Sie liefert das dunkle
Erscheinungsbild; mit dem Standardaussehen von Java wäre es nicht zu machen.

- Die Bibliothek ist **unverändert** übernommen.
- Ihr **vollständiger Lizenztext** liegt in der JAR unter
  `META-INF/LIZENZ-FlatLaf.txt` — byte-gleich mit dem Original.
- Die Apache License 2.0 erlaubt ausdrücklich auch das **Verändern und
  Weitergeben der Bibliothek selbst**. Dieses Recht schränkt die
  Nutzungserlaubnis oben nicht ein und kann es auch gar nicht.

Alles Übrige im Paket — Programm, Beispiele, Anleitung — ist eigene Arbeit
und untersteht dieser Nutzungserlaubnis.

## Keine Gewährleistung

Das Programm wird bereitgestellt **wie es ist**, ohne Gewährleistung
irgendeiner Art. Die Nutzung erfolgt auf eigenes Risiko; eine Haftung für
Schäden oder Datenverlust wird — soweit gesetzlich zulässig —
ausgeschlossen.

Das gilt ausdrücklich auch für die erzeugten **CREATE-Befehle**: Sie
enthalten auf Wunsch `DROP TABLE IF EXISTS`. Wer ein solches Skript auf
einer Datenbank mit echten Daten ausführt, verliert sie. Das Kästchen im
Dialog schaltet es ab.

## Beispieldateien

Die mitgelieferten Beispiele sind eigene Nachbildungen typischer
Aufgabenstellungen, teils angelehnt an veröffentlichte Abituraufgaben des
Landes Hessen. Sie enthalten keine Aufgabentexte, sondern nur die
Diagrammstrukturen.
