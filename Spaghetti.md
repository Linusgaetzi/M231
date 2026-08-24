## Spaghetti mit Tomatensosse
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
