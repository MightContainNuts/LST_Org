```mermaid


graph LR
    CEO[CEO: Neil] --> CTO[CTO: Dean]
    CEO --> CFO[CFO: Gillian]
    CEO --> COO[COO: Callum]

    CTO --> FE1[FE2: Gavin]
    CTO --> FE2[FE2: Dinesh]

    CTO --> VP2[VP Product]
    CFO --> VP3[VP Finance]
    VP1 --> EngMgr1[Engineering Manager]
    VP1 --> EngMgr2[Engineering Manager]
    VP2 --> ProdMgr1[Product Manager]
    VP2 --> ProdMgr2[Product Manager]
    VP3 --> AcctMgr1[Accounting Manager]
    VP3 --> AcctMgr2[Accounting Manager]
    EngMgr1 --> Dev1[Developer]
    EngMgr1 --> Dev2[Developer]
    ProdMgr1 --> PM1[Project Manager]
    AcctMgr1 --> Acct1[Accountant]
