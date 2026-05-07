<!-- README_2 — Field journal / lab notebook -->

```
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│              L A B   N O T E B O O K                         │
│                                                              │
│    KAKCALU13   ·   vol. VI   ·   started 2020                │
│    page 412 of an open-ended investigation                   │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

`subject:` building useful things from cheap parts and stubborn ideas
`location:` Mizoram → wherever the M2 is plugged in
`status:` ongoing

---

### 📓 recent entries

```
══ 2026-05-07 ══════════════════════════════════════════════════
   trial #47 · CITADEL ON APPLE SILICON
   ─────────────────────────────────────
   hypothesis : Metal renderer can replace OGL on Citadel
   apparatus  : mac-gz-rendering · ogre-next fork · M2
   result     : ✓ frames render, lighting still off
   next       : patch ogre-next, retest
   ref        : Kakcalu13/mac-gazebodistro

══ 2026-05-05 ══════════════════════════════════════════════════
   tawng — speak/listen prototype
   ─────────────────────────────────────
   first end-to-end Kotlin build. mic → STT → reply.
   latency 1.2s on-device. acceptable for v0.
   note: my daughter said her name into it. it heard it.

══ 2026-05-04 ══════════════════════════════════════════════════
   mujoco_world — fresh sim env started
   want this for the kids' games eventually.
   ~ swap pybullet later? open question.

══ 2026-05-02 ══════════════════════════════════════════════════
   duhthusam — ECS architecture decision
   ─────────────────────────────────────
   archetypes vs sparse sets.
   going archetypes. SoA wins on cache.
   first renderable triangle expected ~next month.
   (notebook ref: p.408, p.401)

══ 2026-04-21 ══════════════════════════════════════════════════
   feagi_game — picked up 3rd star ⭐
   somebody outside the project is playing with it.
   first time that's happened.

══ 2026-02-05 ══════════════════════════════════════════════════
   MIZO STT BREAKTHROUGH
   ─────────────────────────────────────
   Whisper fine-tune
       baseline WER : 0.34
       after 4 hrs  : 0.18
   training set includes my own family's recordings.
   it's learning my children's voices.
```

---

### 🗂️ active investigations

| # | line of inquiry | repos in evidence |
|---|---|---|
| I | reviving Ignition Citadel on M-series Macs | [`mac-gazebodistro`](https://github.com/Kakcalu13/mac-gazebodistro) · [`homebrew-legacy`](https://github.com/Kakcalu13/homebrew-legacy) · [`mac-citadel-gazebo`](https://github.com/Kakcalu13/mac-citadel-gazebo) · [`citadel-bridge`](https://github.com/Kakcalu13/citadel-bridge) · `mac-gz-*` (×7) |
| II | preserving Mizo through ML and play | [`mizo_ai_speech_to_text`](https://github.com/Kakcalu13/mizo_ai_speech_to_text) · `tawng` 🔒 · [`Mizo-godot-game`](https://github.com/Kakcalu13/Mizo-godot-game) · [`Inkhelhna-ho-te`](https://github.com/Kakcalu13/Inkhelhna-ho-te) |
| III | neuromorphic control of physical & virtual bodies | [feagi-connector](https://github.com/feagi/feagi-connector) (1,355 commits) · [`feagi-viser`](https://github.com/Kakcalu13/feagi-viser) · [`blender-connector`](https://github.com/Kakcalu13/blender-connector) · [`feagi_game`](https://github.com/Kakcalu13/feagi_game) |
| IV | a game engine built from first principles | `duhthusam` 🔒 (C++) · [`Inkhelhna-ho-te`](https://github.com/Kakcalu13/Inkhelhna-ho-te) (target title) |

---

### 🧪 instruments on the bench

```
languages   ▸  Python · C++ · GDScript · Bash · Kotlin · Ruby
                 └─ learning: Rust · Zig · Pony · Swift
build       ▸  CMake · Docker · GitHub Actions
sim         ▸  Gazebo · MuJoCo · Webots · Carla
sensors     ▸  IMU · LiDAR · cam · mic · pressure · LED · EEG · IR
boards      ▸  Raspberry Pi · Arduino · Micro:bit · ESP32
cloud       ▸  GCloud · AWS · Azure · Kubernetes · Terraform
```

---

### 📎 attached evidence

![1.5M lines on feagi-connector](_static/1m_proof.png)

```
─── end of page 412 ─── continued page 413 ───
```
