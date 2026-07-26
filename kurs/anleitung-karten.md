# Anleitungskarten "Der Fisch in der Waldnaab"

> **Hinweis für Johannes (nicht mit ausdrucken):**
> Sechs Karten, je eine pro Bauschritt (A–F aus dem [Ablaufplan](ablaufplan.md)); Karte F ist der Profi-Bonus mit der Ente für die schnellsten Kinder. Jede Karte hat eine Vorderseite mit der Aufgabe und eine Rückseite mit der Lösung zum Nachschauen. Am besten druckst du doppelseitig: Stell in den Druckereinstellungen "Umschlagen an der kurzen Kante" ein, dann liegen Vorder- und Rückseite beim Wenden richtig übereinander.
>
> Zwei Stellen musst du vor dem Drucken noch mit echten Werten füllen, weil sie von eurem Startprojekt abhängen: Startposition des Fischs und Ufer-Farbe. Markiert mit ⚙️.
>
> Die Kästen `🖼️ [Platz für Screenshot]` sind für dich. Füg dort je einen Screenshot aus dem echten Scratch-Projekt ein, damit die Kinder die Blöcke wiedererkennen.
>
> Block-Farben zur Orientierung: 🟡 Ereignisse · 🟠 Steuerung · 🔵 Bewegung · 🔷 Fühlen · 🟣 Aussehen
>
> Alle Blocktexte hier sind gegen die echte deutsche Scratch-Oberfläche geprüft — etwa `wird [ ] berührt?`, `pralle vom Rand ab`, `Figur` statt "Sprite", `Pfeil oben`/`Pfeil unten` — damit die Kinder die Wörter genauso auf dem Bildschirm wiederfinden.

---
---

## Karte A – Vorderseite

# 🐟 Schritt A: Dein Spielfeld

**Deine Aufgabe:** Öffne dein Scratch-Projekt "Der Fisch in der Waldnaab". Es ist schon vorbereitet!

Schau dir dein Spielfeld an:

- Wo schwimmt dein Fisch gerade?
- Wo ist das Ufer?
- Wo ist das Ziel — der Abenteuerspielplatz?

**Tipp:** Klick oben links auf die grüne Fahne 🟢. Passiert noch nichts? Das ist völlig normal — dein Fisch kann noch nicht schwimmen. Das baust du gleich in Schritt B!

🖼️ *[Platz für Screenshot: Startprojekt mit Fisch, Ufer und Ziel]*

---

## Karte A – Rückseite

# 🔑 Lösung – Schritt A

Bei diesem Schritt gibt es noch nichts zu bauen. Du hast nur dein Projekt geöffnet und dir alles angeschaut.

Siehst du deinen Fisch auf dem Wasser, das Ufer am Rand und den Abenteuerspielplatz irgendwo auf der Karte? Dann ist alles bereit für Schritt B!

🖼️ *[Platz für Screenshot: beschriftetes Spielfeld mit Pfeilen auf Fisch/Ufer/Ziel]*

---
---

## Karte B – Vorderseite

# 🐟 Schritt B: Dein Fisch schwimmt los!

**Deine Aufgabe:** Bau vier kleine Programme, damit dein Fisch mit den Pfeiltasten schwimmen kann — nach rechts, links, oben und unten.

**So gehst du vor:**

1. Klick links auf die Kategorie 🟡 Ereignisse.
2. Zieh den Block `wenn Taste [ ] gedrückt wird` auf die Bühne.
3. Stell im Block die Pfeiltaste ein, die du gerade brauchst.
4. Klick auf die Kategorie 🔵 Bewegung.
5. Zieh den Block `ändere x um ( )` bzw. `ändere y um ( )` unter den Ereignis-Block.
6. Wiederhole das für alle vier Pfeiltasten.

**Tipp:** Für "rechts" und "oben" nimmst du eine positive Zahl (z. B. 10), für "links" und "unten" eine negative Zahl (z. B. -10). Probier ruhig aus, wie schnell dein Fisch schwimmen soll!

🖼️ *[Platz für Screenshot: leere Bühne mit Ereignisse- und Bewegung-Kategorie]*

---

## Karte B – Rückseite

# 🔑 Lösung – Schritt B

Du brauchst vier kleine Programme, die unabhängig nebeneinanderstehen:

```
🟡 wenn Taste [Pfeil rechts] gedrückt wird
🔵 ändere x um (10)
```

```
🟡 wenn Taste [Pfeil links] gedrückt wird
🔵 ändere x um (-10)
```

```
🟡 wenn Taste [Pfeil oben] gedrückt wird
🔵 ändere y um (10)
```

```
🟡 wenn Taste [Pfeil unten] gedrückt wird
🔵 ändere y um (-10)
```

