<h1 align="center">Haplo</h1>

<p align="center">
  <strong>Swift packages for things that should be hard.</strong><br>
  <em>On-device AI, real 3D, live interpreters. All running on the phone in your pocket.</em>
</p>

<p align="center">
  <a href="https://haploapp.com">haploapp.com</a> &middot;
  <a href="https://twitter.com/jc_builds">@jc_builds</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Apple-ecosystem-black?logo=apple" alt="Apple ecosystem">
  <img src="https://img.shields.io/badge/Swift-5.9%2B-orange?logo=swift" alt="Swift">
  <img src="https://img.shields.io/badge/on--device-first-blueviolet" alt="On-device first">
  <img src="https://img.shields.io/badge/MIT-licensed-green" alt="MIT licensed">
</p>

---

## Featured

<table>
<tr>
<td width="50%" valign="top">

### 📱 [iOS Eras](https://github.com/haplollc/ios-eras)

Drag a ruler from 2007 to 2026 and watch the iPhone rebuild itself. Every
stock app arrives in the release it shipped in, every icon is redrawn at
every redesign, and the dock, the notch and the Dynamic Island morph from one
year to the next. Every position was measured off a real screenshot of that
version.

**[Try it in your browser →](https://haplollc.github.io/ios-eras/)**

</td>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/haplollc/ios-eras/main/media/home-screen-eras.gif" width="100%" alt="Scrubbing the iPhone home screen from 2007 to 2026">

</td>
</tr>

<tr>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/haplollc/ThinkingOrbs/main/assets/banner-light.gif" width="100%" alt="All nine ThinkingOrbs designs animating side by side">

</td>
<td width="50%" valign="top">

### 🔮 [ThinkingOrbs](https://github.com/haplollc/ThinkingOrbs)

Dotted, genuinely 3D loading indicators for AI and agent interfaces. Nine
hand-tuned designs and two purpose-tuned sizes, drawn only in grayscale dots
so they sit quietly in any interface, light or dark.

```swift
ThinkingOrb(.searching)
```

That is the whole integration.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🪙 [Minted](https://github.com/haplollc/Minted)

Hand it a flat image of a pin and get back a real 3D coin: the artwork
becomes the face, the outline is traced from the image, and the gold in the
art is detected and rendered as metal that catches the light.

```swift
let coin = try ArtworkCoin(image: pinArtwork)
SpinningArtworkCoinView(coin: coin)
```

No 3D model files. One PNG per pin.

</td>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/haplollc/Minted/main/assets/demo.gif" width="100%" alt="Minted turning pin artwork into spinning 3D collectible coins">

</td>
</tr>

<tr>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/haplollc/ClayGlobe/main/assets/demo.gif" width="100%" alt="ClayGlobe planting waving flags on a claymorphic 3D globe">

</td>
<td width="50%" valign="top">

### 🌍 [ClayGlobe](https://github.com/haplollc/ClayGlobe)

A claymorphic globe that plants a waving flag on every country someone has
visited, and works out where they have been from photo metadata alone.
Offline reverse geocoding included, no network and no API key.

```swift
@StateObject var globe = GlobeManager()
ClayGlobeView(manager: globe)
await globe.scanPhotoLibrary()
```

</td>
</tr>
</table>

---

## Everything we ship

### On-device AI

| Package | What it does | |
|---|---|---|
| 🎨 **[Mirage](https://github.com/haplollc/Mirage)** | Diffusion image generation on iOS, macOS and visionOS. Embeds `stable-diffusion.cpp` and `ggml-metal`, so SD, SDXL, SD3, Flux, Chroma, Qwen-Image and anything else sd.cpp loads runs without a Core ML conversion. | ![stars](https://img.shields.io/github/stars/haplollc/Mirage?style=flat&label=%20&color=gray) |
| 🎭 **[Gepetto](https://github.com/haplollc/Gepetto)** | LLM-driven browser automation. A native WKWebView agent loop that navigates, extracts, interacts and screenshots, with the model checking its own work. | ![stars](https://img.shields.io/github/stars/haplollc/Gepetto?style=flat&label=%20&color=gray) |
| 🔥 **[Forge](https://github.com/haplollc/Forge)** | A floating SwiftUI debugger for local models. Every token, sampler, grammar mask and tool call, live, over any inference stack. | ![stars](https://img.shields.io/github/stars/haplollc/Forge?style=flat&label=%20&color=gray) |
| 🧬 **[Foundry](https://github.com/haplollc/Foundry)** | On-device LoRA fine-tuning. Personalize a local model from inside your app, while the phone sleeps. | ![stars](https://img.shields.io/github/stars/haplollc/Foundry?style=flat&label=%20&color=gray) |
| 🕸️ **[Mesh](https://github.com/haplollc/Mesh)** | Peer-to-peer model federation over the LAN, so an iPhone can borrow the 70B running on your Mac. | ![stars](https://img.shields.io/github/stars/haplollc/Mesh?style=flat&label=%20&color=gray) |
| ✨ **[Apparition](https://github.com/haplollc/Apparition)** | One modifier that gives any SwiftUI view AI awareness. `.aiAware()` and you are done. | ![stars](https://img.shields.io/github/stars/haplollc/Apparition?style=flat&label=%20&color=gray) |

### Graphics and 3D

| Package | What it does | |
|---|---|---|
| 🪙 **[Minted](https://github.com/haplollc/Minted)** | Flat pin artwork becomes a physically lit 3D coin, with the gold in the art rendered as real metal. Also mints coins from SVG paths. | ![stars](https://img.shields.io/github/stars/haplollc/Minted?style=flat&label=%20&color=gray) |
| 🌍 **[ClayGlobe](https://github.com/haplollc/ClayGlobe)** | A claymorphic 3D globe that plants flags on visited countries, with offline coordinate-to-country lookups. | ![stars](https://img.shields.io/github/stars/haplollc/ClayGlobe?style=flat&label=%20&color=gray) |
| 💪 **[MuscleMapKit](https://github.com/haplollc/MuscleMapKit)** | An interactive 3D body that shades each muscle by how hard it was worked, spins under a finger, and reports taps by muscle group. | ![stars](https://img.shields.io/github/stars/haplollc/MuscleMapKit?style=flat&label=%20&color=gray) |

### Interface

| Package | What it does | |
|---|---|---|
| 🔮 **[ThinkingOrbs](https://github.com/haplollc/ThinkingOrbs)** | Dotted, genuinely 3D loading indicators for AI and agent interfaces. Nine designs, two sizes, one line to drop in. | ![stars](https://img.shields.io/github/stars/haplollc/ThinkingOrbs?style=flat&label=%20&color=gray) |
| 📱 **[iOS Eras](https://github.com/haplollc/ios-eras)** | Twenty years of iPhone on one ruler: the home screen and the button from 2007 to 2026, in SwiftUI and [in the browser](https://haplollc.github.io/ios-eras/). | ![stars](https://img.shields.io/github/stars/haplollc/ios-eras?style=flat&label=%20&color=gray) |

### Runtimes

| Package | What it does | |
|---|---|---|
| 🐍 **[Terrarium](https://github.com/haplollc/Terrarium)** | Python 3.13 embedded in an iOS or macOS app, with on-device `pip install` and a Pyodide fallback for numpy, pandas, matplotlib and friends. | ![stars](https://img.shields.io/github/stars/haplollc/Terrarium?style=flat&label=%20&color=gray) |
| 🔥 **[Kiln](https://github.com/haplollc/Kiln)** | A live Swift and SwiftUI interpreter you can embed anywhere. Hand it Swift source at runtime, get back a real view. No compile step. | ![stars](https://img.shields.io/github/stars/haplollc/Kiln?style=flat&label=%20&color=gray) |

---

## Why on-device

Cloud is expensive, slow, and wants your data. The phone in your pocket is
none of those things.

- **Private** &mdash; your data never leaves the device. No telemetry, no API key, no middleware.
- **Free to run** &mdash; no per-token billing on hardware you already paid for.
- **Fast** &mdash; a round trip to a data center costs hundreds of milliseconds you do not have to spend.
- **Offline** &mdash; airplane mode, the subway, a basement. None of it should stop your app.
- **Yours** &mdash; nothing breaks because somebody else had an outage.

## Apps

**[Bilbo](https://haploapp.com/bilbo)** &mdash; a travel app that plans whole trips on
device, and turns the landmarks you visit into collectible 3D pins. ClayGlobe
and Minted were both pulled out of it.

## Stack

Apple Silicon &middot; Swift &middot; SwiftUI &middot; SceneKit &middot; Metal &middot;
llama.cpp &middot; stable-diffusion.cpp &middot; ggml &middot; Apple Foundation Models &middot; SwiftData

## License

Every public package is MIT licensed unless its repo says otherwise. Ship them
in your apps. A star or a shout-out is appreciated, never required.

---

<p align="center">
  <em>ship happens 🚢</em>
</p>
