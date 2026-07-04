# HyperFrames + Claude Code — Free Dynamic-Video Stack

A reference + setup guide for enhancing AI-generated videos with HeyGen HyperFrames.
**Everything here is free: no subscription, no trial.** (API keys/local models noted where needed.)

---

## 0. Prerequisites

HyperFrames needs two things on your machine before anything else works:

```bash
# Node.js 22+  (check your version)
node -v

# FFmpeg  (the engine that compiles frames into MP4)
#   macOS:           brew install ffmpeg
#   Ubuntu/Debian:   sudo apt install ffmpeg
#   Windows:         winget install Gyan.FFmpeg
ffmpeg -version
```

---

## 1. One-shot stack install

```bash
# --- HyperFrames core + agent skills (Apache 2.0) ---
npx skills add heygen-com/hyperframes        # teaches Claude Code the production loop
npx hyperframes init my-video                # scaffold a project
cd my-video

# --- Dynamic catalog blocks (transitions, overlays, captions, charts) ---
npx hyperframes add flash-through-white      # shader transition
npx hyperframes add instagram-follow         # social overlay
npx hyperframes add data-chart               # animated chart

# --- Preview / render ---
npx hyperframes preview                      # live browser preview
npx hyperframes render                       # export MP4
```

Animation libraries (GSAP, Three.js, Anime.js, Lottie) load via CDN inside your
composition HTML — no separate install needed. See the CDN snippets in section 4.

---

## 2. Pexels MCP — free stock footage inside Claude Code

Get a free API key (no credit card) at https://www.pexels.com/api/, then add to your
MCP client config (`claude_desktop_config.json` or Claude Code MCP settings):

czIK4UueWVwMq0bCD3fOIrGtHHClLlnRaUUOSFC3TpervI5KCngmLLuh

```json
{
  "mcpServers": {
    "pexels": {
      "command": "npx",
      "args": ["-y", "mcp-pexels"],
      "env": { "PEXELS_API_KEY": "your_key_here" }
    }
  }
}
```

Restart the client and Claude can search/fetch royalty-free HD video + photos directly
into a HyperFrames `<video>` track. **Attribution to Pexels + photographer is required.**

---

## 3. Kinetic captions — whisper.cpp (runs 100% locally, free)

```bash
git clone https://github.com/ggml-org/whisper.cpp
cd whisper.cpp && make
# download a model (base.en is a good start)
bash ./models/download-ggml-model.sh base.en

# extract avatar audio, then transcribe to word-level SRT
ffmpeg -i avatar.mp4 -ar 16000 -ac 1 audio.wav
./main -m models/ggml-base.en.bin -f audio.wav -osrt
```

Feed the SRT timestamps into GSAP SplitText (section 4) for pop-in / word-by-word captions.

---

## 4. The tool stack at a glance

| Tool | Link | What it does | Free? |
|---|---|---|---|
| **HyperFrames Agent Skills** | github.com/heygen-com/hyperframes | Teaches Claude Code to plan, write HTML, animate, lint, preview, render | Yes — Apache 2.0 |
| **HyperFrames Catalog** | hyperframes.heygen.com/catalog | Drop-in transitions, overlays, captions, charts, maps, effects | Yes — Apache 2.0 |
| **@hyperframes/shader-transitions** | github.com/heygen-com/hyperframes | WebGL shader wipes/dissolves between scenes | Yes — Apache 2.0 |
| **GSAP** | gsap.com | Kinetic text + choreographed motion; all plugins incl. SplitText/ScrollTrigger | Yes — fully free since Apr 2025, commercial OK |
| **Three.js** | threejs.org | WebGL/3D scenes, product spins, particle backgrounds | Yes — MIT |
| **Anime.js** | animejs.com | Lightweight SVG/DOM motion, staggered overlays | Yes — MIT |
| **Lottie / dotLottie** | lottiefiles.com | Ready-made animated icons/graphics; runtime adapter | Yes — runtimes MIT; assets under Lottie Simple License* |
| **Pexels MCP** | github.com/developer-ishan/mcp-pexels | Pulls free stock video/photo into Claude Code | Yes — MIT; free API key; attribution required |
| **whisper.cpp** | github.com/ggml-org/whisper.cpp | Local transcription → SRT/VTT with word timestamps | Yes — open source, offline |
| **FFmpeg** | ffmpeg.org | Required render engine + post-processing (concat, audio, GIF) | Yes — LGPL/GPL |

\* Free Lottie assets allow commercial use without attribution, but check each file —
paid assets sit alongside free ones.

CDN snippets for the animation adapters (paste into composition HTML):

```html
<script src="https://cdn.jsdelivr.net/npm/gsap@3/dist/gsap.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/gsap@3/dist/SplitText.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/three@latest/build/three.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/animejs@3/lib/anime.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/lottie-web@latest/build/player/lottie.min.js"></script>
```

---

## 5. Ready-to-use Claude Code prompts

```
Using /hyperframes, create a 15-second product intro: fade-in title with GSAP
SplitText (word-by-word), a Pexels background video of a city skyline, the
flash-through-white transition between scenes, and subtle background music.
```

```
Using /hyperframes, build a 30-second social explainer. Pull 3 B-roll clips from
Pexels, add the data-chart block animating our Q2 numbers, and overlay kinetic
captions from captions.srt timed word-by-word.
```

---

## 6. Recommended priority (most impact, least effort)

1. **GSAP SplitText + whisper.cpp** → animated word-by-word captions (biggest retention win)
2. **Catalog transition blocks** → instant scene-to-scene polish
3. **Pexels MCP** → kill flat, static backgrounds with real B-roll

## 7. Stakeholder license notes

- No subscriptions or trials anywhere in this stack.
- Pexels: free key + attribution required.
- Lottie: runtimes fully free; license-check individual downloaded animations.
- HyperFrames/GSAP/Three.js/Anime.js/whisper.cpp/FFmpeg: free for commercial use.
