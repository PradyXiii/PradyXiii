<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a1a0a,30:006400,60:8B0000,100:1a0000&height=200&section=header&text=&fontSize=0&animation=fadeIn" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&duration=4000&pause=1000&color=00C853&center=true&vCenter=true&width=620&height=60&lines=Solo+Leveling+Algo+Trader" />
</p>

I'm a solo trader who builds small, AI-augmented trading systems that keep a human out of the daily
loop. I favor quiet, durable edges over loud ones. Still learning, still building in the open.

### The Trading Desks

| | Desk | Market | What it does |
|---|---|---|---|
| 🔴 | **Options Trading Desk** | NIFTY & SENSEX · F&O | Rules-based, no forecasting |
| 🟢 | **Crypto Trading Desk** | BTC & ETH · options | An LLM brain manages trades under hard caps |

Both run live on real capital, fully automated.

### The Loop

```mermaid
graph LR
    A(["feed"]) --> B(["filter"])
    B --> C{"gate"}
    C -->|clean| E(["context"])
    E --> F[["decide"]]
    F --> G{signal?}
    G -->|weak| H(["pass"])
    G -->|strong| I{{"risk gate"}}
    I -->|OK| J(["execute"])
    I -->|breach| K(["kill-switch"])
    J --> M(["journal"])
    M --> A
    H --> A

    classDef base fill:#0a1a0a,stroke:#00C853,stroke-width:2px,color:#fff
    classDef brain fill:#4b0000,stroke:#DC143C,stroke-width:2px,color:#fff
    classDef gate fill:#006400,stroke:#fff,stroke-width:2px,color:#fff
    classDef alert fill:#8B0000,stroke:#fff,stroke-width:2px,color:#fff

    class A,B,E,J,M base
    class F brain
    class I gate
    class K alert
```

<p align="center"><sub>last update: 2026-07-02</sub></p>
