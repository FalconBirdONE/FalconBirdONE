<img src="https://capsule-render.vercel.app/api?type=transparent&height=140&section=header&text=Shardul%20Shinde&fontSize=52&fontColor=8FA3B8&fontAlignY=42&desc=%E9%8D%9B%E9%80%A0%20%C2%B7%20kitan%20%C2%B7%20forging&descSize=16&descAlignY=68&descColor=5C6B7A&animation=fadeIn" width="100%" />

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=3400&pause=900&color=8FA3B8&center=true&vCenter=true&width=560&lines=native+modules%2C+payment+rails%2C+on-device+inference;I+read+the+spec.+then+I+read+the+source.;%E4%B8%80%E6%9C%9F%E4%B8%80%E4%BC%9A+%E2%80%94+every+build+is+its+own+moment" alt="typing" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/shardul"><img src="https://img.shields.io/badge/LinkedIn-2F3A45?style=flat-square&logo=linkedin&logoColor=8FA3B8" /></a>
  <a href="https://shardulshinde.com"><img src="https://img.shields.io/badge/Website-2F3A45?style=flat-square&logo=safari&logoColor=8FA3B8" /></a>
  <a href="mailto:shardulshinde2005@gmail.com"><img src="https://img.shields.io/badge/Mail-2F3A45?style=flat-square&logo=maildotru&logoColor=8FA3B8" /></a>
</p>

<div align="center">
  <sub><code>─────────────────────  序  ─────────────────────</code></sub>
</div>

I work where the abstraction leaks — the seam between a JS bundle and a native `.so`, between a payment spec and the terminal actually holding the card. Most of what I build is infrastructure someone else's product sits on top of, which means it either works silently or it fails at 2am.

I don't collect frameworks. I pick a layer, read down to where the documentation stops, and stay there until the thing is deployed and boring.

<div align="center">
  <sub><code>─────────────────────  技  ─────────────────────</code></sub>
</div>

### mobile, down to the metal

React Native / Expo on Android, but the interesting half is below it — writing native Java modules and bridging them cleanly into TypeScript. Biometric capture SDKs talking to dedicated hardware, NFC and host card emulation, TFLite inference running on-device with no network round trip, Room/SQLite for state that has to survive a dead connection. Plus the unglamorous half: Gradle, ADB, Metro, and the cross-platform build failures nobody writes blog posts about.

### payments infrastructure

Transaction rails, terminal software, and the standards underneath them — how a payment actually clears, what the terminal is legally obliged to do, and where the failure modes hide. Interested in rail-agnostic design: systems that don't hardcode one network into the domain model.

### cryptography & post-quantum readiness

Classical foundations (RSA signing, stream and block ciphers, implemented rather than just read about) and where they break. Crypto agility as an architectural property — what it costs to make a live system able to swap primitives, and what "quantum-safe" has to mean in production rather than on a slide.

### agentic AI, with real permissions

Authorization layers for agents that move money — scoped mandates, revocation, audit trails, and the assumption that the agent will eventually do something stupid. Building for the case where the model is wrong and the ledger still has to be right.

### transformers, from the inside

Attention, positional encoding, tokenization, embeddings — worked through implementation-first rather than API-first, because the failure modes only make sense once you've seen the matrices.

<div align="center">
  <sub><code>─────────────────────  具  ─────────────────────</code></sub>
</div>

```
core        TypeScript · React · React Native · Python · C/C++ · Java (native modules) · SQL
mobile      Expo · Gradle · Android SDK · NFC/HCE · TFLite · Room/SQLite
web         Next.js (App Router) · TanStack Query · TanStack Table
ml          NumPy · Matplotlib · transformers · local inference (Ollama)
tooling     Git · Claude Code · MCP · Cursor · Obsidian
```

<div align="center">
  <sub><code>─────────────────────  外  ─────────────────────</code></sub>
</div>

Outside the terminal I run a university tech council — which is mostly logistics, email pipelines, and convincing four hundred people to be in the same room at the same time. Turns out shipping an event and shipping software fail for identical reasons.

Otherwise: F1, chess, table tennis, geopolitics, and an unreasonable amount of Minecraft.

<div align="center">
  <br />
  <img src="https://github-readme-stats.vercel.app/api?username=FalconBirdONE&show_icons=true&hide_border=true&bg_color=00000000&title_color=8FA3B8&text_color=7D8B99&icon_color=8FA3B8&hide=issues&card_width=420" />
  <br /><br />
  <sub><code>一期一会</code></sub>
  <br />
  <sub>ichi-go ichi-e — one encounter, one chance. build it like it counts.</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=transparent&height=60&section=footer" width="100%" />
