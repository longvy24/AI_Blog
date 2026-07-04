# AI Prompting Series · Vol 2 — Metadata Tracker

Videos 11–20. Three variations per video (A original / B reframed hook + app-chrome aesthetic / C reframed demo + illustrated diagram aesthetic). Each gets its own MP4, blog post, and per-platform SEO copy.

**Music credit (required in every YouTube description; paste into IG/TikTok captions):**
```
Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Series-wide hashtag baseline:** `#ChatGPT #AItools #PromptEngineering #ChatGPTTips #AIhacks #productivity #tech #LearnAI`

---

## Video 11 · Context Feeding

**Status:** ✅ Shipped — all 3 variations rendered
**Topic:** Pasting the previous output back in with one bridging line so ChatGPT picks up where it left off
**Color scheme:** 🟢 Lime
**Blog post:** [`Go_Live/ai-prompting/21-context-feeding.html`](Go_Live/ai-prompting/21-context-feeding.html)

### Renders

| Variant | File | Runtime | Size | Hook angle | Visual |
|---|---|---|---|---|---|
| A | [`11-context-feeding.mp4`](Videos/AI_Prompt_Engineering_Vol2/11-context-feeding/11-context-feeding.mp4) | 41s | 6.5 MB | Problem-led (amnesia chat mockup) | Standard cards + chat bubbles |
| B | [`11b-context-feeding.mp4`](Videos/AI_Prompt_Engineering_Vol2/11-context-feeding/11b-context-feeding.mp4) | 40s | 5.7 MB | Solution-led ("Give AI a memory") | Realistic desktop AI app chrome (sidebar, traffic lights, send button) |
| C | [`11c-context-feeding.mp4`](Videos/AI_Prompt_Engineering_Vol2/11-context-feeding/11c-context-feeding.mp4) | 36s | 5.7 MB | Problem-led (torn pages metaphor) | Illustrated diagram aesthetic — storyboard panels, branching workflow, thought-bubble chain. Creative-writing demo (Sarah). |

### YouTube Shorts

**Title:**
```
ChatGPT Keeps Forgetting What You Said — Here's the Fix
```

**Description:**
```
ChatGPT has no memory between prompts. So if you built something great in one message, the next prompt starts from zero — and the output drifts. The fix: paste the previous output back in and add one bridging line. "Using the strategy above, now write..." Suddenly it's consistent, connected, and coherent.

This is called context feeding, and it's the technique that turns a single-session AI into a long-form collaborator. Works on ChatGPT, Claude, and Gemini.

│ ChatGPT memory │ ChatGPT forgets │ how to use ChatGPT │ context feeding │ AI long-form writing │ prompt engineering tips │ ChatGPT for creators │ AI tools 2026 │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #ChatGPTTips #AIhacks #productivity #ContentCreators #sidehustle #tech #YouTubeShorts
```

**Pinned comment:**
```
The exact bridge line I use: "Using what you just wrote above, now [next task]." What's the longest thing you've tried to build with ChatGPT? 👇
```

### Instagram Reels

**Caption:**
```
ChatGPT forgets everything — here's how to fix it 🧩

Save this 🔖 — the one-line trick that makes ChatGPT remember what it just built.
```

**Hashtags:**
```
#ChatGPT #PromptEngineering #AIhacks #AItools #productivity #ContentCreators #LearnAI
```

### TikTok

**Caption:**
```
ChatGPT forgets what it just said — this fixes it instantly 🧩 What's the longest thing you've tried to build with AI? 👇
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #TechTok #productivity
```

### Thumbnails (use `thumbnail-generator-v4.html`)

**Primary — for Variant A:**
- Icon: 🧩  ·  Scheme: Lime
- L1: `CHATGPT` — Lime / MD
- L2: `KEEPS FORGETTING` — White / XL
- L3: `FIX THIS` — Lime / LG

**Backup — for Variant B (solution-led):**
- Icon: 🔁  ·  Scheme: Lime
- L1: `GIVE AI` — Lime / MD
- L2: `A MEMORY` — White / XL
- L3: `HERE'S HOW` — Lime / LG

**Alt — for Variant C (creative-writing angle):**
- Icon: 📖  ·  Scheme: Lime
- L1: `AI LOSES` — Lime / MD
- L2: `THE PLOT` — White / XL
- L3: `MID-SCENE` — Lime / LG

### Build changes / notes