**Testen:** Drück die Pfeiltasten — dein Fisch sollte in alle vier Richtungen schwimmen. Schwimmt er zu langsam oder zu schnell? Ändere die Zahl 10 nach oben oder unten!

🖼️ *[Platz für Screenshot: alle vier fertigen Mini-Skripte]*

---
---

## Karte C – Vorderseite

# 🐟 Schritt C: Nicht ans Ufer schwimmen!

**Deine Aufgabe:** Baue eine Regel: Wenn dein Fisch das Ufer berührt, schwimmt er automatisch zurück an seinen Startplatz.

**So gehst du vor:**

1. Zieh den Block `wenn grüne Fahne 🟢 angeklickt wird` (🟡 Ereignisse) auf eine neue, freie Stelle der Bühne.
2. Häng den Block `gehe zu x: ( ) y: ( )` (🔵 Bewegung) direkt darunter — er setzt deinen Fisch beim Start an seinen Platz.
3. Zieh darunter den Block `wiederhole fortlaufend` (🟠 Steuerung). Alles, was jetzt hineinkommt, läuft die ganze Zeit weiter.
4. Leg in die Dauerschleife einen `falls < >, dann`-Block (🟠 Steuerung).
5. Zieh in die kleine Lücke der `falls`-Bedingung den Block `wird Farbe [ ] berührt?` (🔷 Fühlen) und klick dann mit der Pipette die Ufer-Farbe auf deinem Hintergrund an.
6. Häng noch einmal den Block `gehe zu x: ( ) y: ( )` (🔵 Bewegung) in den `falls...dann`-Block — mit denselben Werten wie in Schritt 2.

**Tipp:** Das ist der kniffligste Schritt heute. Wenn du nicht weiterkommst, ist das total okay, frag einfach!

🖼️ *[Platz für Screenshot: leere Steuerung- und Fühlen-Kategorie]*

---

## Karte C – Rückseite

# 🔑 Lösung – Schritt C

```
🟡 wenn grüne Fahne 🟢 angeklickt wird
🔵 gehe zu x: (⚙️ Start-x) y: (⚙️ Start-y)
🟠 wiederhole fortlaufend
    🟠 falls < 🔷 wird Farbe [Ufer-Farbe] berührt? >, dann
        🔵 gehe zu x: (⚙️ Start-x) y: (⚙️ Start-y)
```

> **⚙️ Vor dem Ausdrucken anpassen:** Trage hier die tatsächliche Start-Position eures Fischs ein (z. B. x: -200 / y: -150). Wähle beim Vorführen außerdem die richtige Ufer-Farbe mit der Pipette direkt im Projekt aus — die lässt sich hier nicht als Text abbilden.

**Testen:** Klick die grüne Fahne, steuere den Fisch absichtlich ans Ufer — er sollte sofort zurück zum Start springen.

🖼️ *[Platz für Screenshot: fertiger Skript-Turm dieses Schritts]*

---
---

## Karte D – Vorderseite

# 🐟 Schritt D: Ziel erreicht!

**Deine Aufgabe:** Wenn dein Fisch den Abenteuerspielplatz berührt, soll "Geschafft!" erscheinen und das Spiel stoppen.

**So gehst du vor:**

1. Du brauchst keinen neuen Turm: Ergänze einfach deine Dauerschleife aus Schritt C um einen zweiten `falls...dann`-Block (🟠 Steuerung), direkt unter dem ersten.
2. Zieh den Block `wird [ ] berührt?` (🔷 Fühlen) in die neue falls-Lücke und wähl im Dropdown deine Abenteuerspielplatz-Figur aus.
3. Häng in den `falls...dann`-Block den Block `sage [ ] für ( ) Sekunden` (🟣 Aussehen) und trag den Text "Geschafft!" ein.
4. Häng darunter noch den Block `stoppe [alles]` (🟠 Steuerung) an.

🖼️ *[Platz für Screenshot: Dauerschleife mit zwei falls-Blöcken]*

---

## Karte D – Rückseite

# 🔑 Lösung – Schritt D

Zweiter Block, direkt unter dem Ufer-Check in derselben Dauerschleife:

```
🟡 wenn grüne Fahne 🟢 angeklickt wird
🔵 gehe zu x: (⚙️ Start-x) y: (⚙️ Start-y)
🟠 wiederhole fortlaufend
    🟠 falls < 🔷 wird Farbe [Ufer-Farbe] berührt? >, dann
        🔵 gehe zu x: (⚙️ Start-x) y: (⚙️ Start-y)
    🟠 falls < 🔷 wird [Abenteuerspielplatz] berührt? >, dann
        🟣 sage [Geschafft! 🎉] für (2) Sekunden
        🟠 stoppe [alles]
```

**Testen:** Schwimm einmal ganz von Start bis zum Abenteuerspielplatz durch. Kommt "Geschafft!"? Dann ist dein Spiel fertig spielbar! 🎉

