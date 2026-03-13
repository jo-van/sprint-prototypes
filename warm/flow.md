# Version A: The Warm Human 🌅 — User Flow

```mermaid
flowchart TD
    subgraph S1["☀️ Screen 1: Wake Up"]
        A1[/"Morning, Noor ☀️"/]
        A1a["Soft cream bg + gentle pulse"]
        A1b["No login, no buttons"]
        A1 --> A1a --> A1b
    end

    subgraph S2["💬 Screen 2: Chaos Acknowledged"]
        B1["347 unread emails"]
        B2["3 calendar conflicts"]
        B3["12 items need attention"]
        B4[/"Let me handle this?"/]
        B5(["Please do ✨"])
        B1 & B2 & B3 --> B4 --> B5
    end

    subgraph S3["✨ Screen 3: Working"]
        C1["Clearing the noise..."]
        C2["Finding what matters..."]
        C3["Almost there..."]
        C4["✉️ → ⭐ envelopes dissolve to stars"]
        C1 --> C2 --> C3
        C4
    end

    subgraph S4["🌿 Screen 4: Breathing Room"]
        D1["📧 4 emails need you"]
        D2["📅 Moved your 2pm to tomorrow"]
        D3["🛡️ Protected your lunch break"]
    end

    subgraph S5["🤯 Screen 5: Holy Shit"]
        E1["Same clean layout"]
        E2["⏳ 1.5 sec delay..."]
        E3["💬 'Also cancelled that call\nyou've been dreading.'"]
        E4(["Start your free morning briefings →"])
        E1 --> E2 --> E3 --> E4
    end

    S1 -->|"auto 2s or tap"| S2
    S2 -->|"tap button"| S3
    S3 -->|"auto 3s"| S4
    S4 -->|"tap"| S5
    S5 -->|"CTA"| SIGNUP["🎉 Free Tier Signup"]

    style S1 fill:#FFF8E7,stroke:#D4A574,color:#333
    style S2 fill:#FFF3E0,stroke:#E8A855,color:#333
    style S3 fill:#F5F0FF,stroke:#B39DDB,color:#333
    style S4 fill:#F1F8E9,stroke:#81C784,color:#333
    style S5 fill:#FFFDE7,stroke:#FFD54F,color:#333
    style SIGNUP fill:#C8E6C9,stroke:#4CAF50,color:#333
```

## Emotional Arc
```mermaid
graph LR
    A["😰 Overwhelmed"] -->|"Screen 1"| B["😌 Acknowledged"]
    B -->|"Screen 2"| C["🤞 Hopeful"]
    C -->|"Screen 3"| D["😊 Watching magic"]
    D -->|"Screen 4"| E["😮‍💨 Relief"]
    E -->|"Screen 5"| F["🤯 Holy shit"]
    F --> G["💳 Take my money"]

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
| Background | `#FFF8F0` (warm cream) |
| Accent | `#D4A574` (amber) |
| Text | `#2C1810` (warm dark) |
| Heading Font | Crimson Text (serif) |
| Body Font | Source Sans Pro |
| Animation | Breathe (slow pulse), never rushed |
| Micro-copy tone | Warm friend who happens to be organized |
