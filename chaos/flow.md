# Version B: The Chaos Killer ⚡ — User Flow

```mermaid
flowchart TD
    subgraph S1["⚡ Screen 1: Launch"]
        A1[/"Ready to fix your day?"/]
        A1a["Dark gradient + electric blue glow"]
        A1b["Geometric AI icon pulsing"]
        A1 --> A1a --> A1b
    end

    subgraph S2["🚨 Screen 2: Damage Report"]
        B1["🔴 347 unread emails"]
        B2["⚠️ 3 calendar conflicts"]
        B3["Counter animates 0 → 347"]
        B4(["FIX THIS CHAOS →"])
        B1 & B2 --> B3 --> B4
    end

    subgraph S3["🤖 Screen 3: AI Working"]
        C1["💬 Reading 347 emails..."]
        C2["💬 Sorting by urgency..."]
        C3["💬 Detecting conflicts..."]
        C4["💬 Finding 8 must-reads..."]
        C5["Counter: 347 → → → 8"]
        C1 --> C2 --> C3 --> C4
        C5
    end

    subgraph S4["✅ Screen 4: Results"]
        D1["🟢 3 conflicts → RESOLVED ✓"]
        D2["🔵 347 emails → 8 need you"]
        D3(["See your 8 emails →"])
        D1 & D2 --> D3
    end

    subgraph S5["💀 Screen 5: Kill Shot"]
        E1["📧 8 email cards with AI summaries"]
        E2["💊 Response pills glowing"]
        E3["Tap pill → ✈️ paper airplane"]
        E4["Counter: 8 → 7"]
        E5["'347 → 0. No thinking required.'"]
        E6(["Start crushing it — Free →"])
        E1 --> E2 --> E3 --> E4 --> E5 --> E6
    end

    S1 -->|"tap anywhere"| S2
    S2 -->|"tap FIX THIS"| S3
    S3 -->|"auto after bubbles"| S4
    S4 -->|"tap"| S5
    S5 -->|"CTA"| SIGNUP["🎉 Free Tier Signup"]

    style S1 fill:#1A1A2E,stroke:#00D4FF,color:#E0E0E0
    style S2 fill:#16213E,stroke:#FF4444,color:#E0E0E0
    style S3 fill:#0F3460,stroke:#00D4FF,color:#E0E0E0
    style S4 fill:#1A3A1A,stroke:#00FF88,color:#E0E0E0
    style S5 fill:#1A1A2E,stroke:#00D4FF,color:#E0E0E0
    style SIGNUP fill:#004D40,stroke:#00FF88,color:#E0E0E0
```

## Dopamine Arc
```mermaid
graph LR
    A["😤 Frustrated"] -->|"Screen 1"| B["💪 Ready to fight"]
    B -->|"Screen 2"| C["😳 Seeing the damage"]
    C -->|"Screen 3"| D["😈 Watching AI destroy chaos"]
    D -->|"Screen 4"| E["🎯 347 → 8. Satisfaction."]
    E -->|"Screen 5"| F["🤯 One tap sends. 8 → 7 → 0"]
    F --> G["💳 Shut up and take my money"]

    style A fill:#FFCDD2,stroke:#E53935
    style B fill:#FFE0B2,stroke:#FB8C00
    style C fill:#FFF9C4,stroke:#FDD835
    style D fill:#E1BEE7,stroke:#8E24AA
    style E fill:#C8E6C9,stroke:#43A047
    style F fill:#BBDEFB,stroke:#1E88E5
    style G fill:#A5D6A7,stroke:#2E7D32
```

## Design Tokens
| Element | Value |
|---------|-------|
| Background | `#1A1A2E` (near black) |
| Primary accent | `#00D4FF` (electric blue) |
| Success | `#00FF88` (electric green) |
| Danger | `#FF4444` (alert red) |
| Text | `#E0E0E0` (light grey) |
| Font | Inter / SF Pro (system, bold weights) |
| Animation | Snappy, satisfying pops, numbers counting down |
| Micro-copy tone | Direct, confident, zero BS |
