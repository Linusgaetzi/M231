## Spaghetti mit Tomatensosse
```mermaid
flowchart TD

    A["Spaghetti mit Tomatensoße"]

    A --> B["1. Wasser aufsetzen"]
    B --> C["Salz ins kochende Wasser"]
    C --> D["Spaghetti hineingeben"]

    D --> E{"Sind die Nudeln al dente?"}

    E -- "Nein" --> F["Noch 1–2 Minuten kochen"]
    F --> E

    E -- "Ja" --> G["Spaghetti abgießen"]

    A --> H["2. Tomatensoße vorbereiten"]
    H --> I["Zwiebel und Knoblauch hacken"]
    I --> J["Olivenöl erhitzen"]
    J --> K["Zwiebel und Knoblauch anbraten"]
    K --> L["Passierte Tomaten hinzufügen"]
    L --> M["Mit Salz, Pfeffer und Oregano würzen"]
    M --> N["10–15 Minuten köcheln lassen"]

    N --> O["3. Alles kombinieren"]
    G --> O

    O --> P["Spaghetti mit Soße vermengen"]
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
