```mermaid


graph LR

    style CEO fill:#FFD700,stroke:#FFD700;
    style CTO fill:#87CEEB,stroke:#87CEEB;
    style CFO fill:#87CEEB,stroke:#87CEEB;
    style COO fill:#87CEEB,stroke:#87CEEB;
    style FE1 fill:#98FB98,stroke:#98FB98;
    style FE2 fill:#98FB98,stroke:#98FB98;
    style FE3 fill:#98FB98,stroke:#98FB98;
    style FE4 fill:#98FB98,stroke:#98FB98;




    CEO[CEO: Neil ] --> CTO[CTO: Dean ]
    CEO --> CFO[CFO: Gillian ]
    CEO --> COO[COO: Callum ]

    
    CTO --> Team1_Lead[Team1_Lead: Gavin ]
    Team1_Lead --> T1FE1[T1FE1: Dinesh ]
    Team1_Lead --> T1FE2[T1FE2: t.b.d ]
    Team1_Lead --> T1FE3[T1FE3: t.b.d ]

    CTO --> Team2_Lead[Team2_Lead: t.b.d ]
    Team2_Lead --> T2FE1[T2FE1: t.b.d ]
    Team2_Lead --> T2FE2[T2FE2: t.b.d ]
    Team2_Lead --> T2FE3[T2FE3: t.b.d ]
