# Hi, I'm Ankur 👋

<img src="https://komarev.com/ghpvc/?username=sinhaankur&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />

**Principal UX Designer at Oracle · Human–AI Interaction · Toronto**

I'm a designer who ships code. 12+ years designing enterprise products across banking, supply chain, and cloud infrastructure — and I don't stop at Figma: I research the problem, design the interaction, and prototype it in real code, then hand engineering a contract they can build against. At Oracle I own the design end-to-end for cloud database operations in OCI, turning dangerous, expert-only tasks (encryption, key rotation, disaster-recovery failover) into safe, guided flows a non-expert can run.

Evenings and weekends, I build [**Unhosted**](https://github.com/unhosted-ai) — where the design thinking gets to be fully public.

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

## 🧭 Earlier open-source research

Before Unhosted, a connected trilogy of agentic-UX code prototypes exploring how humans stay in the loop with AI agents:

- **[Helm](https://github.com/sinhaankur/Helm)** — Real-time oversight of LLM agents · approval gate, reversibility chip, diff view. [live demo](https://sinhaankur.github.io/Helm/)
- **[Sentinel](https://github.com/sinhaankur/Human-in-the-Loop)** — Embeddable inline AI oversight · ships as React lib, Chrome extension, VS Code participant, Docker. [live demo](https://sinhaankur.github.io/Human-in-the-Loop/)
- **[Recourse](https://github.com/sinhaankur/Recourse)** — Consumer AI as advocate against institutional loops · document-first, statute-anchored. [live demo](https://sinhaankur.github.io/Recourse/)
- **[Probabilistic-UI](https://github.com/sinhaankur/Probabilistic-UI)** — The shared design vocabulary that runs across all three.

## 🛠 Other things I've made

- **[GovLens](https://github.com/sinhaankur/GovLens)** — Chrome extension overlaying a universal reader on any government portal across 25+ national TLDs
- **[WatchTower](https://github.com/sinhaankur/WatchTower)** — Self-hosted deployment platform; ships across macOS / Windows / Linux / VS Code / PyPI
- **[EMPATHEIA](https://github.com/sinhaankur/ideal-giggle)** — Multi-modal AI companion with offline-first hybrid fallback

## 💼 Day job

Principal UX Designer at **Oracle**, OCI Database Tools (DBaaS team) — I own the design end-to-end for cloud database operations: encryption (TDE + OCI Vault/KMS), pluggable-database lifecycle, and Cross-Region Data Guard failover.
*Feature specifics are under NDA — the open-source work above is my best public demonstration of how I think about design.*

## 🌐 Find me

- 📍 Toronto, Canada
- 🌐 [sinhaankur.com](https://www.sinhaankur.com)
- 💼 [LinkedIn](https://linkedin.com/in/sinhaankur27)
- ✍️ [Medium](https://medium.com/@sinhaankur27)
- 📬 sinhaankur827@gmail.com

