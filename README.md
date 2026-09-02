# Hi, I'm Ankur 👋

<img src="https://komarev.com/ghpvc/?username=sinhaankur&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />

**Principal UX Designer at Oracle · Human–AI Interaction · Toronto**

I'm a designer who ships code. 12+ years designing enterprise products across banking, supply chain, and cloud infrastructure — and I don't stop at Figma: I research the problem, design the interaction, and prototype it in real code, then hand engineering a contract they can build against. At Oracle I own the design end-to-end for cloud database operations in OCI, turning dangerous, expert-only tasks (encryption, key rotation, disaster-recovery failover) into safe, guided flows a non-expert can run.

The open-source work here is where that thinking gets to be fully public. Most of these repos are **exploration and ideas** — a working sketchbook for the human–AI seam, motion, performance, and on-device AI. A few (like [**Unhosted**](https://github.com/unhosted-ai)) are serious builds. The day job at Oracle is the anchor; everything else is how I keep sharp.

## 🎨 How I work as a designer

- **Research → design → code prototype → handoff.** I talk to real users (DBAs, operators), map the flows, and prove the interaction in working code before engineering commits to building it.
- **Reversibility, not "safety," is my policy axis.** How I decide when an interface must pause for a human: the more irreversible the step, the more the UI slows you down and confirms.
- **Performance is a UX concern.** A design isn't done if it janks. Example: for the [Universe Engine](https://www.sinhaankur.com) on my site, I render body/constellation labels as in-scene WebGL sprites (so they occlude at true depth instead of floating over the 3D scene), and measure/wrap their text **reflow-free** with [`@chenglou/pretext`](https://github.com/chenglou/pretext) — the canvas font engine does the layout, so building a label never forces a browser reflow, and multilingual names (CJK / Arabic / emoji) still wrap correctly.
- **Calibrated language over raw numbers.** In my AI prototypes, confidence reads as *Likely / Unsure / Low* (exact % on hover) — because a percentage isn't a decision, a posture is.

## 🚀 Unhosted — AI that lives where you do

Frontier-class AI inference on hardware you own. Unhosted pools the computers you already have — and optionally your friends', and optionally a public swarm of strangers' GPUs — into a single inference cluster. One endpoint. Mac, Linux, Windows. CUDA, Metal, ROCm.

**Three trust modes. You decide the radius:**

```
       ╭───────────────────────────────╮
       │   public · pay (USDC)         │   strangers' GPUs, opt-in
       │   ╭───────────────────────╮   │
       │   │  trusted · free       │   │   friends, family, team
       │   │   ╭───────────────╮   │   │
       │   │   │ local · free  │   │   │   devices you own
       │   │   ╰───────────────╯   │   │
       │   ╰───────────────────────╯   │
       ╰───────────────────────────────╯
```

The first two are free forever. The third is the safety net. You can use Unhosted for the rest of your life and never spend a dollar.

**Status:** pre-alpha, built in public. CLI at v0.0.34.

| Repo | What it is | Lang |
|---|---|---|
| [unhosted-core](https://github.com/unhosted-ai/unhosted-core) | The daemon — LAN cluster, mDNS discovery, model management, single-endpoint API. | Rust |
| [unhosted-payments](https://github.com/unhosted-ai/unhosted-payments) | Settlement layer for public mode — policy-driven, multi-rail, country-aware. | Rust |
| [unhosted-plugins](https://github.com/unhosted-ai/unhosted-plugins) | Extensions that talk to the daemon. First: MCP server. | TS |
| [homebrew-unhosted](https://github.com/unhosted-ai/homebrew-unhosted) | Homebrew tap. Today: RPC-enabled llama.cpp for VRAM-pooling. | Ruby |

## 💼 Day job — the anchor

Principal UX Designer at **Oracle**, OCI Database Tools (DBaaS team) — I own the design end-to-end for cloud database operations: encryption (TDE + OCI Vault/KMS), pluggable-database lifecycle, and Cross-Region Data Guard failover. Turning dangerous, expert-only tasks into safe, guided flows a non-expert can run.
*Feature specifics are under NDA — the open-source work here is my best public demonstration of how I think about design.*

## 🧪 Exploration & ideas

A sketchbook, not a product shelf. These are how I pressure-test the ideas above in real code — some polished, some deliberately rough. Grouped by what they're exploring:

**Human–AI seam & on-device AI**
- [**cognitive-twin-agent**](https://github.com/sinhaankur/cognitive-twin-agent) — a local-first personal-AI runtime; the seam between a human and an agent, on hardware you own
- [**EMPATHEIA**](https://github.com/sinhaankur/ideal-giggle) — camera-based empathetic AI companion, offline-first hybrid fallback
- [**Probabilistic-UI**](https://github.com/sinhaankur/Probabilistic-UI) — a design vocabulary for AI surfaces that are honest about uncertainty

**Engines & real-world data** (the visual, performance-first lane)
- [**portfolio-2026**](https://github.com/sinhaankur/portfolio-2026) — the Universe / Satellite Engine: real orbits, live space data, WebGL, [sinhaankur.com](https://www.sinhaankur.com)
- [**Firmament**](https://github.com/sinhaankur/Firmament) — point your iPhone at the real sky and understand it (iOS, Apple Intelligence)
- [**MultiVerse**](https://github.com/sinhaankur/MultiVerse) — physics-grounded Three.js visualization of cosmological models
- [**aero-engine-3d**](https://github.com/sinhaankur/aero-engine-3d) — interactive 3D encyclopedia of Airbus families

**Apps & tools**
- [**Kelo**](https://github.com/sinhaankur/Kelo) — private, on-device health + wealth companion (Swift, HealthKit)
- [**Draften**](https://github.com/sinhaankur/Draften) — a unified design + diagramming workspace that opens your files (Tauri)
- [**Structura**](https://github.com/sinhaankur/Structura) — scan real structures with your phone's depth sensor (iOS/Android)
- [**WatchTower**](https://github.com/sinhaankur/WatchTower) — turn a computer you own into your personal cloud (self-hosted deploys)
- [**GovLens**](https://github.com/sinhaankur/GovLens) — a universal reader overlaid on government portals across 25+ national TLDs

**Explainers**
- [**Petrodollar-Paradox**](https://github.com/sinhaankur/Petrodollar-Paradox) · [**bharat**](https://github.com/sinhaankur/bharat) · [**brainrot**](https://github.com/sinhaankur/brainrot) — interactive web explainers on economics, data, and media bias

> Full map of the live projects: [sinhaankur.com/lab](https://www.sinhaankur.com/lab)

## 🌐 Find me

- 📍 Toronto, Canada
- 🌐 [sinhaankur.com](https://www.sinhaankur.com)
- 💼 [LinkedIn](https://linkedin.com/in/sinhaankur27)
- 📬 sinhaankur827@gmail.com

