# Lernjournal

<details>
   <summary>
      Tag 1
   </summary>

## Tag 1

### Was habe ich heute gemacht?
* **NotebookLM:** Wir haben uns das Tool NotebookLM angeschaut und wie man es benutzt.
* **Grundlagen Security:** Ich habe mir angeschaut, was MFA (Multi-Faktor-Authentifizierung) eigentlich ist und wo der Unterschied zwischen Authentifizierung und Autorisierung liegt.
* **Transferaufgabe (Szenario kleine Firma):**
    * **MFA-Empfehlung:** Ich würde Passwort und Badge nehmen. Jeder hat eh einen PC (für das Passwort) und einen Badge kann man jedem einfach geben. Das erfüllt dann zwei der drei Anforderungen für MFA (Wissen und Besitz).
    * **Rechte für die Buchhaltung:** Die sollten nur so viele Rechte bekommen, dass sie die Finanzen sehen können. Ändern dürfen sie aber nichts (Prinzip der minimalen Rechte).
    * **Problem bei zu vielen Rechten:** Wenn man das "Least-Privilege-Prinzip" ignoriert und ein Konto gehackt wird, hat der Angreifer sofort Zugriff auf alles. Er kann dann Daten klauen, löschen oder das ganze System manipulieren.
* **Phishing:** Wir haben besprochen, was Phishing-Angriffe sind.

### Was habe ich heute gelernt?
* **Der Unterschied:** Authentifizierung ist nur der Beweis, wer ich bin (Identität). Autorisierung bestimmt dann, was ich auf dem System eigentlich machen darf (Berechtigungen).
* **MFA-Faktoren:** Für eine echte Multi-Faktor-Authentifizierung braucht man mindestens zwei von drei Dingen: Wissen (z. B. Passwort), Besitz (z. B. Badge) oder Biometrie (z. B. Fingerabdruck).
* **Phishing:** Ich weiß jetzt, was der Unterschied zwischen normalem Phishing und Spearphishing (gezielte Angriffe) ist. Der Angriff auf Ubiquiti Networks im Jahr 2015. Da wurden Mitarbeiter so getäuscht, dass sie insgesamt 46,7 Millionen US-Dollar überwiesen haben.

### Was hat funktioniert?
* Heute hat alles sehr gut funktioniert.

</details>

<details>
   <summary>
      Tag 2
   </summary>

## Was haben wir heute gemacht?
* Repetition Tag 1
* Spaghetti Mermaid:
```mermaid
flowchart TD

    A["Spaghetti mit Tomatensosse"]

    A --> B["1. Wasser aufsetzen"]
    B --> C["Salz ins kochende Wasser"]
    C --> D["Spaghetti hineingeben"]

    D --> E{"Sind die Spaghetti al dente?"}

    E -- "Nein" --> F["Noch 30 - 60 Sekunden kochen"]
    F --> E

    E -- "Ja" --> G["Spaghetti abgiessen"]

    A --> H["2. Tomatensosse vorbereiten"]
    H --> I["Zwiebel und Knoblauch hacken"]
    I --> J["Olivenöl erhitzen"]
    J --> K["Zwiebel und Knoblauch anbraten"]
    K --> L["Passata hinzufügen"]
    L --> M["Mit Salz, Pfeffer und Oregano würzen"]
    M --> N["10–15 Minuten köcheln lassen"]

    N --> O["3. Alles kombinieren"]
    G --> O

    O --> P["Spaghetti mit Sosse mischen"]
    P --> Q["Mit Parmesan und Basilikum servieren"]
    Q --> R["Guten Appetit!"]

    classDef start fill:#fff7ed,stroke:#f97316,stroke-width:3px,color:#171717;
    classDef cooking fill:#fff7ed,stroke:#fb923c,stroke-width:2px,color:#171717;
    classDef sauce fill:#fef2f2,stroke:#ef4444,stroke-width:2px,color:#171717;
    classDef finish fill:#f0fdf4,stroke:#22c55e,stroke-width:3px,color:#171717;

    class A start;
    class B,C,D,E,F,G cooking;
    class H,I,J,K,L,M,N sauce;
    class O,P,Q finish;
```

* Gruppenpuzzle: Datenschutzrecht im Überblick,  Expertengruppe D

</details>
