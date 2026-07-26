# Didaktischer Ablaufplan – Scratch-Kurs "Der Fisch in der Waldnaab"

**Zielgruppe:** bis 6 Kinder, 8–12 Jahre, keine Scratch-Vorerfahrung
**Dauer:** 120 Minuten
**Lernziel:** Jedes Kind hat am Ende ein funktionierendes, selbst gebautes Spiel und versteht dabei die Grundkonzepte Ereignisse, Bewegung, Bedingungen und Kollisionsabfrage.
**Spielidee:** Ein Fisch schwimmt die Waldnaab hoch bis zum Abenteuerspielplatz. Berührt er das Ufer, schwimmt er zurück an den Start.

Didaktisches Prinzip durchgehend: **"Ich mach vor – wir machen zusammen – du machst allein"**, in kleinen Schritten mit sofort sichtbarem Erfolg nach jedem Schritt. Kein Schritt dauert länger als 15 Minuten am Stück ohne Hands-on-Phase.

---

## Vorbereitung (vor dem Kurstag, nicht Teil der 120 Min.)

- [ ] Scratch-Lehrer-Account + Klasse mit bis zu 6 Kinder-Accounts anlegen, Zugangs-Zettel ausdrucken
- [ ] Grafiken erstellen: Waldnaab-Hintergrund (mit Ufer erkennbar), Fisch-Figur, Ziel-Figur "Abenteuerspielplatz", optional Gegner-Figuren (Ente, Angelhaken, Ast)
- [ ] Start-Projekt in der Klasse hinterlegen: Hintergrund + Fisch-Figur + Ziel-Figur bereits eingefügt, Fisch auf Startposition, damit Schritt A kaum Zeit kostet
- [ ] Urkunden-Vorlage mit Kursdatum vorbereiten, Namen können nach dem Kurs schnell ergänzt werden
- [ ] PCs/Tablets testen (Login funktioniert, Scratch lädt), Zugangs-Zettel bereitlegen

---

## Phase 1 – Ankommen & Einstieg (15 Min. | 0:00–0:15)

| Zeit | Inhalt | Methode |
|---|---|---|
| 0:00–0:05 | Begrüßung, kurze Vorstellungsrunde, Ankündigung: "Heute baut ihr euer eigenes Fisch-Spiel und nehmt es mit nach Hause" | Plenum, motivierend, konkret |
| 0:05–0:10 | Login mit dem Zugangs-Zettel, technischer Check | Einzelbetreuung, jedes Kind wird kurz bestätigt |
| 0:10–0:15 | Ganz knappe Scratch-Tour: Bühne, Figur, Kostüme, Blockpalette, grüne Flagge/Stopp-Zeichen – nur was gleich gebraucht wird | Zeigen am Beamer/Bildschirm, keine Details, die erst später relevant werden |

**Didaktischer Hinweis:** Keine vollständige Werkzeugerklärung. Kinder in diesem Alter verlieren nach 2–3 Minuten reiner Erklärung die Aufmerksamkeit — jedes weitere Werkzeug wird erst im Moment des Bedarfs erklärt (Just-in-time).

---

## Phase 2 – Kernbau in 5 Schritten (75 Min. | 0:15–1:30)

### Schritt A – Bühne & Figur einrichten (10 Min. | 0:15–0:25)
Vorbereitetes Startprojekt öffnen. Kinder sehen ihren Fisch bereits auf der Waldnaab. Kurzer Check: sitzt jeder im richtigen Projekt, sieht jeder seinen Fisch?
→ **Erfolgserlebnis:** "Ich habe schon ein eigenes Spielfeld."

### Schritt B – Bewegung mit Pfeiltasten (15 Min. | 0:25–0:40)
Ich-mach-vor: Block `wenn Taste [ ] gedrückt wird` + `ändere x um ( )` / `ändere y um ( )` zusammenstecken (für alle vier Pfeiltasten).
Kinder bauen nach, testen sofort, dürfen Geschwindigkeit selbst anpassen.
→ **Erfolgserlebnis:** Der Fisch schwimmt frei auf der Bühne.

