# Anleitungskarten "Der Fisch in der Waldnaab"

> **Hinweis für Johannes (nicht mit ausdrucken):**
> Sechs Karten, je eine pro Bauschritt (A–F aus dem [Ablaufplan](ablaufplan.md); Karte F ist der Profi-Bonus mit der Ente für die schnellsten Kinder). Jede Karte hat eine **Vorderseite** (Aufgabe, für die Kinder zum Selbermachen) und eine **Rückseite** (Lösung zum Nachschauen). Am besten doppelseitig drucken, sodass beim Wenden am **kurzen** Rand ("Umschlagen an der kurzen Kante" in den Druckereinstellungen) Vorder- und Rückseite jeder Karte zusammenpassen.
>
> An zwei Stellen musst du vor dem Drucken noch echte Werte eintragen, weil sie von eurem fertigen Startprojekt abhängen (Startposition des Fischs, Ufer-Farbe): markiert mit **⚙️ Vor dem Ausdrucken anpassen**.
>
> Die Kästen `🖼️ [Platz für Screenshot]` sind für dich gedacht — dort kannst du je einen Screenshot aus dem echten Scratch-Projekt einfügen, damit die Kinder die Blöcke wiedererkennen.
>
> Block-Farben zur Orientierung (Scratch-Kategorien): 🟡 Ereignisse · 🟠 Steuerung · 🔵 Bewegung · 🔷 Fühlen · 🟣 Aussehen
>
> **Begriffs-Hinweis:** Alle Blocktexte hier sind 1:1 gegen die echte deutsche Scratch-Oberfläche geprüft (u. a. `wird [ ] berührt?`, `pralle vom Rand ab`, `Figur` statt "Sprite", `Pfeil oben`/`Pfeil unten`), damit die Kinder die Wörter exakt auf dem Bildschirm wiederfinden.

---
---

## Karte A – Vorderseite

# 🐟 Schritt A: Dein Spielfeld

**Deine Aufgabe:** Öffne dein Scratch-Projekt "Der Fisch in der Waldnaab". Es ist schon vorbereitet!

Schau dir dein Spielfeld an:

- Wo schwimmt dein Fisch gerade?
- Wo ist das Ufer?
- Wo ist das Ziel — der Abenteuerspielplatz?

**Tipp:** Klick oben links auf die 🟢 grüne Fahne. Passiert noch nichts? Das ist völlig normal — dein Fisch kann noch nicht schwimmen. Das baust du gleich in Schritt B!

🖼️ *[Platz für Screenshot: Startprojekt mit Fisch, Ufer und Ziel]*

---

## Karte A – Rückseite

# 🔑 Lösung – Schritt A

Bei diesem Schritt gibt es noch nichts zu bauen — du hast nur dein Projekt geöffnet und dir alles angeschaut. ✅

Wenn du das hier siehst:

- deinen Fisch 🐟 auf dem Wasser
- das Ufer am Rand
- den Abenteuerspielplatz irgendwo auf der Karte

...dann ist alles bereit für Schritt B!

🖼️ *[Platz für Screenshot: beschriftetes Spielfeld mit Pfeilen auf Fisch/Ufer/Ziel]*

---
---

## Karte B – Vorderseite

# 🐟 Schritt B: Dein Fisch schwimmt los!

**Deine Aufgabe:** Bau vier kleine Programme, damit dein Fisch mit den Pfeiltasten schwimmen kann — nach rechts, links, oben und unten.

**So gehst du vor:**

1. Klick links auf die Kategorie **🟡 Ereignisse**.
2. Zieh den Block `wenn Taste [ ] gedrückt wird` auf die Bühne.
3. Stell im Block die Pfeiltaste ein, die du gerade brauchst.
4. Klick auf die Kategorie **🔵 Bewegung**.
5. Zieh den Block `ändere x um ( )` bzw. `ändere y um ( )` **unter** den Ereignis-Block.
6. Wiederhole das für alle vier Pfeiltasten.

**Tipp:** Für "rechts" und "oben" nimmst du eine positive Zahl (z. B. 10), für "links" und "unten" eine negative Zahl (z. B. -10). Probier ruhig aus, wie schnell dein Fisch schwimmen soll!

