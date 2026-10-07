# System Architecture

```
Trade documents ───────┐
Declarations ──────────┼──> Evidence normalization ──> Cross-source consistency
Future sensor inputs ──┘                                      │
                                                             ↓
                                                   Provenance + uncertainty
                                                             │
                                        ┌────────────────────┼──────────────────┐
                                        ↓                    ↓                  ↓
                                      ACT                 VERIFY             ESCALATE
```

The architecture separates observations from decisions. A sensor interface is an integration boundary until a real sensing system exists and is evaluated.