- **New brand lime `#84E000`** (not Vol 1's `#a3e635`) — matches the v4 thumbnail generator and blog template
- **Hyperframes bumped to 0.6.18** (Vol 1 was 0.5.7) — same API
- **V11C bug fix:** SVG animated paths (`#path-1/2/3`, `#chain-path`) were visible by default in their scene's CSS, so the branching dashed lines appeared floating with nothing connected during scene-3 fade-in. Fix: added `tl.set([...paths], { opacity: 0 }, 0)` at the very top of the GSAP timeline so they're hidden from t=0. Pattern applies to any future video using stroke-dashoffset path-drawing animations.
- **Music + voice baseline:** Infraction track at `data-volume="0.15"` with 3.5s `power2.in` fade-out; `am_adam` Kokoro voice

### Posting cadence (per strategy doc)

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily (this one in rotation), 7-9am or 7-9pm EST

---

## Video 12 · System Prompts

**Status:** ✅ Shipped — all 3 variations rendered
**Topic:** Custom instructions / system prompt field — set rules once, every conversation follows them
**Color scheme:** 🔵 Blue (`#38BDF8`)
**Blog post:** [`Go_Live/ai-prompting/22-system-prompts.html`](Go_Live/ai-prompting/22-system-prompts.html)

### Renders

| Variant | File | Runtime | Size | Hook angle | Visual |
|---|---|---|---|---|---|
| A | [`12-system-prompts.mp4`](Videos/AI_Prompt_Engineering_Vol2/12-system-prompts/12-system-prompts.mp4) | 37s | 5.8 MB | Problem-led ("There's a hidden layer") | Circuit-chip icon (12 pins + pulsing core) + prompt-card demo with WITHOUT/WITH comparison stack |
| B | [`12b-system-prompts.mp4`](Videos/AI_Prompt_Engineering_Vol2/12-system-prompts/12b-system-prompts.mp4) | 37s | 5.6 MB | Solution-led ("Configure once. AI runs differently forever") | Realistic ChatGPT settings-modal chrome (sidebar nav highlighted, Custom Instructions field with placeholder→filled, Cancel/Save buttons). 3-slider control panel icon |
| C | [`12c-system-prompts.mp4`](Videos/AI_Prompt_Engineering_Vol2/12-system-prompts/12c-system-prompts.mp4) | 37s | 6.6 MB | Problem-led (layered-stack visualization — Conversation/Prompts/★System Prompt) | Illustrated diagram aesthetic — graph-paper bg, dashed rules card, Poetry Coach → haiku demo, foundation+5-branches SVG. Creative-writing demo angle. |

### YouTube Shorts

**Title:**
```
The Hidden Layer In Every ChatGPT Conversation
```

**Description:**
```
There's a hidden layer in every ChatGPT conversation, and most users never touch it. It's called the system prompt — and you can set it yourself. Set a persona, a format, and a constraint, and from that moment forward every new chat follows those rules. No more starting from zero. No more repeating yourself.

ChatGPT calls it Custom Instructions. It lives in Settings → Personalization. Spend 10 minutes today writing yours and you'll save that time back in the first week.

│ ChatGPT custom instructions │ system prompt │ ChatGPT settings │ how to use ChatGPT │ prompt engineering │ ChatGPT productivity │ AI tools 2026 │ AI hacks │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #ChatGPTTips #AIhacks #productivity #CustomInstructions #SystemPrompt #LearnAI #YouTubeShorts
```

**Pinned comment:**
```
My exact system prompt template: "You are a [persona]. Always respond in [format]. Never [constraint]." What persona are you running ChatGPT as? 👇
```

### Instagram Reels

**Caption:**
```
There's a hidden layer in every ChatGPT conversation 🧬

Save this 🔖 — the one setting that changes every reply forever.
```

**Hashtags:**
```
#ChatGPT #PromptEngineering #AIhacks #AItools #productivity #CustomInstructions #LearnAI
```

### TikTok

**Caption:**
```
There's a hidden setting in ChatGPT that changes every reply forever 🧬 Save this — you'll use it tonight.
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #TechTok #productivity
```

### Thumbnails (use `thumbnail-generator-v4.html`)

**Primary — for Variant A:**
- Icon: 🧬  ·  Scheme: Blue
- L1: `THE HIDDEN` — Blue / MD
- L2: `LAYER IN AI` — White / XL
- L3: `MOST IGNORE` — Blue / LG

**Backup — for Variant B (solution-led / settings-screen):**
- Icon: ⚙️  ·  Scheme: Blue
- L1: `CONFIGURE` — Blue / MD
- L2: `CHATGPT ONCE` — White / XL
- L3: `HERE'S HOW` — Blue / LG

**Alt — for Variant C (creative-writing angle):**
- Icon: 📜  ·  Scheme: Blue
- L1: `LOCK IN` — Blue / MD
- L2: `YOUR VOICE` — White / XL
- L3: `EVERY CHAT` — Blue / LG

### Build changes / notes

- **New blue palette** for blog post: `--blue: #38BDF8` on `--bg: #0D1117` — mirrors the video's color scheme. CSS variables follow the same shape as V11's lime palette (`--blue-dim`, `--blue-glow`)
- **Distinct icons across variants:** V12A uses a **circuit chip** (12 pins + corner nodes + pulsing core), V12B uses a **3-slider control panel** (knobs at different positions), V12C uses the **layered-stack rectangles** (no icon). Resolves the "same gear in A and B" issue caught in preview
- **Renders organized into per-video subfolder:** `Videos/AI_Prompt_Engineering_Vol2/12-system-prompts/` containing all 3 MP4s (matches new V11 layout)
- **V11 blog post embed path updated** to match the new nested folder structure
- **GSAP hide-at-t0 rule applied** in V12C: `tl.set(["#fpath-1..5","#fbubbles"], { opacity: 0 }, 0)` to prevent the foundation diagram's dashed branches from flashing before scene 4 — same pattern saved as memory from V11C
- **Hyperframes versions:** V12A on 0.6.19, V12B on 0.6.19, V12C on 0.6.20 (matches whatever each scaffold pulled at init time)

### Posting cadence (per strategy doc)

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily (this one in rotation), 7-9am or 7-9pm EST

---

## Video 13 · Zero-Shot vs. Few-Shot

**Status:** ✅ Shipped — all 3 variations rendered
**Topic:** Head-to-head test — when to use zero-shot vs few-shot prompting
**Color scheme:** 🔴 Red (`#EF4444`)
**Blog post:** [`Go_Live/ai-prompting/23-zero-shot-vs-few-shot.html`](Go_Live/ai-prompting/23-zero-shot-vs-few-shot.html)

### Renders

| Variant | File | Runtime | Size | Hook angle | Visual |
|---|---|---|---|---|---|
| A | [`13-zero-vs-few.mp4`](Videos/AI_Prompt_Engineering_Vol2/13-zero-vs-few/13-zero-vs-few.mp4) | 37s | 5.2 MB | Direct comparison ("Two methods. Same task. Wildly different.") | Vertical split-screen arena (top=Zero-Shot, bottom=Few-Shot, giant red VS badge), method cards, 2-row scoresheet, verdict rule |
| B | [`13b-zero-vs-few.mp4`](Videos/AI_Prompt_Engineering_Vol2/13-zero-vs-few/13b-zero-vs-few.mp4) | 37s | 5.1 MB | Experiment framing ("I ran the same prompt 2 ways") | Realistic ChatGPT chat-window chrome — traffic lights, send button, two stacked windows showing both prompts running with verdict pills (6/10 GENERIC vs 9/10 ★ WINNER) |
| C | [`13c-zero-vs-few.mp4`](Videos/AI_Prompt_Engineering_Vol2/13-zero-vs-few/13c-zero-vs-few.mp4) | 37s | 5.1 MB | Teacher metaphor ("ChatGPT just took an exam") | Illustrated/notebook aesthetic — graph-paper bg, two student-desk SVGs (blank vs study-notes), notebook strategy page, graded scoresheet with Q1/Q2 + totals row |

### YouTube Shorts

**Title:**
```
I Tested Two ChatGPT Prompt Styles — One Clearly Wins
```

**Description:**
```
Zero-shot prompting: just ask the question. Few-shot prompting: give 2–3 examples first, then ask. I ran the same tasks through both — and the results will change how you prompt.

Spoiler: few-shot wins on creative and format-heavy tasks. Zero-shot holds its own on simple, direct questions. Knowing when to use each is the real skill. Works on ChatGPT, Claude, and Gemini.

│ ChatGPT prompting methods │ few-shot vs zero-shot │ ChatGPT tips │ how to prompt ChatGPT │ prompt engineering comparison │ AI output quality │ ChatGPT for work │ AI tools 2026 │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #FewShot #ZeroShot #AIhacks #productivity #tech #LearnAI #YouTubeShorts
```

**Pinned comment:**
```
The verdict: few-shot for format-heavy tasks, zero-shot for quick questions. Which one have you been using? 👇
```

### Instagram Reels

**Caption:**
```
Zero-shot vs. few-shot — which ChatGPT method wins? ⚔️

Save this 🔖 — the quick rule for when to use each one.
```

**Hashtags:**
```
#ChatGPT #PromptEngineering #AIhacks #AItools #FewShot #productivity #LearnAI
```

### TikTok

**Caption:**
```
I tested zero-shot vs few-shot prompting — one clearly wins ⚔️ Which do you use more? 👇
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #TechTok #productivity
```

### Thumbnails (use `thumbnail-generator-v4.html`)

**Primary — for Variant A:**
- Icon: ⚔️  ·  Scheme: Red
- L1: `I TESTED` — Red / MD
- L2: `BOTH METHODS` — White / XL
- L3: `ONE WINS` — Red / LG

**Backup — for Variant B (chat-windows / experiment angle):**
- Icon: 🆚  ·  Scheme: Red
- L1: `SAME PROMPT` — Red / MD
- L2: `TWO RESULTS` — White / XL
- L3: `9 VS 6` — Red / LG

**Alt — for Variant C (exam student / illustrated):**
- Icon: 📝  ·  Scheme: Red
- L1: `CHATGPT` — Red / MD
- L2: `TOOK AN EXAM` — White / XL
- L3: `THE SCORE` — Red / LG

### Build changes / notes

- **Distinct aesthetics across variants:** A = vertical split-screen battle arena. B = realistic ChatGPT chat windows (traffic lights, send button, message bubbles, verdict pills). C = notebook/graph-paper + student-desk SVG illustrations + graded scoresheet
- **Contrast fix at scoresheet:** `.tscore.lose` color `#5a3a3a` failed WCAG (1.6:1) — bumped to `#a87878` / `#b89090` for readable-but-still-muted "losing side" treatment. Same `#fca5a5` palette applied to `.rbadge` text in all variants
- **Acceptable false positives:** V13B has 9 contrast warnings on `.cw-send "↑"` (dark text on bright red send button) — same recurring sampling artifact as V12B's Save button, V12A/B/C accent badges. Visually correct, validator misreads
- **Variant-specific hook VOs:** V13A vo1 = "Two methods. Same task. Wildly different outputs." V13B vo1 = "I ran the same ChatGPT prompt two different ways." V13C vo1 = "ChatGPT just walked into an exam. Zero-shot, no notes." Shared vo2/vo4/vo5 across all three. C also gets a custom vo3 (exam scoring reframe)
- **Scene timing varies per variant** because V13C's hook VO is 7.1s (the longest) — scenes shifted to 7.5/13/20.5/27 instead of A's 5.5/11/18/25 boundaries
- **Hyperframes:** all three on 0.6.20

### Posting cadence (per strategy doc)

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily (this one in rotation), 7-9am or 7-9pm EST

---

## Video 14 · Temperature & Randomness

**Status:** ✅ Shipped — all 3 variations rendered
**Topic:** Temperature setting (0.0–1.0) — low for precise outputs, high for creative ones
**Color scheme:** 🔵 Blue (`#38BDF8`)
**Blog post:** [`Go_Live/ai-prompting/24-temperature-randomness.html`](Go_Live/ai-prompting/24-temperature-randomness.html)

### Renders

| Variant | File | Runtime | Size | Hook angle | Visual |
|---|---|---|---|---|---|
| A | [`14-temperature.mp4`](Videos/AI_Prompt_Engineering_Vol2/14-temperature/14-temperature.mp4) | 37s | 5.6 MB | "Most people never touch this dial" | Hero slider with gradient track (blue→indigo→red) — handle **animates 0.2 → 0.9 live** with value counter ticking; demo "Describe a cat" at 0.2 vs 0.9; 3 use-case cards |
| B | [`14b-temperature.mp4`](Videos/AI_Prompt_Engineering_Vol2/14-temperature/14b-temperature.mp4) | 37s | 4.6 MB | "Hidden in every AI tool — one slider" | Full OpenAI Playground app chrome — traffic lights, `platform.openai.com` title, sidebar with Model/Temp slider/Top P/Max Tokens; live slider drag; scenes 2/3 show same playground at 0.2 (3 identical runs) vs 0.9 (3 wildly different runs) |
| C | [`14c-temperature.mp4`](Videos/AI_Prompt_Engineering_Vol2/14-temperature/14c-temperature.mp4) | 37s | 6.1 MB | "AI has a temperature — zero is ice, one is jazz" | Illustrated — large SVG thermometer with mercury rising from cold blue → hot red, bulb color-shifts; notebook L/H definitions; 3 zone cards with ❄/🌤/🔥 emojis + sample outputs at 0.0/0.5/1.0 |

### YouTube Shorts

**Title:**
```
This ChatGPT Setting Controls How Creative (or Accurate) It Gets
```

**Description:**
```
There's a setting called Temperature hiding in most AI tools — and it changes everything. Turn it down and ChatGPT gets precise and consistent. Turn it up and it gets creative, unpredictable, and surprising. Most people never touch it.

Use low temperature for legal, finance, and technical writing. Use high temperature for brainstorming, creative writing, and ideation. Works in ChatGPT Playground, Claude, and Gemini Advanced.

│ ChatGPT temperature setting │ AI settings explained │ how to use ChatGPT │ ChatGPT for creative writing │ AI accuracy │ prompt engineering tips │ ChatGPT playground │ AI tools 2026 │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #ChatGPTTips #AIhacks #productivity #tech #LearnAI #Temperature #YouTubeShorts
```

**Pinned comment:**
```
My rule: 0.2 for anything factual, 0.8 for creative brainstorming, 1.0 when I want something surprising. What would you use high temp for? 👇
```

### Instagram Reels

**Caption:**
```
This AI dial changes everything — and most people never touch it 🌡️

Save this 🔖 — when to use low temp vs. high temp for better ChatGPT outputs.
```

**Hashtags:**
```
#ChatGPT #PromptEngineering #AIhacks #AItools #TechTips #productivity #LearnAI
```

### TikTok

**Caption:**
```
The AI temperature dial — low for accurate, high for creative 🌡️ What would you turn it up for? 👇
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #TechTok #productivity
```

### Thumbnails (use `thumbnail-generator-v4.html`)

**Primary — for Variant A:**
- Icon: 🌡️  ·  Scheme: Blue
- L1: `THE HIDDEN` — Blue / MD
- L2: `AI DIAL` — White / XL
- L3: `0.2 OR 0.9` — Blue / LG

**Backup — for Variant B (Playground / settings angle):**
- Icon: 🎚️  ·  Scheme: Blue
- L1: `ONE SLIDER` — Blue / MD
- L2: `CHANGES EVERYTHING` — White / XL
- L3: `HERE'S HOW` — Blue / LG

**Alt — for Variant C (thermometer / zones):**
- Icon: 🔥  ·  Scheme: Blue
- L1: `ICE COLD` — Blue / MD
- L2: `OR WILD JAZZ` — White / XL
- L3: `YOUR PICK` — Blue / LG

### Build changes / notes

- **Distinct icons + aesthetics across variants:** A = hero gradient-slider with animated handle/value counter. B = full OpenAI Playground app chrome (sidebar, model picker, multiple stub controls — visually different from V12B settings-modal and V13B chat-windows). C = animated SVG thermometer with mercury rising + bulb color-shift
- **Live slider/temp animation:** V14A and V14B both use a GSAP object proxy (`tempState`) to drive the value display text from 0.2 → 0.9 in sync with the visual fill width and handle position. V14C uses SVG `clipPath` rect attr animation for the mercury rise
- **Same-prompt demo:** All three variants use "Describe a cat" at low vs high temp — visual continuity across the trio. The cold output is encyclopedia-style, hot is "tiny philosopher in a fur coat" / "chaos engineers in fur coats"
- **Spectrum palette:** blue `#38BDF8` ↔ indigo `#818cf8` ↔ red `#EF4444` used consistently across the gradient track (V14A/B), the verdict rule card badges (LOW = blue, HIGH = red), and the zone cards (cold/warm/hot). Mirrors the actual cold→hot metaphor
- **Acceptable warnings:** All three pass WCAG (138/205/154 text elements respectively). Only known lint warnings are the recurring overlapping-tween false positives near scene transitions
- **Hyperframes:** all three on 0.6.20

### Posting cadence (per strategy doc)

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily (this one in rotation), 7-9am or 7-9pm EST

---

## Video 15 · Output Formatting Control

**Status:** ✅ Shipped — all 3 variations rendered
**Topic:** Add a "Format:" line to every prompt — AI fills any container you give it
**Color scheme:** 🔴 Red (`#EF4444`)
**Blog post:** [`Go_Live/ai-prompting/25-output-formatting.html`](Go_Live/ai-prompting/25-output-formatting.html)

### Renders

| Variant | File | Runtime | Size | Hook angle | Visual |
|---|---|---|---|---|---|
| A | [`15-formatting.mp4`](Videos/AI_Prompt_Engineering_Vol2/15-formatting/15-formatting.mp4) | 37s | 5.3 MB | Side-by-side format contrast ("Same prompt. Two outputs.") | Two stacked output cards (messy wall of text vs structured bullets), prompt-evolution card showing the `Format:` line being added, 3 preset cards (EXC/SOC/TUT) |
| B | [`15b-formatting.mp4`](Videos/AI_Prompt_Engineering_Vol2/15-formatting/15b-formatting.mp4) | 37s | 5.1 MB | "I added one line to my prompt" — experiment framing | Notion-style document app chrome — titlebar with traffic lights, breadcrumb nav (Workspace/Reports/Q4 Earnings), AI ASSIST badge, inline prompt row with `Format:` highlighted in red, animated build of clean output (header → 3 bullets → action line) |
| C | [`15c-formatting.mp4`](Videos/AI_Prompt_Engineering_Vol2/15-formatting/15c-formatting.mp4) | 37s | 5.9 MB | "AI is water — fills any container you give it" | Illustrated/blueprint aesthetic — **vertical stack of 4 vessels** (spilled puddle WITHOUT vs cup/beaker/flask WITH), each row with SVG + name + WITH/WITHOUT tag pill. Engineering blueprint page with 4-row spec sheet. 3 blueprint cards with BP-EXC-01/SOC-02/TUT-03 numbering |

### YouTube Shorts

**Title:**
```
Add This One Word to Every ChatGPT Prompt — Outputs Change Completely
```

**Description:**
```
The word is "Format:" — and it's the single biggest structural upgrade you can make to any ChatGPT prompt. Tell it exactly what shape you want the output in: bullet count, header style, word limit, ending format. ChatGPT will hit the spec every time. No editing, no reformatting, no copy-paste cleanup.

Works on ChatGPT, Claude, and Gemini. Use it for summaries, captions, emails, reports, and anything where layout matters.

│ ChatGPT formatting │ how to format ChatGPT output │ ChatGPT output control │ prompt formatting │ how to use ChatGPT │ better AI outputs │ prompt engineering tips │ AI tools 2026 │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #ChatGPTTips #AIhacks #productivity #tech #sidehustle #LearnAI #YouTubeShorts
```

**Pinned comment:**
```
My go-to format line: "Format: 3 bullet points. One bold header. Max 80 words. End with a one-line action item." Screenshot it — you'll use it today. What format do you always have to fix manually? 👇
```

### Instagram Reels

**Caption:**
```
One word makes ChatGPT format everything perfectly 📐

Save this 🔖 — the 3 format templates I use for every summary, caption, and report.
```

**Hashtags:**
```
#ChatGPT #PromptEngineering #AIhacks #AItools #TechTips #productivity #LearnAI
```

### TikTok

**Caption:**
```
Add "Format:" to your ChatGPT prompt — the output shape changes completely 📐 What format do you always fix manually? 👇
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #TechTok #productivity
```

### Thumbnails (use `thumbnail-generator-v4.html`)

**Primary — for Variant A:**
- Icon: 📐  ·  Scheme: Red
- L1: `ADD ONE WORD` — Red / MD
- L2: `FIXES EVERY PROMPT` — White / XL
- L3: `FORMAT:` — Red / LG

**Backup — for Variant B (Notion / app-chrome angle):**
- Icon: 📋  ·  Scheme: Red
- L1: `MESSY VS` — Red / MD
- L2: `STRUCTURED` — White / XL
- L3: `ONE LINE` — Red / LG

**Alt — for Variant C (containers / blueprint angle):**
- Icon: 🧪  ·  Scheme: Red
- L1: `AI IS WATER` — Red / MD
- L2: `BUILD THE SHAPE` — White / XL
- L3: `OR IT SPILLS` — Red / LG

### Build changes / notes

- **Distinct visual identities:** A = stacked output cards comparison + prompt-evolution flow. B = Notion-style doc editor app chrome (titlebar, breadcrumbs, AI prompt row, animated content build) — different from V12B (settings modal), V13B (chat windows), V14B (Playground sidebar). C = blueprint/engineering aesthetic with **vertical 4-vessel stack** (puddle + cup + beaker + flask), each row containing SVG + label + WITH/WITHOUT tag
- **V15C layout iteration:** Original horizontal 4-up grid was too cramped + left ~60% empty space below. User flagged at preview; rebuilt as vertical stack with each vessel as a full-width row (SVG-left, meta-middle, tag-right). Slide-in-from-left animation top-to-bottom + water-brightening sequence on the 3 WITH vessels
- **Contrast fixes during build:** V15B `.tsep "/"` breadcrumb separator was 2.5:1 (bumped from `#4b5563` to `#94a3b8`); `.em "Format:"` was 3.07:1 on red-tinted bg (bumped from `#EF4444` to `#fca5a5`). V15C corner-mark + spec-row em both got white bumps for clean WCAG passes
- **Acceptable false-positives:** Each variant has the recurring overlapping-GSAP-tweens warning (transition seams) — these are real overlaps but well under audible/visual perception
- **Hyperframes:** all three on 0.6.20

### Posting cadence (per strategy doc)

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily (this one in rotation), 7-9am or 7-9pm EST

---

## Video 16 · Tree of Thought

**Status:** ✅ Shipped — all 3 variations rendered
**Topic:** ToT prompting — explore 3 approaches, evaluate each, pick the best
**Color scheme:** 🟢 Lime (`#84E000`)
**Blog post:** [`Go_Live/ai-prompting/26-tree-of-thought.html`](Go_Live/ai-prompting/26-tree-of-thought.html)

### Renders

| Variant | File | Runtime | Size | Hook angle | Visual |
|---|---|---|---|---|---|
| A | [`16-tree-of-thought.mp4`](Videos/AI_Prompt_Engineering_Vol2/16-tree-of-thought/16-tree-of-thought.mp4) | 37s | 5.0 MB | "CoT is good. ToT is better" callback to V3 of the series | Live SVG tree diagram — root question → 3 evaluated branches → winner box. Method comparison cards in scene 2 |
| B | [`16b-tree-of-thought.mp4`](Videos/AI_Prompt_Engineering_Vol2/16-tree-of-thought/16b-tree-of-thought.mp4) | 37s | 5.6 MB | "I asked ChatGPT to explore 3 approaches at once" | **Whimsical/Miro-style canvas app** — toolbar (Frame/Connect/Node/★ AI Branch), dotted grid bg, AI prompt overlay, zoom pill. Scene 2: same canvas in **CoT linear-chain mode** (dim red, single path locks to wrong answer "Paid Ads"). Scene 3: canvas in ToT mode (lime, branching tree, picks Community Build). Distinct from V12-V15 app aesthetics |
| C | [`16c-tree-of-thought.mp4`](Videos/AI_Prompt_Engineering_Vol2/16-tree-of-thought/16c-tree-of-thought.mp4) | 37s | 6.2 MB | "AI takes the first path it finds" + literal stylized tree drawing | Scene 1: animated SVG tree grows from trunk → limbs → leaves (winner branch B has bright white-haloed leaves). Scene 2: **side-by-side CoT-chain-vs-ToT-tree SVG diagram** with VS divider + summary tags. Scene 3: **sequenced reveal** — 3 cards pop in one at a time with letter-badge + score pops, then losers dim/desaturate and winner B scales up with 60px glow, then verdict callout drops in |

### YouTube Shorts

**Title:**
```
ChatGPT Thinks Deeper When You Use This Prompting Method
```

**Description:**
```
"Think step by step" is good. Tree of Thought prompting is better. Instead of one reasoning path, you force ChatGPT to explore multiple approaches — weigh the pros and cons — then commit to the best one. The output quality on complex decisions jumps noticeably.

This is called Tree of Thought prompting, and it's the upgrade from chain-of-thought. Works on ChatGPT, Claude, and Gemini for strategy, decisions, and anything with multiple valid options.

│ tree of thought prompting │ ChatGPT advanced prompts │ chain of thought vs tree of thought │ how to use ChatGPT │ prompt engineering techniques │ ChatGPT for decisions │ AI reasoning │ AI tools 2026 │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #TreeOfThought #ChainOfThought #AIhacks #productivity #tech #LearnAI #YouTubeShorts
```

**Pinned comment:**
```
The ToT prompt I use: "Explore 3 different approaches. Evaluate each. Then recommend the best one and explain why." What decision would you run this on? 👇
```

### Instagram Reels

**Caption:**
```
The upgrade from "think step by step" — Tree of Thought prompting 🌳

Save this 🔖 — the exact prompt structure that makes ChatGPT explore every option before it answers.
```

**Hashtags:**
```
#ChatGPT #PromptEngineering #AIhacks #AItools #TreeOfThought #productivity #LearnAI
```

### TikTok

**Caption:**
```
This beats chain-of-thought every time on complex questions 🌳 What decision would you test it on? 👇
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #TechTok #productivity
```

### Thumbnails (use `thumbnail-generator-v4.html`)

**Primary — for Variant A:**
- Icon: 🌳  ·  Scheme: Lime
- L1: `CHAIN OF THOUGHT` — Lime / MD
- L2: `IS GOOD` — White / XL
- L3: `THIS IS BETTER` — Lime / LG

**Backup — for Variant B (canvas / app-chrome):**
- Icon: 🧠  ·  Scheme: Lime
- L1: `3 APPROACHES` — Lime / MD
- L2: `AT ONCE` — White / XL
- L3: `1 WINNER` — Lime / LG

**Alt — for Variant C (tree art):**
- Icon: 🌲  ·  Scheme: Lime
- L1: `WALK EVERY` — Lime / MD
- L2: `PATH FIRST` — White / XL
- L3: `THEN COMMIT` — Lime / LG

### Build changes / notes

- **Series callback in V16A:** "Chain of Thought is good. Tree of Thought is better." hook calls back to V3 of the series (CoT) — Vol 1 viewers get the upgrade narrative for free
- **V16B app-chrome distinctiveness:** chose **Whimsical/Miro-style infinite canvas** with dot-grid background, AI prompt overlay, zoom indicator, and toolbar with "★ AI Branch" tool — different from V12B (settings modal), V13B (chat windows), V14B (Playground sidebar), V15B (Notion doc)
- **V16B scene 2 — CoT contrast:** the canvas switches to "CoT MODE" (dim red badge, AI dot turns red) and shows a **linear chain** of nodes locking into the wrong answer (A · Paid Ads), so scene 3's branching ToT tree visibly beats it. User feedback: scene 2 originally just showed root-node alone, didn't communicate CoT's linearity
- **V16C scene 2 iteration:** originally a text-heavy notebook page with empty space below. Rebuilt as a **side-by-side SVG diagram** — CoT linear chain on left vs ToT branching tree on right, with VS divider, summary tags, and the prompt template callout
- **V16C scene 3 winner-pop sequencing:** user requested each branch pop in one at a time with its evaluation, then the winner pop out visually. Implemented:
  - Each card slides in (t=14.0 / 14.85 / 15.7) with staggered letter-badge + score pops
  - At t=16.9 the **losers A and C dim to 35% opacity + desaturate**, winner B scales to 1.08x with a 60px lime glow
  - At t=17.2 B's "9.2" score number flashes with text-shadow glow
  - Verdict callout drops in at t=17.8 with bounce
- **Acceptable false positives:** All 3 variants have the recurring dark-text-on-lime-button warnings (the `★ AI RECOMMENDS` verdict box, the winner badge "B", SVG `<text>` on lime-fill rects). Same sampling pattern accepted across V12-V15
- **Hyperframes:** all three on 0.6.20

### Posting cadence (per strategy doc)

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily (this one in rotation), 7-9am or 7-9pm EST

---

## Video 17 · Persona Depth

**Status:** ✅ Shipped — all 3 variations rendered
**Topic:** The 5-layer persona upgrade — Role / Context / Experience / Style / Constraints
**Color scheme:** 🔵 Blue (`#38BDF8`)
**Blog post:** [`Go_Live/ai-prompting/27-persona-depth.html`](Go_Live/ai-prompting/27-persona-depth.html)

### Renders

| Variant | File | Runtime | Size | Hook angle | Visual |
|---|---|---|---|---|---|
| A | [`17-persona-depth.mp4`](Videos/AI_Prompt_Engineering_Vol2/17-persona-depth/17-persona-depth.mp4) | 37s | 6.3 MB | V1 callback — "That was just the intro" | WEAK vs STRONG comparison + 5-layer anatomy with live persona builder + 3 template cards (Investor/Editor/UX Critic) |
| B | [`17b-persona-depth.mp4`](Videos/AI_Prompt_Engineering_Vol2/17-persona-depth/17b-persona-depth.mp4) | 37s | 7.3 MB | "I built my AI a real biography" | **persona.app — LinkedIn-style profile builder**. Hero shows fully-built Mira Reyes profile with 5/5 layers. Scene 2: **Anatomy/Template mode** — 5 layer sections each with question + 3 example chips + ★ WHY explanation + SKIP warning. Scene 3: **Library view** — 3 stacked persona cards (Investor / Editor / UX Critic) each with quote + 5-row layer summary + ★ SIGNATURE traits + use-case + ↗ PASTE button |
| C | [`17c-persona-depth.mp4`](Videos/AI_Prompt_Engineering_Vol2/17-persona-depth/17c-persona-depth.mp4) | 37s | 10 MB | "Generic role → Generic answer" | Illustrated blueprint aesthetic. Scene 1: **3×2 grid** comparing generic experts (Finance/Writing/Design ?) vs filled personas ($/✎/◐). Scene 2: **Character sheet** with 5 numbered rows + rich detail paragraphs per layer. Scene 3: **3 detailed dossiers** with italic quote + 2×2 detail grid (EXP/CONTEXT/STYLE/CONS) + ★ SIGNATURE row |

### YouTube Shorts

**Title:**
```
"Act as an Expert" Is Weak — ChatGPT Responds to This Instead
```

**Description:**
```
Giving ChatGPT a job title is the starting point, not the finish line. The output difference between "act as a marketing expert" and a fully-built biographical persona — with context, track record, working style, and communication constraints — is not subtle. It's the difference between a generic answer and one that sounds like it came from someone who's actually done the work.

This is the upgrade from basic role prompting. Works on ChatGPT, Claude, and Gemini.

│ ChatGPT persona prompting │ role prompting upgrade │ how to use ChatGPT │ ChatGPT expert mode │ better AI outputs │ prompt engineering advanced │ ChatGPT for work │ AI tools 2026 │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #PersonaPrompting #ChatGPTTips #AIhacks #productivity #tech #LearnAI #YouTubeShorts
```

**Pinned comment:**
```
The 5 elements of a strong persona: 1) Role 2) Organization/context 3) Experience volume 4) Working style 5) Constraints. Which one do you skip most? 👇
```

### Instagram Reels

**Caption:**
```
"Act as an expert" gives you a generic answer. This gives you an expert answer 🎭

Save this 🔖 — the 3 full persona templates (Investor, Editor, UX Critic) you can paste in today.
```

**Hashtags:**
```
#ChatGPT #PromptEngineering #AIhacks #AItools #PersonaPrompting #productivity #LearnAI
```

### TikTok

**Caption:**
```
"Act as an expert" is weak — here's what a real persona looks like 🎭 Which of the 3 templates would you use first? 👇
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #TechTok #productivity
```

### Thumbnails (use `thumbnail-generator-v4.html`)

**Primary — for Variant A:**
- Icon: 🎭  ·  Scheme: Blue
- L1: `"AN EXPERT"` — Blue / MD
- L2: `IS WEAK` — White / XL
- L3: `5 LAYERS WIN` — Blue / LG

**Backup — for Variant B (persona.app / library angle):**
- Icon: 👤  ·  Scheme: Blue
- L1: `BUILD AI` — Blue / MD
- L2: `A BIOGRAPHY` — White / XL
- L3: `5 LAYERS` — Blue / LG

**Alt — for Variant C (character sheet / dossier angle):**
- Icon: 📋  ·  Scheme: Blue
- L1: `GENERIC ROLE` — Blue / MD
- L2: `GENERIC ANSWER` — White / XL
- L3: `BUILD A REAL PERSON` — Blue / LG

### Build changes / notes

- **Series callback in V17A:** "V1 taught you to give AI a job title — that was just the intro." mirrors V16A's CoT → ToT callback. Builds series continuity for return viewers
- **V17B app-chrome — persona.app:** chose a **LinkedIn-style profile builder** with cover photo + avatar + section cards (Role/Context/Experience/Style/Constraints) — distinct from V12-V16 apps (settings/chat/playground/doc/canvas)
- **V17B scene 2 iteration:** original showed a half-empty "Marketing Expert" profile (1/5 layers). User flagged this didn't match VO context. Rebuilt as **Anatomy/Template mode** — each layer section now teaches the layer's purpose with question + examples + ★ WHY box + SKIP warning. Toolbar switches to "Template" tab + "★ ANATOMY MODE" indicator
- **V17B scene 3 iteration:** original showed one Mira Reyes profile being built. User flagged VO3 mentions "3 personas" but only 1 shown. Rebuilt as **Library view** — 3 persona cards stacked, each with quote + 5-row layer summary + signature traits + use-case label + ↗ PASTE button. Toolbar switches to "Library" tab
- **V17C scene 1 iteration:** original was 2 side-by-side dossier cards. User wanted **3×2 grid** matching scene 3 personas. Rebuilt as 6 cards in 3 rows × 2 cols — each row pairs a generic role (Finance/Writing/Design expert with dashed ? silhouette) with the corresponding filled persona ($/✎/◐). Card style mirrors the reference image (centered avatar + 5-field table)
- **V17C scene 2 enrichment:** each of the 5 character-sheet rows now has a full descriptive paragraph (3-4 sentences) with **bold emphasized phrases** + italic quote callouts. Each layer reads like a real personality dossier
- **V17C scene 3 enrichment:** each dossier card now has italic voice-quote + 2×2 detail grid + ★ SIGNATURE row with 3 trait phrases. Each dossier reads like a hireable real person
- **Acceptable false positives:** All variants have the recurring dark-text-on-blue-button warnings (PASTE button, verify checkmarks, EXPORT ALL) — same pattern accepted across V12-V16
- **Hyperframes:** all three on 0.6.20

### Posting cadence (per strategy doc)

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily (this one in rotation), 7-9am or 7-9pm EST

---

## Video 18 · Prompt Templates

**Status:** ✅ Shipped — all 3 variations rendered
**Topic:** Prompts are like mad libs — build the structure once, fill the blanks forever
**Color scheme:** 🟢 Lime (`#84E000`)
**Blog post:** [`Go_Live/ai-prompting/28-prompt-templates.html`](Go_Live/ai-prompting/28-prompt-templates.html)

### Renders

| Variant | File | Runtime | Size | Hook angle | Visual |
|---|---|---|---|---|---|
| A | [`18-prompt-templates.mp4`](Videos/AI_Prompt_Engineering_Vol2/18-prompt-templates/18-prompt-templates.mp4) | 37s | 6.5 MB | "Stop typing the same prompts every day — hours wasted" | Hours-wasted stat card + daily prompt rows in scene 1. Scene 2: template anatomy with 6 fills + filled preview + AI output panels. Scene 3: **Library of 8 templates** built from the `ai_prompt_template_pack.html` source — each card has icon, name, keyboard shortcut, multi-line body, fill EG row with concrete values |
| B | [`18b-prompt-templates.mp4`](Videos/AI_Prompt_Engineering_Vol2/18-prompt-templates/18b-prompt-templates.mp4) | 37s | 5.5 MB | "What a prompt library app would look like — prompts.app mockup" | **prompts.app — Library app chrome mockup** (the app is the visual aesthetic, not a real product). Hero shows search bar + titlebar with ★ 4 SAVED badge. Scene 2: **Anatomy/Template mode** — single template torn open with 4 var-tag chips + ★ WHY callouts + filled preview + AI output panel. Scene 3: **Library view** — 4 detailed library cards (Cold Email / Social Caption / Research Summary / Meeting Agenda) each with WHEN-to-use strip + full multi-line prompt + FILL EG + ↪ AI OUTPUT preview + 💡 tip |
| C | [`18c-prompt-templates.mp4`](Videos/AI_Prompt_Engineering_Vol2/18-prompt-templates/18c-prompt-templates.mp4) | 37s | 6.5 MB | "Prompts are like mad libs — fill the blanks forever" | Dark digital **lesson-page worksheet** aesthetic. Each scene has "★ LESSON 18 · Page X / 5" paginated header + footer + glowing lime side-rail pins. Scene 1: mad-libs worksheet with **5 blanks that ink-in one at a time** (cold email · launch demo · direct · SaaS founders · 10+ yrs experience) + AI Output preview card. Scene 2: bracket formula `[FORMAT][TOPIC][TONE][AUDIENCE]` + 4 pinned var cards + AI Output. Scene 3: **3 molds** (Cold Email / Social Hook / Research Brief) each with mini AI Output block inside. Scene 4: glowing lime "Build once · Use forever" stamp. Scene 5: 3-step homework checklist that ticks itself off. **Slide-page transitions** between scenes |

### YouTube Shorts

**Title:**
```
Stop Typing the Same ChatGPT Prompt — Build It Once, Use It Forever
```

**Description:**
```
You're typing the same kind of prompt 50 times a week. Cold emails, social captions, research summaries, meeting agendas. Each one rebuilt from scratch. The fix is the oldest writing trick in the book: mad libs. Build a template with brackets — [topic], [tone], [audience], [format] — fill the blanks in 10 seconds, send it. The 4 templates in this video cover most of what knowledge workers prompt every day. Steal them.

Works on ChatGPT, Claude, and Gemini.

│ ChatGPT templates │ prompt templates │ AI prompts library │ ChatGPT shortcuts │ better AI outputs │ prompt engineering basics │ ChatGPT for work │ AI tools 2026 │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #PromptTemplates #ChatGPTTips #AIhacks #productivity #tech #LearnAI #YouTubeShorts
```

**Pinned comment:**
```
The 4 starter templates: 1) Cold email 2) Social hook 3) Research brief 4) Meeting agenda. Which one would save you the most time this week? 👇
```

### Instagram Reels

**Caption:**
```
You're typing the same prompts 50x a week — and you don't even know it 📋

Save this 🔖 — 4 templates you can fill in 10 seconds and re-use forever.
```

**Hashtags:**
```
#ChatGPT #PromptEngineering #AIhacks #AItools #PromptTemplates #productivity #LearnAI
```

### TikTok

**Caption:**
```
Prompts are mad libs 📋 fill the blanks, send it, done. Which of the 4 templates would you steal first? 👇
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #TechTok #productivity
```

### Thumbnails (use `thumbnail-generator-v4.html`)

**Primary — for Variant A:**
- Icon: 📋  ·  Scheme: Lime
- L1: `STOP TYPING` — Lime / MD
- L2: `THE SAME PROMPT` — White / XL
- L3: `BUILD ONCE` — Lime / LG

**Backup — for Variant B (prompts.app / library angle):**
- Icon: 📁  ·  Scheme: Lime
- L1: `BUILD A` — Lime / MD
- L2: `PROMPT LIBRARY` — White / XL
- L3: `4 TEMPLATES` — Lime / LG

**Alt — for Variant C (mad libs / worksheet angle):**
- Icon: ✏️  ·  Scheme: Lime
- L1: `PROMPTS ARE` — Lime / MD
- L2: `MAD LIBS` — White / XL
- L3: `FILL FOREVER` — Lime / LG

### Build changes / notes

- **V18A scaffold:** built around the **8-template prompt pack** from `/Users/titanstower/Downloads/ai_prompt_template_pack.html` — each template kept its source styling (icon + cat + multi-line prompt box + var-tag styled brackets + lightbulb tip). Scene 1 leads with a **wasted-time stat card** ("2.5 hours/week typing same prompts") + 6 daily prompt rows
- **V18B app-chrome — prompts.app:** chose a **library app with sidebar + search + titlebar** to distinguish from V17B's LinkedIn-style persona.app. Sidebar shows 4 category icons + USAGE block (47 this quarter · ⌘↵ avg send). Scene 2 acts as a "single-template anatomy mode" with the template torn open showing the 4 brackets
- **V18B reduced from 8 → 4 templates** to match VO3's "Four template categories" line. Each card grew from compact list item to 5-section rich card (WHEN / prompt / FILL EG / ↪ AI OUTPUT / 💡 tip) filling the freed vertical space
- **V18C heavy iteration cycle:**
  1. First built as dark digital **8-blueprint diagram cards** with FILL EG + corner tags + metric badges → user flagged "too similar to V18A"
  2. **Total creative pivot** to **handwritten paper Mad Libs worksheet** aesthetic — cream `#F4EBD0` background, navy ink, yellow highlighter, red rubber stamps, punched binder holes, paper-flip slide transitions, paginated worksheet headers
  3. Added a **5th blank** to S1 madlib for "10+ yrs experience" + AI Output preview blocks on every scene's cards (S1 full, S2 full, S3 mini per mold)
  4. User said "I like the style but go back to digital dashboard" → **ported worksheet structure to dark digital** — kept lesson-page format, page-flip transitions, mad-libs blanks, 3 named molds, homework checklist — but swapped cream paper → `#0A0C0A`, navy ink → white, yellow highlighter → lime, punched holes → glowing lime pin-dots
- **VO match audit:** transcribed all 5 VOs with whisper to verify content. VO3 says **"3 template molds, cold email, social hook, research brief"** — V18C now shows exactly 3 molds with those names in that order, sliding in at 14.0s / 15.0s / 16.0s to match VO pacing
- **Acceptable false positives:** All variants have dark-text-on-lime-button warnings (★ SAVED badges, var-tag styled brackets, ★ STARTER PACK chips, ⏱ 10s stamps) — same pattern accepted across V11-V17
- **Hyperframes:** all three on 0.6.20

### Posting cadence (per strategy doc)

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily (this one in rotation), 7-9am or 7-9pm EST

---

## Video 19 · Multimodal Prompting

**Status:** ✅ Shipped — all 3 variations rendered
**Topic:** AI can see now — stop typing 5-paragraph prompts, drop an image instead
**Color scheme:** 🔵 Blue (`#38BDF8`)
**Blog post:** [`Go_Live/ai-prompting/29-multimodal-prompting.html`](Go_Live/ai-prompting/29-multimodal-prompting.html)

### Renders

| Variant | File | Runtime | Size | Hook angle | Visual |
|---|---|---|---|---|---|
| A | [`19-multimodal-prompting.mp4`](Videos/AI_Prompt_Engineering_Vol2/19-multimodal-prompting/19-multimodal-prompting.mp4) | 37s | 7.5 MB | "AI can see now — show, don't tell" | WEAK vs STRONG **comparison cards** (text-only @ ~340 tokens / 40% accuracy / 3-5× iterations / ~8m time vs multimodal @ ~18 tokens / 95% accuracy / 1× iteration / ~15s time), each with AI-result snippet + 4-tile stats grid + follow-ups footer. Bottom verdict band: `8m / 5-para essay` vs `15s / 1 image + 1 line`. Scene 2: formula `[Text] + [Image] = [Rich answer]` + 3 input cards (Sketch / Screenshot / Photo) each with example sentence + ⏱ 10s stamp + proof block "what each input unlocks". Scene 3: 3 use-cards (UI / CODE / EAT). Scene 4: ★ MULTIMODAL LAW principle (340 vs 18 tokens) |
| B | [`19b-multimodal-prompting.mp4`](Videos/AI_Prompt_Engineering_Vol2/19-multimodal-prompting/19b-multimodal-prompting.mp4) | 37s | 5.7 MB | "What multimodal looks like in a real chat app — vision.chat mockup" | **vision.chat — Mac-app chat workspace mockup** (the app is the visual aesthetic, not a real product). Sidebar with "+ New chat" + Today/Yesterday recents (dashboard copy fix · napkin→React · whiteboard→notes · etc.) + Alex·Pro user pill. Scene 1 chat thread: user attaches `dashboard-v3.png` + "rewrite to feel conversational, match the illustration warmth" → AI replies w/ headline + button + "matched sage-green" → user "Perfect. Ship it." → **AI delivers full rendered solution-preview card** (cream/sage dashboard mock with `✓ SHIPPED · v3.1` lime stamp + `Good to see you again, Alex.` headline + sage CTA button + `+42% warmth / +18% CTR projected` diff line). Scene 2 composer-anatomy: text card + image drop card + AI output + ⌘+V shortcut + **before/after live preview** (dark cold "Hi there!/Submit" vs warm sage "Good to see you again, Alex./Let's pick up where you left off →"). Scene 3 Library view: 3 saved chats (UI / CODE / EAT) each w/ thumb + prompt + AI output + ⏱ 10s stamp |
| C | [`19c-multimodal-prompting.mp4`](Videos/AI_Prompt_Engineering_Vol2/19-multimodal-prompting/19c-multimodal-prompting.mp4) | 37s | 9.2 MB | "Page of text vs page with image — one wins" | Dark digital **lesson-page worksheet** aesthetic (★ LESSON 19 paginated header/footer + glowing blue rail pins + blueprint grid bg). Scene 1: **Two illustrated document SVGs** — LEFT shows a page of 13+ text lines + closed-eye-with-X badge (VISION OFF), RIGHT shows a page with an actual landscape image (sun + 5-peak mountain photo + filename tag) + glowing open-eye badge w/ 5 emanating light rays (VISION ON). Both with stats blocks below. Scene 2: **SVG flow pipeline** — speech-bubble TEXT node + photo-frame IMAGE node (sun + mountains landscape) merging down via dashed curves into 70px AI BRAIN circle w/ big open eye + arrow down to lime output pill. Plus 3 input SVG cards (pencil-sketch / mini-UI w/ cursor / camera). Scene 3: 3 illustrated use-cases each w/ left input SVG → flow text → right rendered output SVG. Scene 4: side-by-side illustrated math (8 text lines vs 1 photo card). **Slide-page transitions** between scenes |

### YouTube Shorts

**Title:**
```
Stop Typing 5-Paragraph Prompts — Drop an Image Instead
```

**Description:**
```
You're typing a paragraph to describe what's on your screen when ChatGPT could just look at it. Drag the screenshot, type one line, ship. The math: ~340 tokens of essay vs ~18 tokens + one image. ~40% accuracy vs ~95%. Three to five iterations vs one. This is the upgrade most people are still skipping in 2026 — and it's the cheapest one to make. Works on ChatGPT, Claude, and Gemini, all of which now read images, sketches, and photos as natively as text.

Three use cases: screenshot a UI to rewrite the copy, sketch a feature to get the code, photo your fridge for dinner ideas.

│ ChatGPT multimodal │ ChatGPT vision │ AI image prompting │ ChatGPT screenshot trick │ Claude vision │ Gemini multimodal │ prompt engineering advanced │ AI tools 2026 │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #MultimodalAI #ChatGPTVision #AIhacks #productivity #tech #LearnAI #YouTubeShorts
```

**Pinned comment:**
```
3 multimodal templates: 1) Screenshot a UI → rewrite the copy 2) Sketch a feature → working code 3) Photo your fridge → dinner ideas. Which one are you trying tonight? 👇
```

### Instagram Reels

**Caption:**
```
You're typing 5-paragraph prompts when AI can just *look* 👁

Save this 🔖 — 3 multimodal templates you can paste an image into tonight.
```

**Hashtags:**
```
#ChatGPT #PromptEngineering #AIhacks #AItools #MultimodalAI #ChatGPTVision #productivity #LearnAI
```

### TikTok

**Caption:**
```
Stop typing essays — AI can see your screen now 👁 3 ways to use vision tonight. Which one are you trying? 👇
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #TechTok #productivity
```

### Thumbnails (use `thumbnail-generator-v4.html`)

**Primary — for Variant A:**
- Icon: 👁  ·  Scheme: Blue
- L1: `STOP TYPING` — Blue / MD
- L2: `AI CAN SEE` — White / XL
- L3: `DROP THE IMG` — Blue / LG

**Backup — for Variant B (vision.chat / app angle):**
- Icon: 📎  ·  Scheme: Blue
- L1: `INSIDE` — Blue / MD
- L2: `A VISION CHAT` — White / XL
- L3: `1 IMG · 1 LINE` — Blue / LG

**Alt — for Variant C (diagram / blueprint angle):**
- Icon: 🧠  ·  Scheme: Blue
- L1: `1 IMAGE >` — Blue / MD
- L2: `1,000 TOKENS` — White / XL
- L3: `THE PIPELINE` — Blue / LG

### Build changes / notes

- **Scaffold pattern:** cloned V18A directory → V19A then V19B/V19C, replaced `meta.json` / `package.json` / `index.html`, generated 5 fresh VOs with Kokoro `am_adam` (3.7s / 4.7s / 6.5s / 2.7s / 3.6s = ~21s total speech with ~2s gaps, bgm 0.15 with 3.5s power2.in fade ending @ 33.5s per memory)
- **V19A iteration — fill white space:** initial render had ~600px empty below comparison cards in S1 and ~1200px below the 3 input cards in S2. Grew cmp-card min-height 480 → 920, added 4-tile stats grid + AI-result snippet to each card, added bottom verdict band `8m vs 15s`. S2: grew input-card min-height to 360 + added ic-num/ic-eg/⏱ 10s stamps + new "★ WHAT EACH INPUT UNLOCKS" proof block
- **V19B app-chrome — vision.chat:** chose a **Mac-style chat workspace** (sidebar of recent multimodal chats + thread w/ image-attachment chips + composer w/ paperclip / image / send buttons + composer hint row) to distinguish from V18B's library and V17B's profile builder. Vision badge "★ 1 IMG · 1 LINE" in titlebar
- **V19B S1 iteration:** original thread (3 messages) left ~800px empty below "Perfect. Ship it.". Added a 4th AI message containing a **full rendered solution preview** — cream/sage dashboard mock with `✓ SHIPPED · v3.1` lime stamp + sage-green CTA button + `Δ vs old copy +42% warmth · +18% CTR projected` diff line. Drops in @ 3.35s
- **V19B S2 iteration:** composer-stage had ~780px empty below the shortcut card. Added **`.live-preview` block w/ before/after dashboard mocks** — cold/blue "Hi there! / Submit" (text-only result) → arrow → warm/sage "Good to see you again, Alex. / Let's pick up where you left off →" (multimodal result), capped with verdict "+42% warmth · +18% CTR projected"
- **V19B S2 layout fix:** initial side-by-side `cs-formula` grid overflowed by 22px due to GSAP `x: -40 / x: 40` initial transforms pushing cards outside their grid track. Switched to vertical stack (text → `+` → image) and replaced x-tweens with y-tweens
- **V19C iteration — clearer SVG illustrations:** user flagged S1 brain blobs and S2 flow diagram were too abstract. Redrew S1 brains as **documents-showing-what-AI-processes**: LEFT = page with 13+ text lines + closed-eye-with-X badge (VISION OFF), RIGHT = page with actual sun + 5-peak mountain landscape inside + glowing open-eye badge with 5 light rays (VISION ON). Redrew S2 flow with speech-bubble TEXT (with chat tail), photo-frame IMAGE (sun + mountains), bigger 70px AI BRAIN circle + 80px glow halo + big open eye + larger output pill (`RICH · CONTEXT-AWARE ANSWER` at font-size 14, letter-spacing 3)
- **Acceptable false positives:** All 3 variants have dark-text-on-blue-button warnings (the lime ⏱ 10s stamps, ★ SHIPPED · v3.1 lime stamp on warm cream, badge pills, output pill) — same pattern accepted across V11-V18
- **Hyperframes:** all three on 0.6.20

### Posting cadence (per strategy doc)

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily (this one in rotation), 7-9am or 7-9pm EST

---

## Video 20 · Prompt Triage

**Status:** ✅ Shipped — all 3 variations rendered · **Vol 2 finale**
**Topic:** Your prompt failed? Don't retry — triage it. 3 symptoms (vague / wrong format / missed context) → 3 fixes
**Color scheme:** 🔴 Red (`#EF4444`)
**Blog post:** [`Go_Live/ai-prompting/30-prompt-triage.html`](Go_Live/ai-prompting/30-prompt-triage.html)

### Renders

| Variant | File | Runtime | Size | Hook angle | Visual |
|---|---|---|---|---|---|
| A | [`20-prompt-triage.mp4`](Videos/AI_Prompt_Engineering_Vol2/20-prompt-triage/20-prompt-triage.mp4) | 37s | 7.8 MB | "Don't retry. Triage." | WEAK vs STRONG comparison: gray-bordered **★ Retry blind / ✗** card (5× rewordings of "Make it better" + 3 ✗ symptoms + AI guessing diagnosis + ~340 tokens / ~12m time burnt) vs red-bordered **★ Triage first / ✓** card with **★ THE 4-STEP PROTOCOL** block (Read → Diagnose → Patch → Ship) + 3 ✓ workflow steps + ~30s time. Bottom verdict: `12m / 5× rewordings + same bug` vs `30s / 1 diagnosis + 1 fix`. Scene 2: triage chart (3 symptom→fix rows) + **★ TRIAGE WORKFLOW** horizontal playbook + **★ STARTER LINES** quick-reference grid. Scene 3: 3 case-cards + **★ AI OUTPUT PROOF** with rendered table mock + **★ TRIAGE WIN** stats band (3 / 3 / 90s / 0). Scene 4: ★ TRIAGE LAW. Scene 5: Vol 2 wrapped finale band |
| B | [`20b-prompt-triage.mp4`](Videos/AI_Prompt_Engineering_Vol2/20-prompt-triage/20b-prompt-triage.mp4) | 37s | 5.3 MB | "What a prompt-diagnostic console would look like — triage.app mockup" | **triage.app — Mac-app code-review/linter mockup** (the app is the visual aesthetic, not a real product). Sidebar with "+ New triage" + Today/Yesterday ticket lists with **status icons** (red ✗ fail / green ✓ fixed / amber ⏵ pending). Scene 1 diagnostic flow: 4 dx-sections separated by hairlines — **★ Input** (bad prompt with **wavy red underlines** on flagged phrases) → **★ Diagnosis** (2 red flag rows with `+ FIX` buttons) → **★ Prescription** (cured prompt with green-highlighted added pieces) → **★ AI Output**. Scene 2: vertical symptom→fix chart inside app chrome with `⚑ FLAG` and `✚ APPLY` chips. Scene 3 Library: 3 saved triages (T-01/02/03 icon tiles + bad→cured + ⏱ 30s FIX stamps) + **★ THE CURE · AI OUTPUT PROOF** panel + **★ LIBRARY STATS** 4-tile grid (47 / 30s / 0 / 23m). Scene 4: Principle inside app chrome |
| C | [`20c-prompt-triage.mp4`](Videos/AI_Prompt_Engineering_Vol2/20-prompt-triage/20c-prompt-triage.mp4) | 37s | 10.2 MB | "Diagnostic blueprint — page of 5 retries vs page of 3 flags" | Dark digital **lesson-page worksheet** aesthetic (★ LESSON 20 paginated header/footer + glowing red rail dots + blueprint grid bg). Scene 1: **Two illustrated diagnostic page SVGs** — LEFT shows 5 angle-rotated `RETRY 1-5` stamps stacked chaotically + big X seal + `BLIND` label, RIGHT shows 3 red `⚑` flag rows with `✓ FIX` chips + green arrow + glowing green check seal + `TRIAGED` label. Scene 2: **Full triage decision flowchart SVG** (500px) — BAD OUTPUT → 3 red dashed branches to symptom nodes → 3 green arrows down to fix nodes → merge curves down to green SHIP pill. Plus **★ THE 4-STEP PROTOCOL** + **★ STARTER LINES** grid. Scene 3: 3 illustrated use-blueprints each w/ unique input SVG (squiggle-underline doc / wall-of-text / `?` page) → fix text → unique output SVG (text-rendered specific result / mini 2×4 markdown table / 4-numbered-step-bubble flow). Scene 4: side-by-side illustrated math (5 chaotic retry stamps vs 1 big ★ DIAGNOSED stamp). Scene 5: ★ HOMEWORK red stamp + 3-step ticking checklist + **★ VOL 2 · WRAPPED · 20 LESSONS SHIPPED · THANK YOU** finale band. **Slide-page transitions** between scenes |

### YouTube Shorts

**Title:**
```
Your ChatGPT Reply Was Bad — Don't Retry, Triage It
```

**Description:**
```
You're 5 retries deep on the same prompt and still getting garbage. Stop. The fix isn't another reword — it's a diagnosis. Three symptoms cover ~90% of failed AI replies: vague output, wrong format, missed context. Each one has exactly one fix: add specifics, name the shape, or paste the source. One diagnosis, one re-prompt, 30 seconds. Beats the 12-minute retry spiral every time.

The triage chart in this video is the closer to a 20-video series on prompt engineering. Save it. Use it tonight.

│ ChatGPT triage │ prompt engineering debug │ AI prompt fixes │ ChatGPT retry │ AI prompt diagnosis │ better AI outputs │ ChatGPT for work │ AI tools 2026 │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #PromptTriage #ChatGPTTips #AIhacks #productivity #tech #LearnAI #YouTubeShorts
```

**Pinned comment:**
```
The 3-symptom chart: 1) Vague → + specifics 2) Wrong format → + shape 3) Missed context → + source. Which one trips you up most? 👇 (And: this is the last video of Vol 2 — Vol 1 + Vol 2 = 30 lessons total. Thanks for watching 🙏)
```

### Instagram Reels

**Caption:**
```
Stop retrying the same prompt 5 times 🛑

Save this 🔖 — the 3-symptom triage chart that fixes 90% of bad AI replies in one re-prompt.
```

**Hashtags:**
```
#ChatGPT #PromptEngineering #AIhacks #AItools #PromptTriage #productivity #LearnAI
```

### TikTok

**Caption:**
```
Don't retry — triage 🩺 3 symptoms, 3 fixes, 30 seconds. Which one trips you up? 👇 (Final video of Vol 2!)
```

**Hashtags:**
```
#ChatGPT #AItools #PromptEngineering #TechTok #productivity
```

### Thumbnails (use `thumbnail-generator-v4.html`)

**Primary — for Variant A:**
- Icon: 🩺  ·  Scheme: Red
- L1: `DON'T RETRY` — Red / MD
- L2: `TRIAGE IT` — White / XL
- L3: `3 SYMPTOMS · 3 FIXES` — Red / LG

**Backup — for Variant B (triage.app / console angle):**
- Icon: ⚑  ·  Scheme: Red
- L1: `INSIDE` — Red / MD
- L2: `A TRIAGE CONSOLE` — White / XL
- L3: `DIAGNOSE · FIX · SHIP` — Red / LG

**Alt — for Variant C (blueprint / flowchart angle):**
- Icon: 🗺️  ·  Scheme: Red
- L1: `5 RETRIES BLIND` — Red / MD
- L2: `VS 1 DIAGNOSIS` — White / XL
- L3: `THE TRIAGE CHART` — Red / LG

### Build changes / notes

- **Scaffold pattern:** cloned V19A directory → V20A then V20B/V20C, replaced `meta.json` / `package.json` / `index.html`, generated 5 fresh VOs with Kokoro `am_adam` (2.9s / 5.9s / 5.5s / 1.4s / 3.9s = ~19.5s total speech, bgm 0.15 with 3.5s power2.in fade ending @ 33.5s per memory)
- **V20A iteration — beef up "what to do":** initial Scene 1 had a single one-liner *"Read the bad output → pick the symptom → apply the matching fix → ship."*. Expanded into **★ THE 4-STEP PROTOCOL** block with red-stamped number badges + verb + detail per step (Read · Diagnose · Patch · Ship)
- **V20A iteration — fill S2 white space:** added **★ TRIAGE WORKFLOW** (horizontal 4-step playbook with glyphs ⌕/⚑/✚/↑ + per-step timing ~5s/~5s/~10s/~10s) + **★ STARTER LINES** quick-reference grid (3 rows: Vague/Format/Context with bad ✗ vs good ✓ comparison)
- **V20A iteration — fill S3 white space:** added **★ THE CURE · AI OUTPUT PROOF** (3 result blurbs including a rendered 2×3 markdown table mock) + **★ TRIAGE WIN** aggregate stats band (3 diagnoses · 3 re-prompts · 90s · 0 retry chains). Fixed 3px overflow on `.tw-stat` by adding `padding: 6px 0`
- **V20B app-chrome — triage.app:** chose a **Mac-app code-review/linter mockup** (sidebar with ticket statuses + main panel with 4 dx-sections — Input/Diagnosis/Prescription/AI Output — separated by hairlines) to distinguish from V19B's vision.chat and V18B's prompts.app. The bad prompt block has **wavy red underlines** on flagged phrases like `something good`, `punchy`, `professional`, `people`. The cured prompt has green-highlighted added pieces
- **V20B iteration — fill S3 library white space:** added **★ THE CURE · AI OUTPUT PROOF** (3 ap-rows with T-0X red stamps + green-bordered italic outputs including an actual mini-rendered 2×3 markdown table) + **★ LIBRARY STATS** 4-tile grid (47 / 30s / 0 / 23m). Bottom status updated to `★ Library: 3 templates · all keyboard-mapped · 23m saved/wk`
- **V20C iteration — fill S2 flowchart white space:** added the same **★ THE 4-STEP PROTOCOL** + **★ STARTER LINES** panels as V20A but styled in V20C's blueprint/worksheet aesthetic (dashed red borders, red dot indicators, paginated header consistency)
- **Vol 2 finale touches:** all 3 variants close with **★ VOL 2 · WRAPPED · 20 LESSONS SHIPPED** band on Scene 5. V20A/B use a glowing red rounded band, V20C uses the lesson-page footer "Lesson 20 · Homework · Vol 2 Finale" + finale tag "thank you"
- **Acceptable false positives:** All 3 variants have dark-text-on-red-stamp warnings (the ⏱ 30s FIX stamps, T-0X tags, ★ HOMEWORK stamp, wh-badge `Lesson 20`) — same pattern accepted across V11-V19
- **Hyperframes:** all three on 0.6.20

### Posting cadence (per strategy doc)

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily (this one in rotation), 7-9am or 7-9pm EST
- **Bonus:** post the **Vol 2 wrap montage** (60-second recap of all 20 lessons) the week after V20 ships

---

## Output locations

- **Videos:** `/Users/titanstower/Documents/Projects/AI_BlogSite/Videos/AI_Prompt_Engineering_Vol2/`
- **Blog posts:** `/Users/titanstower/Documents/Projects/AI_BlogSite/Go_Live/ai-prompting/`
- **Thumbnails generator:** [`/Users/titanstower/Documents/Projects/AI_BlogSite/thumbnail-generator-v4.html`](thumbnail-generator-v4.html)
- **Blog template:** [`/Users/titanstower/Documents/Projects/AI_BlogSite/blog-post-template.html`](blog-post-template.html)
- **Strategy doc:** [`/Users/titanstower/Documents/Projects/AI_BlogSite/Prompt Files/ai-prompting-series-content-strategy-v3.md`](Prompt%20Files/ai-prompting-series-content-strategy-v3.md)
- **Hyperframes projects:** `/Users/titanstower/Documents/Projects/Trend_Analyzer/video{11..20}{,b,c}-{slug}/`