🖼️ *[Platz für Screenshot: komplettes Skript inkl. Ziel-Check]*

---
---

## Karte E – Vorderseite

# 🐟 Schritt E: Bonus – ein Hindernis im Fluss!

Nur für Fisch-Profis, die schon fertig sind! Wenn dein Basis-Spiel funktioniert, kannst du jetzt ein bewegliches Hindernis einbauen — zum Beispiel die Angel 🎣.

**So gehst du vor:**

**Teil 1 – die Angel bewegt sich von selbst:**
Klick die Angel-Figur an und bau:
1. Den Block `wenn grüne Fahne 🟢 angeklickt wird` (🟡 Ereignisse).
2. Darunter den Block `wiederhole fortlaufend` (🟠 Steuerung).
3. Darin die Blöcke `gehe ( ) Schritte` und `pralle vom Rand ab` (beide 🔵 Bewegung).

**Teil 2 – wenn der Fisch die Angel berührt, geht's zurück zum Start:**
Klick wieder deine Fisch-Figur an und bau in die bestehende Dauerschleife einen dritten `falls...dann`-Block: gleiches Muster wie beim Ufer, diesmal mit `wird Angel berührt?`.

🖼️ *[Platz für Screenshot: Angel-Figur mit eigenem Bewegungsskript]*

---

## Karte E – Rückseite

# 🔑 Lösung – Schritt E

Skript auf der Angel-Figur:

```
🟡 wenn grüne Fahne 🟢 angeklickt wird
🟠 wiederhole fortlaufend
    🔵 gehe (5) Schritte
    🔵 pralle vom Rand ab
```

Dritter `falls...dann` auf der Fisch-Figur, in der bekannten Dauerschleife:

```
    🟠 falls < 🔷 wird [Angel] berührt? >, dann
        🔵 gehe zu x: (⚙️ Start-x) y: (⚙️ Start-y)
```

**Achtung, Reihenfolge:** Dieser neue Block muss vor dem "Geschafft!"-Block aus Schritt D stehen, sonst können beide Meldungen gleichzeitig auftauchen.

🖼️ *[Platz für Screenshot: fertiges Fisch-Skript mit allen drei falls-Blöcken]*

---
---

## Karte F – Vorderseite

# 🐟 Schritt F: Profi-Bonus – die Ente patrouilliert!

Nur für echte Profis, die auch mit der Angel schon fertig sind! Jetzt kommt ein zweites Hindernis dazu: eine Ente 🦆, die zwischen Ufer und Ufer hin- und herschwimmt.

**So gehst du vor:**

**Teil 1 – die Ente bewegt sich von selbst:**
Klick die Ente-Figur an. Der Aufbau ist genau derselbe wie bei der Angel in Schritt E:
1. Den Block `wenn grüne Fahne 🟢 angeklickt wird` (🟡 Ereignisse).
2. Darunter den Block `wiederhole fortlaufend` (🟠 Steuerung).
3. Darin die Blöcke `gehe ( ) Schritte` und `pralle vom Rand ab` (beide 🔵 Bewegung).

**Tipp:** Damit die Ente hoch und runter patrouilliert statt links-rechts wie die Angel, ergänze vor der Dauerschleife noch den Block `setze Richtung auf ( ) Grad` (🔵 Bewegung) mit dem Wert 0 — dann wird's abwechslungsreicher.

**Teil 2 – wenn der Fisch die Ente berührt, geht's zurück zum Start:**
Klick wieder deine Fisch-Figur an. Jetzt kommt ein vierter `falls...dann`-Block in dieselbe Dauerschleife dazu — Bedingung diesmal: `wird Ente berührt?`, Wirkung genau wie bei Ufer und Angel.

🖼️ *[Platz für Screenshot: Ente-Figur mit eigenem Bewegungsskript]*

---

## Karte F – Rückseite

# 🔑 Lösung – Schritt F

Skript auf der Ente-Figur:

```
🟡 wenn grüne Fahne 🟢 angeklickt wird
🔵 setze Richtung auf (0) Grad
🟠 wiederhole fortlaufend
    🔵 gehe (4) Schritte
    🔵 pralle vom Rand ab
```

Vierter `falls...dann` auf der Fisch-Figur, wieder in derselben Dauerschleife:

```
    🟠 falls < 🔷 wird [Ente] berührt? >, dann
        🔵 gehe zu x: (⚙️ Start-x) y: (⚙️ Start-y)
```

**Profi-Tipp:** Jetzt hat dein Fisch zwei Gegner gleichzeitig im Weg, Angel und Ente. Falls das zu leicht ist: Erhöh einfach die Zahl bei `gehe ( ) Schritte`, dann patrouillieren beide schneller.

🖼️ *[Platz für Screenshot: fertiges Fisch-Skript mit allen vier falls-Blöcken]*
