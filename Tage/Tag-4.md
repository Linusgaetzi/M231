# Tag 4

[← Tag 3](Tag-3.md) · [Übersicht](../README.md) · [Tag 5 →](Tag-5.md)

---

## Themen des Tages

Heute habe ich mich mit folgenden Themen beschäftigt:

- Urheberrecht und Lizenzmodelle
<details>
   <summary>Lizenzmodell</summary>
   
   ```mermaid

flowchart TD     
   A[Lizenzen] --> B[Proprietär]     
   A --> C[Open Source]     
   B --> B1[Code geheim]     
   B --> B2[braucht Lizenz]     
   B --> B3[z. B. Windows]     
   C --> C1[Code offen]     
   C --> C2[meist gratis]     
   C --> C3[z. B. Linux]     
   C --> D[GPL: Änderung = teilen]     
   C --> D1[MIT: fast keine Regeln]
   ```

</details>

- Open-Source-Lizenzen
- Creative-Commons-Lizenzen
- Cookies und Tracking
- Browser-Fingerprinting
- Dark Patterns
- KI als Hilfsmittel zur Analyse von Webseiten

---

# 1. Lizenzmodelle und Urheberrecht

## Was habe ich gemacht?

Zu Beginn habe ich mich mit dem Thema Urheberrecht beschäftigt. Ich habe gelernt, dass Werke wie Texte, Bilder, Musik oder Code automatisch urheberrechtlich geschützt sind, sobald sie erstellt werden.

Anschliessend habe ich verschiedene Lizenzmodelle verglichen. Dabei habe ich mich besonders mit proprietärer Software und Open-Source-Software auseinandergesetzt.

Ich habe ausserdem verschiedene Open-Source-Lizenzen wie MIT, Apache 2.0, GPL, LGPL und AGPL kennengelernt und deren Unterschiede verglichen.

Zum Schluss habe ich mich mit Creative-Commons-Lizenzen beschäftigt und anhand von verschiedenen Szenarien überlegt, welche Lizenz jeweils passend wäre.

## Was habe ich gelernt?

Ich habe gelernt, dass nicht jede Open-Source-Lizenz die gleichen Regeln hat.

Besonders wichtig fand ich:

- Bei proprietärer Software ist der Quellcode normalerweise nicht öffentlich.
- Bei Open-Source-Software ist der Quellcode zugänglich.
- Die MIT-Lizenz erlaubt sehr viel Freiheit bei der Nutzung.
- Die GPL-Lizenz verpflichtet dazu, veränderten Code bei der Weitergabe ebenfalls unter GPL zu veröffentlichen.
- Apache 2.0 bietet zusätzlich Schutz im Bereich von Patenten.
- Creative Commons wird vor allem für Inhalte wie Bilder, Texte oder Videos verwendet.

Ich habe auch gelernt, was die Abkürzungen bei Creative Commons bedeuten:

| Kürzel | Bedeutung |
|---|---|
| BY | Namensnennung |
| SA | Weitergabe unter gleichen Bedingungen |
| NC | Keine kommerzielle Nutzung |
| ND | Keine Bearbeitung erlaubt |
| CC0 | Rechte werden weitgehend freigegeben |


---

# 2. Privacy-Threats: Cookies und Tracking

## Was habe ich gemacht?

Im nächsten Block habe ich mich mit Datenschutz und verschiedenen Tracking-Methoden beschäftigt.

Ich habe gelernt, wie Cookies funktionieren und welche verschiedenen Arten von Cookies es gibt. Danach habe ich untersucht, wie Unternehmen Nutzer über verschiedene Webseiten hinweg verfolgen können.

Besonders interessant war das Thema Browser-Fingerprinting.

## Was habe ich gelernt?

Cookies sind kleine Dateien, die Webseiten im Browser speichern können.

Es gibt verschiedene Arten:

- Session-Cookies speichern Informationen während einer Sitzung.
- Persistente Cookies speichern Informationen über einen längeren Zeitraum.
- Third-Party-Cookies können Nutzer über verschiedene Webseiten hinweg verfolgen.
- Tracking-Pixel können beispielsweise erkennen, ob eine E-Mail geöffnet wurde.

Beim Browser-Fingerprinting werden verschiedene Informationen über meinen Browser gesammelt.

Dazu gehören zum Beispiel:

- Bildschirmauflösung
- Sprache
- Zeitzone
- Browser und Betriebssystem
- installierte Schriftarten
- WebGL-Informationen
- Canvas-Daten

Ein einzelnes Merkmal ist meistens nicht eindeutig. Die Kombination vieler Merkmale kann jedoch dazu führen, dass ein Browser sehr genau wiedererkannt werden kann.

---

# 3. Eigenen Browser-Fingerprint untersuchen

## Was habe ich gemacht?