### ☕ Kurze Pause (10 Min. | 0:40–0:50)
Bewegung, Getränk, informelles Herzeigen ("Schaut mal, wie schnell mein Fisch schwimmt!"). Wichtig als Puffer für unterschiedliches Tempo bis hierhin.

### Schritt C – Ufer als Hindernis (15 Min. | 0:50–1:05)
Erklärung als Spielregel: "Der Fisch muss im Wasser bleiben – berührt er das Ufer, schwimmt er zurück an den Start und versucht es erneut."
Baustein: `falls <wird Farbe [Ufer] berührt?>, dann` + `gehe zu x: ( ) y: ( )` (Startposition).
Das ist der schwierigste Konzeptsprung des Kurses (erste bedingte Verzweigung) — hier am längsten begleiten, notfalls als Paar-Lösung mit Nachbarkind.
→ **Erfolgserlebnis:** Der Fisch "merkt", wenn er falsch schwimmt.

### Schritt D – Ziel erkennen (10 Min. | 1:05–1:15)
Baustein: `falls <wird [Abenteuerspielplatz] berührt?>, dann` + `sage [Geschafft!] für ( ) Sekunden` + `stoppe [alles]`.
Kinder spielen ihr Spiel von Start bis Ziel einmal komplett durch.
→ **Erfolgserlebnis:** Das Spiel ist ab hier fertig und spielbar — jedes Kind hat spätestens jetzt ein lauffähiges Ergebnis, unabhängig vom weiteren Tempo.

### Schritt E – Differenzierung nach Tempo (15 Min. | 1:15–1:30)
- **Kinder, die fertig sind:** Erweiterung mit einem beweglichen Gegner (z. B. Ente oder Angelhaken, die sich hin- und herbewegt und bei Berührung ebenfalls zum Start zurückschickt)
- **Kinder, die noch an Schritt C/D arbeiten:** gezielte Einzelbetreuung, Fokus liegt darauf, dass am Ende **jedes** Kind ein spielbares Basis-Spiel hat — die Gegner-Erweiterung ist optional, kein Muss

**Didaktischer Hinweis:** Diese Stufe ist bewusst als Sicherheitsnetz eingebaut: Sie verhindert, dass schnelle Kinder warten müssen und langsamere Kinder unter Zeitdruck geraten. Das Kursziel ("jeder hat ein funktionierendes Spiel") bleibt für alle erreichbar.

---

## Phase 3 – Abschluss & Würdigung (25 Min. | 1:30–1:55)

| Zeit | Inhalt |
|---|---|
| 1:30–1:45 | Vorführ-Runde: jedes Kind zeigt ca. 2 Min. sein Spiel (bei 6 Kindern ≈ 12–15 Min.), andere dürfen zuschauen/kurz mitspielen |
| 1:45–1:50 | Kurze Reflexion im Kreis: Was hat Spaß gemacht? Was war schwierig? (Blitzlicht, keine lange Diskussion) |
| 1:50–1:55 | **Urkundenübergabe**: jedes Kind einzeln nach vorne, kurzer Applaus, Name wird genannt ("... hat heute sein erstes eigenes Computerspiel programmiert!") |

## Puffer (5 Min. | 1:55–2:00)
Verabschiedung, Hinweis, dass das Spiel im Scratch-Account gespeichert bleibt und zuhause weitergebaut werden kann.

---

## Zeitpuffer-Strategie

Die Pause (0:40–0:50) und Schritt E (0:15–1:30) sind die flexibelsten Blöcke — hier lässt sich Zeit einsparen, falls Login/Einstieg länger dauert, oder Zeit dranhängen, falls Schritt C mehr Begleitung braucht als geplant. Schritt D (Ziel erkennen) sollte spätestens um 1:20 erreicht sein, damit die Abschluss-Phase nicht gekürzt werden muss — die Urkundenübergabe ist der emotionale Abschluss des Kurses und sollte nicht wegfallen.

## Offene Punkte / nächste Schritte

- Scratch-Projekt-Vorlage (Hintergrund, Figuren, Startposition) muss noch erstellt werden
- Feinschritt-Anleitung (Blöcke im Detail, ggf. mit Screenshots) für Schritt B–E
- Urkunden-Vorlage (Design + Druckformat)
- Checkliste für Lehrer- und Kinder-Accounts auf Scratch