🖼️ *[Platz für Screenshot: leere Bühne mit Ereignisse- und Bewegung-Kategorie]*

---

## Karte B – Rückseite

# 🔑 Lösung – Schritt B

Du brauchst **vier** kleine Programme, die unabhängig nebeneinanderstehen:

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

1. Kategorie **🟡 Ereignisse**: Block `wenn grüne Fahne 🟢 angeklickt wird` auf eine neue, freie Stelle der Bühne ziehen.
2. Kategorie **🔵 Bewegung**: Block `gehe zu x: ( ) y: ( )` direkt darunter — das setzt deinen Fisch beim Start an seinen Platz.
3. Kategorie **🟠 Steuerung**: Block `wiederhole fortlaufend` darunter ziehen — alles, was du jetzt reinlegst, läuft die ganze Zeit weiter.
4. In die Dauerschleife hinein: Kategorie **🟠 Steuerung** → Block `falls < >, dann`.
5. In die kleine Lücke der `falls`-Bedingung: Kategorie **🔷 Fühlen** → Block `wird Farbe [ ] berührt?` — dann mit der Pipette die Ufer-Farbe auf deinem Hintergrund anklicken.
6. In den `falls...dann`-Block hinein: nochmal **🔵 Bewegung** → `gehe zu x: ( ) y: ( )`, gleiche Werte wie in Schritt 2.

**Tipp:** Das ist der kniffligste Schritt heute — wenn du nicht weiterkommst, ist das total okay, frag einfach!

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

> **⚙️ Vor dem Ausdrucken anpassen:** Trage hier die tatsächliche Start-Position eures Fischs ein (z. B. x: -200 / y: -150) und wähle beim Vorführen die richtige Ufer-Farbe mit der Pipette direkt im Projekt aus — die kann hier nicht als Text abgebildet werden.

**Testen:** Klick die grüne Fahne, steuere den Fisch absichtlich ans Ufer — er sollte sofort zurück zum Start springen.

🖼️ *[Platz für Screenshot: fertiger Skript-Turm dieses Schritts]*

---
---

## Karte D – Vorderseite

# 🐟 Schritt D: Ziel erreicht!

**Deine Aufgabe:** Wenn dein Fisch den Abenteuerspielplatz berührt, soll "Geschafft!" erscheinen und das Spiel stoppen.

**So gehst du vor:**

1. Du brauchst **keinen neuen Turm** — ergänze einfach deine Dauerschleife aus Schritt C um einen zweiten `falls...dann`-Block (Kategorie **🟠 Steuerung**), direkt unter dem ersten, innerhalb derselben Dauerschleife.
2. In die `falls`-Lücke: Kategorie **🔷 Fühlen** → Block `wird [ ] berührt?`, dann im Dropdown deine Abenteuerspielplatz-Figur auswählen.
3. In den `falls...dann`-Block hinein: Kategorie **🟣 Aussehen** → Block `sage [ ] für ( ) Sekunden`, Text "Geschafft!" eintragen.
4. Darunter: Kategorie **🟠 Steuerung** → Block `stoppe [alles]`.

🖼️ *[Platz für Screenshot: Dauerschleife mit zwei falls-Blöcken]*

---

## Karte D – Rückseite

# 🔑 Lösung – Schritt D

Ergänzung **innerhalb derselben Dauerschleife** von Schritt C, als zweiter Block direkt unter dem Ufer-Check:

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

**Nur für Fisch-Profis, die schon fertig sind!** Wenn dein Basis-Spiel funktioniert, kannst du jetzt ein bewegliches Hindernis einbauen — zum Beispiel die Angel 🎣.

**So gehst du vor:**

**Teil 1 – die Angel bewegt sich von selbst:**
Klick die Angel-Figur an und bau:
1. Kategorie **🟡 Ereignisse**: `wenn grüne Fahne 🟢 angeklickt wird`
2. Kategorie **🟠 Steuerung**: `wiederhole fortlaufend`
3. Darin: Kategorie **🔵 Bewegung**: `gehe ( ) Schritte` und `pralle vom Rand ab`