Als praktische Aufgabe sollte ich meinen eigenen Browser-Fingerprint untersuchen.

Dabei ging es darum herauszufinden:

1. Ob mein Browser eindeutig identifizierbar ist.
2. Welche Eigenschaften besonders stark zur Identifikation beitragen.
3. Was ich verändern könnte, um meinen Fingerprint weniger eindeutig zu machen.

## Was habe ich gelernt?

Durch diese Aufgabe habe ich verstanden, dass die Einstellungen meines Browsers einen direkten Einfluss auf meine Privatsphäre haben können.

Mögliche Schutzmassnahmen sind:

- Third-Party-Cookies blockieren
- Datenschutzfreundliche Browser verwenden
- Tracking-Blocker einsetzen
- Cookies regelmässig löschen
- Fingerprinting-Schutz aktivieren

---

# 4. Dark Patterns

## Was habe ich gemacht?

Danach habe ich mich mit sogenannten Dark Patterns beschäftigt.

Ich habe verschiedene Beispiele untersucht und gelernt, wie Webseiten und Apps Nutzer bewusst beeinflussen können.

Dabei ging es nicht um technische Sicherheitslücken, sondern um Manipulation durch Design und Benutzerführung.

## Was habe ich gelernt?

Dark Patterns sind Gestaltungsmethoden, die Nutzer zu Entscheidungen bringen sollen, die sie möglicherweise eigentlich nicht treffen wollten.

Ich habe verschiedene Arten kennengelernt:

### Roach Motel

Es ist einfach, sich für einen Dienst anzumelden, aber sehr schwierig, sich wieder abzumelden.

### Confirmshaming

Der Nutzer wird durch eine beschämende Formulierung unter Druck gesetzt.

Beispiel:

> „Nein danke, ich möchte keine Vorteile erhalten.“

### Hidden Costs

Zusätzliche Kosten werden erst sehr spät im Kaufprozess angezeigt.

### Sneak into Basket

Ein zusätzliches Produkt oder eine Versicherung wird automatisch in den Warenkorb gelegt.

### Privacy Zuckering

Datenschutzeinstellungen werden absichtlich kompliziert oder schwer auffindbar gestaltet.

### Disguised Ads

Werbung wird so gestaltet, dass sie wie ein normales Suchergebnis oder Inhalt aussieht.

### Forced Continuity

Ein kostenloses Angebot wird automatisch kostenpflichtig, wenn der Nutzer nicht rechtzeitig kündigt.

---

# 5. KI zur Analyse von Dark Patterns

## Was habe ich gemacht?

Im letzten Teil habe ich gelernt, wie KI als Hilfsmittel bei der Analyse von Dark Patterns eingesetzt werden kann.

Die Aufgabe bestand darin, Webseiten zu untersuchen und eine KI nach einer möglichen Einschätzung zu fragen.

Danach sollte die Antwort der KI aber kritisch überprüft werden.

## Was habe ich gelernt?

Ich habe gelernt, dass KI bei der Analyse helfen kann, aber nicht automatisch recht hat.

Eine KI kann:

- mögliche Dark Patterns erkennen
- Kategorien vorschlagen
- Texte und Benutzeroberflächen analysieren
- bei der Recherche helfen

Trotzdem muss ich die Ergebnisse selbst überprüfen.

Die KI kann zum Beispiel:

- ein falsches Pattern erkennen
- eine Situation überbewerten
- wichtige Informationen übersehen
- eine überzeugend klingende, aber falsche Erklärung geben

---

# Reflexion

Heute habe ich viel darüber gelernt, wie Technologie, Datenschutz und Benutzeroberflächen miteinander verbunden sind.

Besonders interessant fand ich, dass Nutzer nicht nur durch technische Methoden wie Cookies oder Fingerprinting überwacht werden können. Auch das Design von Webseiten kann Menschen bewusst beeinflussen.

Die wichtigsten Erkenntnisse des Tages sind für mich:

1. Ich muss auf Lizenzen achten, bevor ich fremde Inhalte oder Code verwende.
2. Mein Browser gibt mehr Informationen über mich preis, als ich zuerst gedacht habe.
3. Tracking funktioniert nicht nur über Cookies.
4. Webseiten können durch Dark Patterns gezielt manipulativ gestaltet sein.
5. KI kann bei Analysen helfen, muss aber immer kritisch überprüft werden.

---

# Bezug zu Handlungszielen

- **HZ 6.1 – Lizenzmodelle:** Urheberrecht, proprietäre und Open-Source-Lizenzen (MIT, Apache 2.0, GPL), Creative Commons
- **HZ 4.1 – Privacy-Threats und Dark Patterns:** Cookies, Tracking, Browser-Fingerprinting, Dark Patterns

---

[← Tag 3](Tag-3.md) · [Übersicht](../README.md) · [Tag 5 →](Tag-5.md)
