<h1 align="center">Haplo</h1>

<p align="center">
  <strong>Local-first AI for the Apple ecosystem.</strong><br>
  <em>On-device. Offline-capable. Yours.</em>
</p>

<p align="center">
  <a href="https://haplo.ai">haplo.ai</a> ·
  <a href="https://twitter.com/jc_builds">@jc_builds</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Apple-ecosystem-black?logo=apple" alt="Apple ecosystem">
  <img src="https://img.shields.io/badge/Swift-5.9%2B-orange?logo=swift" alt="Swift">
  <img src="https://img.shields.io/badge/local--first-AI-blueviolet" alt="Local-first AI">
  <img src="https://img.shields.io/badge/MIT-licensed-green" alt="MIT licensed">
</p>

---

## What we ship

🤖 **[Haplo](https://haplo.ai)** — A private AI chat for iOS. Runs on-device, works offline, plugs into any GGUF model or Apple Foundation Models. No cloud. No subscription. No data leaving your phone.

The packages below all power Haplo and are free for anyone else building local AI on Apple platforms.

## Open source

### Shipped

| Package | What it does |
|---|---|
| 🐪 **[Kuzco](https://github.com/haplollc/Kuzco)** | On-device LLM, vision, image, and 3D inference for Apple platforms. Wraps llama.cpp + others into a clean Swift API. |
| 🎭 **[Gepetto](https://github.com/haplollc/Gepetto)** | LLM-driven browser automation. Native WKWebView agent loop with multi-step task execution and AI validation. |
| 🔥 **[Forge](https://github.com/haplollc/Forge)** | Floating SwiftUI debugger for local LLMs. Live tokens/sec, memory, context — for any inference stack. |

### In progress

| Package | What it'll do |
|---|---|
| 🧬 **[Foundry](https://github.com/haplollc/Foundry)** | On-device LoRA fine-tuning. Personalize a local LLM from inside your app, while it sleeps. |
| 🕸️ **[Mesh](https://github.com/haplollc/Mesh)** | Peer-to-peer LLM federation over LAN. iPhone borrows your Mac's 70B over wifi. |
| ✨ **[Apparition](https://github.com/haplollc/Apparition)** | One SwiftUI modifier that gives any view AI superpowers. `.aiAware()` and you're done. |

## Why local

Cloud AI is expensive, slow, and needs your data.<br>
On-device AI is free, fast, and private.

We bet that as Apple Silicon gets faster and models get smaller, more apps will stop sending prompts to a data center. So we're building the stack that makes that easy in Swift.

- **Privacy** — your data stays on your device. No telemetry. No API key. No opaque middleware.
- **Cost** — no per-token billing. Run unlimited inference on hardware you already paid for.
- **Latency** — round-trips to a data center add hundreds of milliseconds. On-device is faster.
- **Offline** — airplane mode, subway, basement, plane. AI shouldn't need wifi.
- **Resilience** — your AI doesn't break when OpenAI has an outage.

## Stack

Apple Silicon · Swift · SwiftUI · Metal · llama.cpp · ONNX Runtime · Apple Foundation Models · SwiftData

## License

All public packages MIT-licensed unless otherwise noted. Ship them in your apps. A star or a shout-out is appreciated, never required.

---

<p align="center">
  <em>ship happens 🚢</em>
</p>
