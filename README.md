# tbz-tools

Eigenständige HTML-Übungswerkzeuge für den Unterricht (Technische
Berufsschule Zürich). Wird über GitHub Pages ausgeliefert; die Quelle
der Werkzeuge liegt im (privaten) Unterrichts-Repo `tbz` und wird von
dort hierher kopiert.

- `projektionsmethode-trainer.html` – TZ Kap. 2, sechs Ansichten nach
  Projektionsmethode 1 zuordnen (drehbares 3D-Modell).
- `skript-aufgaben.html` – TZ Kap. 2.3, die Werkstücke der
  Skript-Aufgaben S. 18–21 als 3D-Modell; Ansichten aufdecken oder als
  Quiz zuordnen (vom Trainer aus verlinkt). Dazu die vier Teile der
  Übung 2.3.3 (S. 24, ISO aus V, D, SL): Lösung ist der Körper selbst,
  zuerst verdeckt, mit Taste für die isometrische Lage.
- `konstante-beschleunigung-animation.html` – Physik Kap. 2, Bewegung
  mit konstanter Beschleunigung: Fahrzeug, Zerlegung
  x = x₀ + v₀·t + ½·a·t² und die drei Diagramme x–t, v–t, a–t.
- `konstante-beschleunigung-ohne-zeit.html` – Physik Kap. 2, Gleichung
  ohne Zeit v² = v₀² + 2·a·(x − x₀): gesuchte Grösse wählen (v, v₀, a
  oder x), Rechnung mit Vereinfachung und eingesetzten Zahlen, beide
  Wurzel-Vorzeichen, Fahrzeug auf der Strecke, Diagramme v–x, v²–x und
  v–t (Herkunft).
- `schiefe-ebene-simulation.html` – Physik Versuch 1, Wagen auf der
  schiefen Ebene ohne Reibung, Höhe einstellbar; Diagramme s–t, v–t,
  a–t und Messreihe a(h) bzw. a(α).
- `wurf-simulator.html` – Physik Kap. 3, Wurfbewegungen: schiefer
  Wurf mit Vektoren und Diagrammen, zwei Kugeln (waagrechter Wurf und
  freier Fall gleichzeitig), Affenschuss (Ziel fällt im Schussmoment),
  Reichweite gegen Winkel und virtuelles Labor «g bestimmen» auf einem
  unbekannten Planeten.
- `pruefungstrainer-kinematik.html` – Physik Kap. 2, Vorbereitung auf
  Prüfung 2: fünf Situationen (Tram fährt an, Auto bremst, Stein fällt,
  Ball nach oben, schiefe Ebene) mit Animation und zwei Diagrammen, dazu
  Multiple-Choice-Fragen zum Lösungsweg (welche Gleichung, welches
  Vorzeichen, welches Diagramm, welches Resultat) mit Begründung;
  Zahlen zufällig, Ergebnis pro Situation bleibt im Browser. Daneben die
  Formelsammlung der Prüfung; nach jeder Antwort ist die passende Formel
  markiert.
- `klammern-trainer.html` – Algebra Kap. 2.4, Terme vereinfachen Schritt
  für Schritt: Lernen (vor jedem Schritt die Regel wählen – Klammer
  ausrechnen, Distributivgesetz, Produkte berechnen, Plus/Minus vor der
  Klammer, Zusammenfassen – die Stelle wird markiert) und Üben (eigenen
  Rechenweg Zeile für Zeile schreiben, Rückmeldung mit typischen Fehlern,
  Tipp und «Schritt zeigen»). Sieben Stufen mit Zufallsaufgaben, eigene
  Terme möglich.
- `ti-nspire.html` – Physik/Algebra Kap. 0, TI-Nspire CX II-T CAS:
  Tutorial und Trainer in zehn Stationen (Lernen mit Tastenfeld und
  Bildschirm-Nachbau, Üben in drei Stufen mit Aufgaben aus den Skripten).

## TI-Nspire – Tutorial & Trainer

![TI-Nspire Tutorial & Trainer](ti-nspire-screenshot.png)

**<https://nunigan.github.io/tbz-tools/ti-nspire.html>** – den TI-Nspire
CX II-T CAS Schritt für Schritt lernen (Tastenfeld und Bildschirm-Nachbau,
Tasten leuchten auf) und mit dem Gerät daneben üben (drei Stufen pro
Station, Aufgaben mit Zufallszahlen und Rückmeldung zu typischen Fehlern).
Stationen: Start, Rechnen, Terme (CAS), Gleichungen, Variablen,
Trigonometrie, Graphs, Einheiten, Messreihen, Sensoren. Für Berufsschule,
BMS und Gymnasium, erstes Jahr; deutsches Gerätemenü. Eine HTML-Datei,
keine Abhängigkeiten, läuft offline; Fortschritt bleibt im Browser.

**Lizenz:** `ti-nspire.html` steht unter
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.de)
(M. Schmid, Technische Berufsschule Zürich) – frei nutzen, anpassen und
weitergeben, mit Namensnennung und unter gleicher Lizenz. Die übrigen
Werkzeuge in diesem Repo sind vorerst nur für den Unterrichtsgebrauch
freigegeben.

**Mitmachen:** Stimmt ein Tastenweg auf deinem Gerät nicht, fehlt eine
Aufgabe, ist etwas unklar? Bitte ein
[Issue](https://github.com/Nunigan/tbz-tools/issues) eröffnen. Alle
Tastenwege sind gegen das TI-Handbuch geprüft; einzelne Menünummern noch
nicht am Gerät.