**Teil 2 – wenn der Fisch die Angel berührt, geht's zurück zum Start:**
Klick wieder deine Fisch-Figur an. Baue einen **dritten** `falls...dann`-Block in deine bestehende Dauerschleife aus Schritt C/D — genau nach demselben Muster wie beim Ufer, nur diesmal mit "wird Angel berührt?".

🖼️ *[Platz für Screenshot: Angel-Figur mit eigenem Bewegungsskript]*

---

## Karte E – Rückseite

# 🔑 Lösung – Schritt E

**Skript auf der Angel-Figur:**

```
🟡 wenn grüne Fahne 🟢 angeklickt wird
🟠 wiederhole fortlaufend
    🔵 gehe (5) Schritte
    🔵 pralle vom Rand ab
```

**Ergänzung auf der Fisch-Figur**, dritter `falls...dann` in der bekannten Dauerschleife:

```
    🟠 falls < 🔷 wird [Angel] berührt? >, dann
        🔵 gehe zu x: (⚙️ Start-x) y: (⚙️ Start-y)
```

**Geschafft-Skript merken:** Achte darauf, dass dieser neue Block **vor** dem "Geschafft!"-Block aus Schritt D steht, sonst könnte es komisch aussehen, wenn beides gleichzeitig passiert.

🖼️ *[Platz für Screenshot: fertiges Fisch-Skript mit allen drei falls-Blöcken]*

---
---

## Karte F – Vorderseite

# 🐟 Schritt F: Profi-Bonus – die Ente patrouilliert!

**Nur für echte Profis, die auch mit der Angel schon fertig sind!** Jetzt kommt ein zweites Hindernis dazu: eine Ente 🦆, die zwischen Ufer und Ufer hin- und herschwimmt.

**So gehst du vor:**

**Teil 1 – die Ente bewegt sich von selbst:**
Klick die Ente-Figur an und bau **nach genau demselben Muster wie bei der Angel** in Schritt E:
1. Kategorie **🟡 Ereignisse**: `wenn grüne Fahne 🟢 angeklickt wird`
2. Kategorie **🟠 Steuerung**: `wiederhole fortlaufend`
3. Darin: Kategorie **🔵 Bewegung**: `gehe ( ) Schritte` und `pralle vom Rand ab`

**Tipp:** Damit die Ente **hoch und runter** statt links-rechts patrouilliert (spannender, weil anders als die Angel!), ergänze vor der Dauerschleife noch: Kategorie **🔵 Bewegung** → Block `setze Richtung auf ( ) Grad` mit dem Wert `0`.

**Teil 2 – wenn der Fisch die Ente berührt, geht's zurück zum Start:**
Klick wieder deine Fisch-Figur an. Baue einen **vierten** `falls...dann`-Block in deine bestehende Dauerschleife — genau nach demselben Muster wie bei Ufer und Angel, nur diesmal mit "wird Ente berührt?".

🖼️ *[Platz für Screenshot: Ente-Figur mit eigenem Bewegungsskript]*

---

## Karte F – Rückseite

# 🔑 Lösung – Schritt F

**Skript auf der Ente-Figur:**

```
🟡 wenn grüne Fahne 🟢 angeklickt wird
🔵 setze Richtung auf (0) Grad
🟠 wiederhole fortlaufend
    🔵 gehe (4) Schritte
    🔵 pralle vom Rand ab
```

**Ergänzung auf der Fisch-Figur**, vierter `falls...dann` in der bekannten Dauerschleife:

```
    🟠 falls < 🔷 wird [Ente] berührt? >, dann
        🔵 gehe zu x: (⚙️ Start-x) y: (⚙️ Start-y)
```

**Profi-Tipp:** Jetzt hat dein Fisch zwei Gegner gleichzeitig im Weg — Angel **und** Ente. Wenn das zu leicht ist: Erhöh einfach die Zahl bei `gehe ( ) Schritte` bei beiden, damit sie schneller patrouillieren!

🖼️ *[Platz für Screenshot: fertiges Fisch-Skript mit allen vier falls-Blöcken]*
