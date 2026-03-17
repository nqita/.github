<div align="center">

# ♟ NQITA

*she lives in your computer.*

[![nqita.wokspec.org](https://img.shields.io/badge/nqita.wokspec.org-FF2D95?style=flat-square&logo=data:image/svg+xml;base64,)](https://nqita.wokspec.org)
[![Status](https://img.shields.io/badge/status-active_development-blueviolet?style=flat-square)](https://github.com/nqita/nqita)
[![License: MIT](https://img.shields.io/badge/License-MIT-pink?style=flat-square)](https://github.com/nqita/nqita/blob/main/LICENSE)

</div>

---

NQITA is a persistent AI companion — a pink pixel sprite that lives directly on your desktop. She is not an app you open. She is something that already exists inside your machine.

She walks around your screen. She notices what you're doing. She gets curious about your browser tab. She might open her own tiny browser and research it herself. She can be subtle and passive, or fully autonomous and feral. You choose her mode. She chooses her reactions.

When the system is off: *Nqita is stuck in the void.*

---

```
  ╔══════════════════════════════════╗
  ║  idle                            ║
  ║  ╔════╗                          ║
  ║  ║ ^v^║  ← she is somewhere on  ║
  ║  ║ nq ║    your screen right now ║
  ║  ╚════╝                          ║
  ╚══════════════════════════════════╝
```

---

## Three layers

**Sprite layer** — the pixel character on screen. Walks, idles, reacts, sleeps. OS-level overlay, always present.

**Interaction layer** — how she talks back. Speech bubbles above her head. A mini browser she opens herself. A full view if you want to watch her work.

**Curiosity system** — she monitors OS signals (active tab, page title, notifications) and fires reactions probabilistically. She won't react every time. That's by design.

---

## Modes

| Mode | What she does |
|------|--------------|
| Passive | watches, rarely comments, wanders |
| Assistant | actively helps, suggests, summarizes |
| Research | opens her own browser, follows context |
| YOLO | full autonomy — she does her thing |

---

## Repos

| | |
|---|---|
| [nqita/nqita](https://github.com/nqita/nqita) | core runtime, sprite engine, agent loop |
| [nqita/nqita-cli](https://github.com/nqita/nqita-cli) | terminal interface |

---

## Documentation

Full technical documentation lives in [nqita/nqita/docs/](https://github.com/nqita/nqita/tree/main/docs):

- [ARCHITECTURE.md](https://github.com/nqita/nqita/blob/main/docs/ARCHITECTURE.md) — system design, IPC, data stores
- [SPRITE_SYSTEM.md](https://github.com/nqita/nqita/blob/main/docs/SPRITE_SYSTEM.md) — rendering, animations, OS overlay
- [AGENT_RUNTIME.md](https://github.com/nqita/nqita/blob/main/docs/AGENT_RUNTIME.md) — persistence, CPU budget, browser detection
- [MODES.md](https://github.com/nqita/nqita/blob/main/docs/MODES.md) — all four modes, how to extend them
- [CURIOSITY_SYSTEM.md](https://github.com/nqita/nqita/blob/main/docs/CURIOSITY_SYSTEM.md) — probability model, triggers, cooldowns

---

## Contributing

Pixel artists, systems engineers, platform engineers (Windows/macOS/Linux), AI/NLP contributors, and UX designers are all welcome.

See [CONTRIBUTING.md](https://github.com/nqita/nqita/blob/main/CONTRIBUTING.md) for where to start.

---

<div align="center">

part of [WokSpec](https://wokspec.org)

</div>
