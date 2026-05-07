<!--
  README_2 — Live mermaid constellation
-->

<div align="center">

# 🌌 kakcalu13's repo constellation

_maker · roboticist · dad — every node is a real repo, every edge a real dependency_

</div>

---

```mermaid
%%{init: {'theme':'base','themeVariables':{
  'primaryColor':'#0f172a','primaryTextColor':'#e2e8f0','primaryBorderColor':'#14b8a6',
  'lineColor':'#64748b','secondaryColor':'#1e293b','tertiaryColor':'#0f172a',
  'fontFamily':'JetBrains Mono, monospace'
}}}%%
flowchart TB
  classDef mizo    fill:#134e4a,stroke:#14b8a6,color:#ccfbf1
  classDef apple   fill:#7c2d12,stroke:#f97316,color:#ffedd5
  classDef feagi   fill:#312e81,stroke:#8b5cf6,color:#e0e7ff
  classDef kids    fill:#831843,stroke:#ec4899,color:#fce7f3
  classDef engine  fill:#1f2937,stroke:#fbbf24,color:#fef3c7

  ME(("🧑‍💻 kakcalu13"))

  subgraph MIZO ["🪶 preserve-mizo"]
    M1[mizo_ai_speech_to_text]:::mizo
    M2[tawng 🔒]:::mizo
    M3[Mizo-godot-game]:::mizo
    M4[Inkhelhna-ho-te]:::mizo
  end

  subgraph APPLE ["🍎 citadel-on-apple"]
    A1[mac-gazebodistro]:::apple
    A2[homebrew-legacy]:::apple
    A3[mac-citadel-gazebo]:::apple
    A4[citadel-bridge]:::apple
    A5[mac-gz-rendering]:::apple
    A6[mac-gz-transport]:::apple
    A7[mac-gz-msgs]:::apple
    A8[mac-gz-cmake]:::apple
    A9[citadel-gazebo-ogre-next]:::apple
  end

  subgraph FEAGI ["🧠 feagi-neuromorphic"]
    F1[feagi-connector ★]:::feagi
    F2[feagi-viser]:::feagi
    F3[blender-connector]:::feagi
    F4[feagi_game ⭐3]:::feagi
  end

  subgraph ENGINE ["🎮 from-scratch"]
    E1[duhthusam 🔒]:::engine
    E2[Inkhelhna-ho-te]:::engine
  end

  ME --> MIZO
  ME --> APPLE
  ME --> FEAGI
  ME --> ENGINE

  M1 --> M3
  M2 --> M3
  M3 --> KIDS[["👶 my kids learn Mizo"]]:::kids

  A2 --> A1
  A5 --> A1
  A6 --> A1
  A7 --> A1
  A8 --> A1
  A9 --> A3
  A1 --> A3
  A3 --> A4
  A4 --> PY{{"🐍 Python"}}

  F1 --> F2
  F1 --> F3
  F1 --> F4

  E1 --> E2

  click M1 "https://github.com/Kakcalu13/mizo_ai_speech_to_text"
  click M3 "https://github.com/Kakcalu13/Mizo-godot-game"
  click M4 "https://github.com/Kakcalu13/Inkhelhna-ho-te"
  click A1 "https://github.com/Kakcalu13/mac-gazebodistro"
  click A2 "https://github.com/Kakcalu13/homebrew-legacy"
  click A3 "https://github.com/Kakcalu13/mac-citadel-gazebo"
  click A4 "https://github.com/Kakcalu13/citadel-bridge"
  click F4 "https://github.com/Kakcalu13/feagi_game"
```

---

### 📊 by the numbers

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#14b8a6','primaryTextColor':'#fff','lineColor':'#64748b','fontFamily':'JetBrains Mono'}}}%%
pie showData
  "citadel-on-apple" : 12
  "feagi-neuromorphic" : 5
  "preserve-mizo" : 4
  "games-for-my-kids" : 3
  "from-scratch" : 2
  "other" : 30
```

---

### 🛠️ skill graph

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#1e293b','primaryTextColor':'#e2e8f0','primaryBorderColor':'#14b8a6','lineColor':'#64748b','fontFamily':'JetBrains Mono'}}}%%
flowchart LR
  PI[Raspberry Pi ✓] --> ROS[ROS 2 ✓]
  ARD[Arduino ✓] --> ESP[ESP32 ✓]
  ROS --> GAZ[Gazebo ✓]
  GAZ --> CITADEL[Citadel-on-Mac 🔥]
  GAZ --> FEAGI_G[feagi_game ✓]
  PY[Python ✓] --> ML[ML / STT 🔥]
  PY --> FEAGI[FEAGI 1.5M LOC]
  CPP[C++ ✓] --> CMAKE[CMake 🔥]
  CMAKE --> ENGINE[duhthusam 🔒🔥]
  GD[GDScript ✓] --> GODOT[Godot ✓]
  GODOT --> KIDS[Mizo-godot-game ✓]
```

<div align="center">

<a href="https://github.com/Kakcalu13"><img src="https://github-readme-stats.vercel.app/api?username=Kakcalu13&show_icons=true&include_all_commits=true&hide_border=true&theme=tokyonight" alt="stats"/></a>

</div>
