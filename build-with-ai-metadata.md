# Build With AI Series · Vol 4 — Metadata Tracker

Channel: AIToolsDaily24 / Ryu Vy · IG @aitoolsdaily245 · TikTok @dj.bomasterflex · YouTube AIToolsDaily24
Series: **Build With AI** (videos 31–40) — "I built a real thing with AI, zero code." One script → 3 platform-native cuts (**A** YouTube dashboard · **B** Instagram app-chrome *hero* · **C** TikTok illustrated). Everything built in **Claude** (Artifacts; Projects for #35).
Theme rotation: lime / red / blue per video. Music credit (every platform): `Music from #InAudio: https://inaudio.org/  Infraction-Never-Leave-Short-Version.`

---

## Video 31 · Build an App

**Status:** ✅ Shipped — all 3 cuts rendered · **Build With AI opener**
**Topic:** Build a real, working app (an invoice maker) from one plain-English prompt in Claude — no code, no template.
**Color scheme:** 🟢 Lime (`#84E000`)
**Tool featured:** Claude (Artifacts)
**Blog post:** [`Go_Live/build-with-ai/31-build-an-app.html`](Go_Live/build-with-ai/31-build-an-app.html)

### Renders

| Variant | File | Runtime | Size | Platform | Hook angle | Visual |
|---|---|---|---|---|---|---|
| A | `31-build-an-app.mp4` | 37s | 2.7 MB | YouTube | "I built a working app with one prompt — no code" | **Dashboard / stat-cards.** Hook → build spec (tool: Claude + 3 reqs: line items / auto-tax / export PDF) → build metrics (`1 prompt` / `0 lines you wrote` / `~90s` + progress bar) → result (`$1,620` total + 3 ✓ stat rows) → CTA |
| B | `31b-build-an-app.mp4` | 37s | 3.2 MB | Instagram | "One prompt. A real app. Zero code." | **Mock-app chrome (HERO).** One Claude artifact window evolving: composer (the prompt) → building (streaming code lines + progress bar) → the running invoice app (line items, tax, `$1,620` total, Export PDF) → CTA |
| C | `31c-build-an-app.mp4` | 37s | 3.8 MB | TikTok | "You can build an app now. Watch." | **Illustrated / native.** Dashed hand-drawn flow: scribble-underlined hook → ask bubble → dashed `Claude` node w/ sparkles → sketchy phone showing the invoice (`$1,620`) + "it works." scribble → CTA |

### YouTube (A)

**Title:**
```
I Built a Working App With One Prompt — No Code (Claude)
```

**Description:**
```
No code. No template. No course. I opened Claude, described an invoice maker in one plain-English sentence — add line items, calculate tax, export to PDF — and it built the whole thing. The code, the screens, the math. I touched nothing. Seconds later it's running: I add a line item, the total updates live, I export a real invoice.

This is video 1 of Build With AI — every episode I build a real, usable thing with AI and zero code, then show you exactly how. Save it, and build yours tonight.

│ build an app with AI │ no code app builder │ Claude artifacts │ build app one prompt │ AI app builder 2026 │ vibe coding │ build with AI │ invoice app │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#Claude #BuildWithAI #AItools #NoCode #vibecoding #AIapps #ClaudeAI #buildinpublic #LearnAI #YouTubeShorts
```

**Pinned comment:**
```
One sentence in Claude → a working invoice app (line items, auto-tax, PDF export) in seconds, zero code. What would you build first? 👇 (This kicks off Build With AI — a real thing built with AI every episode, no course required.)
```

### Instagram (B)

**Caption:**
```
I built a working invoice app in one prompt 🤯 no code, no template.

Save this 🔖 — then open Claude and build yours tonight. (Episode 1 of Build With AI 🛠️)
```

**Hashtags:**
```
#Claude #BuildWithAI #NoCode #AItools #vibecoding #AIapps #ClaudeAI #LearnAI #buildinpublic
```

### TikTok (C)

**Caption:**
```
one prompt → a real app, zero code 👀 built it in Claude in seconds. what would you build first? 👇 (ep 1 of Build With AI 🛠️)
```

**Hashtags:**
```
#Claude #BuildWithAI #NoCode #vibecoding #TechTok #AItools
```

### Thumbnails

**Hero — for Variant B (Instagram · app-chrome):**
- Icon: ⚡  ·  Scheme: Lime
- L1: `ONE PROMPT` — Lime / MD
- L2: `A REAL APP` — White / XL
- L3: `ZERO CODE · CLAUDE` — Lime / LG

**Primary — for Variant A (YouTube · dashboard):**
- Icon: 🛠️  ·  Scheme: Lime
- L1: `I BUILT AN APP` — Lime / MD
- L2: `IN ONE PROMPT` — White / XL
- L3: `NO CODE · CLAUDE` — Lime / LG

**Alt — for Variant C (TikTok · illustrated):**
- Image: `Assets/pexels/build-an-app-20694602.png` (smartphone + code, Pexels) — focal photo, replaces emoji  ·  Scheme: Lime
- L1: `YOU CAN BUILD` — Lime / MD
- L2: `AN APP NOW` — White / XL
- L3: `NO CODE · WATCH` — Lime / LG

### Build changes / notes

- **Production:** same VO across all 3 cuts (Kokoro `am_adam`, 5 beats: 4.1 / 7.6 / 4.5 / 5.7 / 6.7s ≈ 28.6s speech; BGM Infraction "Never Leave" @ 0.15). 5-scene 37s skeleton; scenes abut at 0 / 6 / 15 / 21 / 28.
- **Tool decision:** whole series built in **Claude** (Artifacts) — no competitor builders advertised. #31 demo = invoice maker.
- **Aesthetic map (swapped):** B app-chrome → Instagram (hero) · C illustrated → TikTok · A dashboard → YouTube.
- **0.7.x lint gotchas hit + fixed:** scene `data-duration` overlaps (abutted exactly); `-apple-system` not auto-resolved (dropped, `system-ui` only); unscoped multi-element gsap selectors (scoped with `#el-scene-N`); a stray top-level `<svg defs>` trips root detection → inline the marker inside its own arrow `<svg>`. All three lint-clean (0 errors).
- **Whisper smell test:** transcript ≈ 99% match to VO script (one mishear "Building"→"Making"; on-screen text + TTS input confirm "Building").
- **HyperFrames 0.7.17.** Video folder stripped to MP4-only (Vol 2 convention).

### Posting cadence

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily, 7-9am or 7-9pm EST
- **Series opener** — pin it on each platform; it's the front door to Build With AI.

---

## Video 32 · Build a Website

**Status:** ✅ Shipped — all 3 cuts rendered
**Topic:** Build a full landing page (a coaching site, "PeakForm") from one plain-English prompt in Claude — no Squarespace, no template, no code.
**Color scheme:** 🔵 Blue (`#38BDF8`)
**Tool featured:** Claude (Artifacts)
**Blog post:** [`Go_Live/build-with-ai/32-build-a-website.html`](Go_Live/build-with-ai/32-build-a-website.html)

### Renders

| Variant | File | Runtime | Size | Platform | Hook angle | Visual |
|---|---|---|---|---|---|---|
| A | `32-build-a-website.mp4` | 39s | 3.2 MB | YouTube | "I built a full website in 10 minutes with AI" | **Dashboard / stat-cards.** Hook → build spec (Claude + hero/services/CTA) → metrics (`1 prompt` / `0 lines` / `~10m` + progress) → result (PeakForm site preview in a browser card + 4 ✓ stats) → CTA |
| B | `32b-build-a-website.mp4` | 39s | 3.3 MB | Instagram | "From idea to a live site in one prompt." | **Browser-chrome (HERO).** One Claude window: composer (the prompt) → building (page skeleton assembling + progress) → the finished PeakForm landing page live in a browser (nav, hero, booking CTA, 3 service cards) → CTA |
| C | `32c-build-a-website.mp4` | 39s | 4.0 MB | TikTok | "A whole website in 10 minutes. No Squarespace." | **Illustrated / native.** Dashed flow: scribble-underlined hook → ask bubble → dashed `Claude` node w/ sparkles → sketchy dashed browser showing the live site + "it's live." scribble → CTA |

### YouTube (A)

**Title:**
```
I Built a Full Website in 10 Minutes With AI — No Code (Claude)
```

**Description:**
```
No Squarespace. No template. No code. I opened Claude, gave it my business in one line — a landing page for a coaching brand with a booking call-to-action — and it built the whole page: hero, services, copy, buttons. Section by section, while I watched. Seconds later it's a finished, styled, live site I can scroll.

Video 2 of Build With AI — every episode I build a real, usable thing with AI and zero code, then show you how. Save it, and build yours tonight.

│ build a website with AI │ no code website │ Claude artifacts │ website in 10 minutes │ AI website builder 2026 │ vibe coding │ landing page AI │ build with AI │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#Claude #BuildWithAI #AItools #NoCode #vibecoding #webdesign #ClaudeAI #buildinpublic #LearnAI #YouTubeShorts
```

**Pinned comment:**
```
One line in Claude → a full landing page (hero, services, booking CTA) in minutes, zero code. What would your site be for? 👇 (Build With AI — a real thing built with AI every episode.)
```

### Instagram (B)

**Caption:**
```
I built a full website in one prompt 🤯 no Squarespace, no template, no code.

Save this 🔖 — then open Claude and build yours tonight. (Episode 2 of Build With AI 🛠️)
```

**Hashtags:**
```
#Claude #BuildWithAI #NoCode #AItools #vibecoding #webdesign #ClaudeAI #LearnAI #buildinpublic
```

### TikTok (C)

**Caption:**
```
a whole website in one prompt 👀 no Squarespace. built it in Claude in minutes. what's your site for? 👇 (ep 2 of Build With AI 🛠️)
```

**Hashtags:**
```
#Claude #BuildWithAI #NoCode #vibecoding #TechTok #webdesign
```

### Thumbnails

**Hero — for Variant B (Instagram · browser-chrome):**
- Icon: 🪄  ·  Scheme: Blue
- L1: `IDEA TO SITE` — Blue / MD
- L2: `ONE PROMPT` — White / XL
- L3: `NO SQUARESPACE` — Blue / LG

**Primary — for Variant A (YouTube · dashboard):**
- Icon: 🌐  ·  Scheme: Blue
- L1: `I BUILT A WEBSITE` — Blue / MD
- L2: `IN 10 MINUTES` — White / XL
- L3: `NO CODE · CLAUDE` — Blue / LG

**Alt — for Variant C (TikTok · illustrated):**
- Image: `Assets/pexels/build-a-website-16675632.jpeg` (website on a laptop, Pexels) — focal photo, replaces emoji  ·  Scheme: Blue
- L1: `A WHOLE WEBSITE` — Blue / MD
- L2: `IN 10 MIN` — White / XL
- L3: `NO CODE · WATCH` — Blue / LG

### Build changes / notes

- Same VO across all 3 cuts (Kokoro `am_adam`, 5 beats: 5.6 / 6.4 / 5.7 / 5.5 / 6.3s ≈ 29.5s; BGM 0.15). 5-scene **~39s**; scenes abut at 0 / 7 / 15 / 22.5 / 30.
- 🔵 Blue accent `#38BDF8` (rotation: 31 lime · 32 blue).
- **Fill-the-frame applied from the first pass** (user note on 32A): scenes centered vertically + cards enlarged so content fills the 9:16 frame. **Scope every GSAP selector to its scene** (`#el-scene-N`) — an unscoped `.dash-hl` hid the build-scene headline until fixed.
- Demo: "PeakForm" coaching landing page. B = polished live browser; C = sketchy dashed browser.
- Whisper smell test: transcript ≈ 99% match to the VO script.
- Build order: user directed "start with version A until further notice" → built A → B → C.

### Posting cadence

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily, 7-9am or 7-9pm EST

---

## Video 33 · Build a Side Hustle

**Status:** ✅ Shipped — all 3 cuts rendered
**Topic:** Build a whole side hustle in a weekend with only Claude — a weekly newsletter ("Sidebar"): name, logo/brand, live signup page, and issue 1. No team, no budget.
**Color scheme:** 🔴 Red (`#EF4444`)
**Tool featured:** Claude (idea · name · brand · site Artifact · first issue)
**Blog post:** [`Go_Live/build-with-ai/33-build-a-side-hustle.html`](Go_Live/build-with-ai/33-build-a-side-hustle.html)

### Renders

| Variant | File | Runtime | Size | Platform | Hook angle | Visual |
|---|---|---|---|---|---|---|
| A | `33-build-a-side-hustle.mp4` | 38s (+2s cover) | YouTube | "I started a business this weekend with only AI" | **Dashboard.** Hook → blank-slate spec (Claude builds: name / logo / signup page / issue 1) → metrics (`1 weekend · 0 employees · ~$0`) → launch (live Sidebar signup page + 3 ✓ stats) → CTA |
| B | `33b-build-a-side-hustle.mp4` | 38s | Instagram | "Blank slate to a real brand in a weekend." | **App-chrome (HERO).** Claude window: the ask → assembling the business piece-by-piece (✓ Name=Sidebar, ✓ Logo, ✓ Signup page, ◌ Issue 01) → the live Sidebar landing page → CTA |
| C | `33c-build-a-side-hustle.mp4` | 38s | TikTok | "A whole business. One weekend. Just AI." | **Illustrated.** Dashed flow: scribble hook → "newsletter business" bubble → dashed Claude node → pieces sketched (name→Sidebar / logo / page / issue) → sketchy live Sidebar page + "it's a business." scribble → CTA |

### YouTube (A)

**Title:**
```
I Started a Business This Weekend — With Only AI (Claude)
```

**Description:**
```
No team. No budget. No idea where to start. I gave Claude a blank slate — a weekly newsletter for side-hustlers — and by Sunday it had named it (Sidebar), designed a logo, written a live signup page, and drafted issue one. A whole brand, in a weekend, with only AI.

Video 3 of Build With AI — every episode I build a real, usable thing with AI and zero code, then show you how. The barrier was never the work; it was starting. Save it and start yours this weekend.

│ AI side hustle │ start a business with AI │ Claude artifacts │ build a brand with AI │ newsletter business │ vibe coding │ build with AI │ side hustle 2026 │

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#Claude #BuildWithAI #sidehustle #AItools #vibecoding #newsletter #ClaudeAI #buildinpublic #LearnAI #YouTubeShorts
```

**Pinned comment:**
```
A blank slate → a named, branded, live newsletter business in one weekend, with only Claude. The barrier was never the work — it was starting. What would yours be? 👇
```

### Instagram (B)

**Caption:**
```
I started a whole business this weekend — with only AI 🤯 name, logo, live signup page, first issue. No team, no budget.

Save this 🔖 — then open Claude and start yours this weekend. (Episode 3 of Build With AI 🛠️)
```

**Hashtags:**
```
#Claude #BuildWithAI #sidehustle #AItools #vibecoding #newsletter #ClaudeAI #LearnAI #buildinpublic
```

### TikTok (C)

**Caption:**
```
a whole business. one weekend. just AI 👀 Claude named it, branded it, built the signup page. the barrier was never the work — it was starting. 👇 (ep 3 of Build With AI 🛠️)
```

**Hashtags:**
```
#Claude #BuildWithAI #sidehustle #vibecoding #TechTok #AItools
```

### Thumbnails

**Hero — for Variant B (Instagram · app-chrome):**
- Icon: 💡  ·  Scheme: Red
- L1: `BLANK SLATE TO` — Red / MD
- L2: `A REAL BRAND` — White / XL
- L3: `IN A WEEKEND` — Red / LG

**Primary — for Variant A (YouTube · dashboard):**
- Icon: 🚀  ·  Scheme: Red
- L1: `I STARTED A BUSINESS` — Red / MD
- L2: `IN A WEEKEND` — White / XL
- L3: `WITH ONLY AI` — Red / LG

**Alt — for Variant C (TikTok · illustrated):**
- Image: `Assets/pexels/build-a-side-hustle-10375902.jpeg` (cafe laptop, Pexels) — focal photo, replaces emoji  ·  Scheme: Red
- L1: `A WHOLE BUSINESS` — Red / MD
- L2: `ONE WEEKEND` — White / XL
- L3: `JUST AI · WATCH` — Red / LG

### Build changes / notes

- Same VO across all 3 cuts (Kokoro `am_adam`, 5 beats: 4.4 / 5.5 / 6.0 / 6.1 / 5.2s ≈ 27s; BGM 0.15). 5-scene **~38s**; scenes abut at 0 / 6.5 / 14 / 21.5 / 29.5.
- 🔴 Red accent `#EF4444` (rotation: 31 lime · 32 blue · 33 red).
- Filled-frame + scoped selectors from the first pass. Meta beat in scene 5 (same "this blog is on a site I built the same way" callout). YouTube cover baked into the A cut (+2s) by the `thumbnail-maker` agent.
- Demo: "Sidebar" — a weekly newsletter for side-hustlers. B's build scene shows the business assembling **piece by piece** (Name/Logo/Page/Issue) — distinct from #31/#32's single-thing builds.
- Whisper smell test: transcript ≈ 99% match to the VO script.
- **"name it · brand it · build it" three-part ask motif added to ALL 3 cuts (2026-06-28)** — same unifying icon set (pencil ✏️ / sparkle ✦ / blocks ▣), styled per aesthetic, paying off in scene 3's name→Sidebar / logo+brand / signup-page stack:
  - **C (TikTok/illustrated):** dashed doodle chips below the ask bubble (was the only cut missing it — the bubble had only the topline ask).
  - **A (YouTube/dashboard):** three accent-topped verb chips between the headline and the spec (ask in verbs → tool → deliverables); also fixed an unscoped `.spec-tool` GSAP selector.
  - **B (Instagram/app-chrome):** a `// claude → 3 tasks queued` row of task pills inside the Claude window under the prompt (reads as Claude parsing the ask into 3 tasks).
  - All re-rendered reusing the **original VO+BGM mix** (extracted per cut → single `mix.wav` track, `data-volume=1`) so audio stays byte-identical + in sync. Durations unchanged: A 40.04s (cover re-baked), B/C 38.04s. Thumbnails unchanged (scene-1 hook is the cover).
- **Sources now KEPT in-folder (policy change 2026-06-28):** `a-youtube/` `b-instagram/` `c-tiktok/` each retain `index.html` + `audio/mix.wav` (all lint-clean, render-ready) alongside the 3 MP4 + 3 PNG — no longer stripped to MP4-only, so future tweaks skip transcript recovery. Applies going forward for the whole series.

### Posting cadence

- YouTube Shorts first · Tue/Thu, 12-3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am-1pm EST
- TikTok daily, 7-9am or 7-9pm EST
- Breakout-precedent anchor — lead the launch week with this one.

---

## Video 34 · Build a Custom Tool

**Topic:** Build the niche tool no app makes — the channel's real **Trend Analyzer** ([live](https://trend-analyzer-xi.vercel.app/)) — from one plain-English prompt in Claude. Topic search + 60-keyword engine, sentiment across TikTok/Instagram/YouTube, a key-insight per platform. 🔵 Blue scheme (`#38BDF8`). **The on-screen app is the user's actual deployed tool, recreated faithfully** (user 2026-06-28: "recreate these videos using my trend analyzer app as a base").

### Renders

| Cut | File | Platform | Hook | Visual |
|---|---|---|---|---|
| A | `34-build-a-custom-tool.mp4` (40s, cover baked) | YouTube | "The app that never existed — so I built it." | **Dashboard.** Hook → spec (Claude + Topic Search/Keyword Engine/3 Platforms/Sentiment) → build stats (0 lines / 1 prompt / ~30s) + bar → the live **Trend Analyzer** ("AI tools" → TikTok POSITIVE / IG POSITIVE / YT NEUTRAL + insights) → CTA |
| B | `34b-build-a-custom-tool.mp4` | Instagram | "One prompt. My exact tool." | **App-chrome (HERO).** Claude window: the prompt → 3 parts queued (topic/sentiment/platforms) → building piece-by-piece (✓ search, ✓ keyword engine, ✓ 3 panels, ◌ sentiment) → the running **Trend Analyzer** (3 platform cards + sentiment) → CTA |
| C | `34c-build-a-custom-tool.mp4` | TikTok | "The tool I couldn't find. So I built it." | **Illustrated.** Dashed flow: scribble hook → "trend analyzer" bubble → 3 sketched parts (topic/mood/3 platforms) → dashed Claude node → sketchy **Trend Analyzer** (3 platform rows + sentiment) + "it reads the room." scribble → CTA |

### YouTube (A)

**Title:**
```
I Built the App That Didn't Exist — in One Prompt (No Code)
```

**Description:**
```
I couldn't find a tool that told me what to make next — so I stopped looking and built my own. No code, no template. I opened Claude, described it in one sentence — a trend analyzer that reads sentiment across TikTok, Instagram & YouTube — and it wrote every line. Seconds later it's running: I type a topic, hit analyze, and it scores the mood on every platform and hands me the angle. It's the real tool I use to run this channel — open it: https://trend-analyzer-xi.vercel.app/

That's the whole point of a custom tool: it fits you, not the other way around.

🛠️ Built with: Claude (Artifacts) · zero code
🔵 Part of Build With AI — a real thing built with AI every episode.

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#buildwithai #claude #nocode #customtool #trendanalysis #aitools #vibecoding #socialmedia
```

**Pinned comment:**
```
One sentence in Claude → a working trend analyzer (sentiment across TikTok/IG/YouTube), zero code. It's the real tool I use to pick topics — try it: https://trend-analyzer-xi.vercel.app/ · What would you build? 👇
```

### Instagram (B)

**Caption:**
```
I stopped guessing what to post. 🔵 I described the trend analyzer I actually wanted to Claude — type a topic, read the sentiment across TikTok, Instagram & YouTube — and it built the whole thing. No code. It's the real tool I use to run this channel. The custom tool you want is one prompt away. Save this. 🔖
```

**Hashtags:**
```
#buildwithai #claude #nocode #customtool #aitools #trendanalysis #contentstrategy #vibecoding
```

### TikTok (C)

**Caption:**
```
the tool that tells me what to post… so I built it 🔵 one prompt, zero code — a trend analyzer for TT/IG/YT. what would you make? #buildwithai #claude #nocode #customtool #aitools #trendanalysis #fyp
```

**Hashtags:**
```
#buildwithai #claude #nocode #customtool #aitools #trendanalysis #fyp #vibecoding
```

### Thumbnails

**A — for Variant A (YouTube · dashboard):**
- Icon: 🧰  ·  Scheme: Blue
- L1: `I BUILT THE` — Blue / MD
- L2: `TOOL I NEEDED` — White / XL
- L3: `ZERO CODE · CLAUDE` — Blue / LG

**B — for Variant B (Instagram · app-chrome HERO):**
- Icon: 🎛️  ·  Scheme: Blue
- L1: `ONE PROMPT` — Blue / MD
- L2: `MY EXACT TOOL` — White / XL
- L3: `NO APP DID IT` — Blue / LG

**C — for Variant C (TikTok · illustrated):**
- Icon: ⚙️  ·  Scheme: Blue
- L1: `THE APP THAT` — Blue / MD
- L2: `DIDN'T EXIST` — White / XL
- L3: `SO I BUILT IT · WATCH` — Blue / LG

### Build changes / notes
- Same VO across all 3 cuts (Kokoro `am_adam`, 5 beats: 4.35 / 5.46 / 5.31 / 5.29 / 5.78s ≈ 26s; BGM 0.15). 5-scene **38s**; scenes abut at 0 / 6.5 / 14 / 21.5 / 29.5.
- 🔵 Blue accent `#38BDF8` (rotation: 31 lime · 32 blue · 33 red · **34 blue**).
- Filled-frame + scoped selectors. Scene-5 meta beat reframed to **"the tools behind this channel? built the exact same way."** YouTube cover baked into the A cut (+2s) by the `thumbnail-maker` agent.
- Demo: the user's real **Trend Analyzer** ([deployed](https://trend-analyzer-xi.vercel.app/)), recreated faithfully — dark + cyan, "Trend Analyzer · Social Intelligence", topic input + ANALYZE (teal gradient), 3 platform cards (TikTok cyan ♪ / Instagram orange ◈ / YouTube red ▶) with sentiment badge (POSITIVE green / NEUTRAL gray) + key insight. Shared search/pulse/bars icon set across B's task pills + C's ask chips. Scene-4 payoff = the analyzer scoring "AI tools" (TT POSITIVE / IG POSITIVE / YT NEUTRAL). **Rebuilt 2026-06-28 from the original "Streak" habit-tracker version** per the user's "use my trend analyzer app" request — new VO (5 beats: 4.84/6.59/6.61/5.70/5.78s), scenes 2–4 swapped; thumbnails (🧰/🎛️/⚙️) kept, A re-baked.
- **Thumbnails use 3 DISTINCT emojis (🧰 / 🎛️ / ⚙️), no Pexels** (user 2026-06-28: "change up the emojis, don't use the pexels plugin") — fixes the prior reuse of one emoji across cuts.
- **Sources kept** in-folder (a-youtube/b-instagram/c-tiktok + audio/).
- Whisper smell test: transcript ≈ 99% match to the VO script.

### Posting cadence
- YouTube Shorts first · Tue/Thu, 12–3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am–1pm EST
- TikTok daily, 7–9am or 7–9pm EST

---

## Video 35 · Build a Custom AI

**Topic:** Build a **custom AI** in Claude — the user's real **Reddit → Script** tool: Claude with a tuned system prompt that turns Reddit's top stories into faceless-video scripts (Hook / Format / Key points / Tone / closing line). 🟠 Reddit-orange (`#FF4500`, deviates from the lime rotation to match the real app). Honest backstory: built for the user's Reddit Story Time channels, which flopped — the AI outlived them. **On-screen app recreated faithfully from the user's source** (neutral "Reddit → Script" name; "Kveeloo" branding dropped to stay Claude-native; Claude is the engine).

### Renders

| Cut | File | Platform | Hook | Visual |
|---|---|---|---|---|
| A | `35-build-a-custom-ai.mp4` (40s, cover baked) | YouTube | "My channel flopped. The AI didn't." | **Dashboard.** Hook → spec (Claude + Scrape Reddit / Top Stories / My Script Format / One Click) → build stats (0 lines / 1 system prompt / ~30s) → the **Reddit → Script** panel (r/AskReddit story → GENERATE → HOOK/FORMAT/END script) → CTA |
| B | `35b-build-a-custom-ai.mp4` | Instagram | "One AI. One job." | **App-chrome (HERO).** Claude window: the prompt → 3 parts queued (scrape/pick/script) → building piece-by-piece (✓ scraper, ✓ filter, ✓ format, ◌ Claude writer) → the running **Reddit → Script** tool → CTA |
| C | `35c-build-a-custom-ai.mp4` | TikTok | "My channel flopped. The AI didn't." | **Illustrated.** Dashed flow: scribble hook → "top stories → script" bubble → 3 sketched parts (scrape/pick/script) → dashed Claude node → sketchy **Reddit → Script** (story → GENERATE → script) + "still works." scribble → CTA |

### YouTube (A)

**Title:**
```
I Built a Custom AI That Writes My Videos From Reddit — No Code (Claude)
```

**Description:**
```
My Reddit story channel flopped. But the custom AI I built to run it is still the best tool I own. No code.

I taught Claude one job, in plain English: read Reddit's top stories, and turn the best one into a video script in my exact format — hook, beats, closing line. One click turns a messy Reddit thread into something I could record today. The channel died. The AI didn't.

That's the whole trick with a custom AI: you teach it your exact job once, and it works forever.

🛠️ Built with: Claude · zero code
🟠 Part of Build With AI — a real thing built with AI every episode.

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#buildwithai #claude #customai #nocode #reddit #aitools #vibecoding #facelesschannel
```

**Pinned comment:**
```
One system prompt in Claude → an AI that turns Reddit's top stories into video scripts. My channel flopped; the AI's still the best tool I own. What would you teach an AI to do? 👇
```

### Instagram (B)

**Caption:**
```
My Reddit channel flopped. 🟠 But the custom AI I built to run it didn't.

I taught Claude one job — scrape Reddit's top stories, write each into a video script in my format — and it still does it every week. No code. Don't settle for generic AI; teach one your exact job, once. Save this. 🔖 (Episode 5 of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #customai #nocode #aitools #reddit #contentcreator #vibecoding
```

### TikTok (C)

**Caption:**
```
my reddit channel flopped 🟠 but the custom AI I built to run it didn't. it scrapes reddit's top stories → writes me a script. taught Claude one job, zero code. (ep 5 of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #customai #nocode #reddit #fyp #aitools
```

### Thumbnails

**A — for Variant A (YouTube · dashboard):**
- Icon: 👽  ·  Scheme: Orange
- L1: `MY CHANNEL` — White / MD
- L2: `FLOPPED.` — Orange / XL
- L3: `THE AI DIDN'T` — White / LG

**B — for Variant B (Instagram · app-chrome HERO):**
- Icon: 🧠  ·  Scheme: Orange
- L1: `I TAUGHT AI` — Orange / MD
- L2: `ONE EXACT JOB` — White / XL
- L3: `ZERO CODE · CLAUDE` — Orange / LG

**C — for Variant C (TikTok · illustrated):**
- Icon: 🤖  ·  Scheme: Orange
- L1: `A FLOP LEFT ME` — Orange / MD
- L2: `A REAL TOOL` — White / XL
- L3: `MY CUSTOM AI · WATCH` — Orange / LG

### Build changes / notes
- Same VO across all 3 cuts (Kokoro `am_adam`, 5 beats: 5.87 / 6.61 / 7.40 / 6.21 / 5.44s ≈ 31.5s; BGM 0.15). 5-scene **38s**; scenes abut at 0 / 6.5 / 14 / 21.5 / 29.5 (VO3 fills scene 3 edge-to-edge).
- 🟠 **Reddit-orange `#FF4500`** — deviates from the lime rotation (35 was slated lime) to match the real app's identity; user approved ("go"). Fonts: Bebas Neue + IBM Plex Mono (built-in; the real app uses Syne + DM Mono).
- Demo = the user's real **Reddit → Kveeloo Prompt Builder** (FastAPI + Claude `claude-sonnet-4-6` with the `KVEELOO_SYSTEM` prompt → video-script prompts). Recreated faithfully; **on-screen name neutralized to "Reddit → Script"** and Kveeloo branding dropped to keep the series Claude-native (user's "everything Claude, no competitor tools" rule). The "custom AI" = the tuned system prompt.
- **Honest backstory (user 2026-06-28):** built it to scrape Reddit's top stories for the user's **failed Reddit Story Time channels** — the channels flopped, the tool didn't. Scene-1 hook + scene-5 meta beat both carry it.
- Scene-4 payoff = the Reddit → Script tool: r/AskReddit story → GENERATE → HOOK / FORMAT / END script. Shared scrape/pick/script icon set across B task pills + C ask chips.
- **Sources kept** in-folder (a-youtube/b-instagram/c-tiktok + audio/). A cover baked (+2s). Whisper smell test ≈ 99%.

### Posting cadence
- YouTube Shorts first · Tue/Thu, 12–3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am–1pm EST
- TikTok daily, 7–9am or 7–9pm EST

---

## Video 36 · Build a Game

**Topic:** Build a **real game** with AI, zero code — the user's own **Grimoire** (Text Twist fused with a roguelike dungeon crawler: *your words are weapons* — spell words to attack monsters, loot gear/spellbooks, descend, permadeath; CrazyGames-ready). 🟡 Gold-on-dark-purple (`#F2C14E` / `#0C0A12`, deviates from the rotation's red to match the game's identity). **On-screen game recreated faithfully from the user's source zip** — kept the **GRIMOIRE** name (it's the user's own game, not a competitor).

### Renders

| Cut | File | Platform | Hook | Visual |
|---|---|---|---|---|
| A | `36-build-a-game.mp4` (40s, cover baked) | YouTube | "Your words are weapons. I can't even code." | **Dashboard.** Hook → spec (Claude + Word Engine / Word-Combat / Loot & Gear / Bosses) → build stats (0 lines I wrote / 6k+ Claude wrote / 29k lexicon) → the **Grimoire** battle (Green Slime + HP + the METEOR rack → cast ×4.2 → 168 dmg) → CTA |
| B | `36b-build-a-game.mp4` | Instagram | "Just describe the game." | **App-chrome (HERO).** Claude window: the game pitch → 3 systems queued (words/combat/descend) → building piece-by-piece (✓ word engine, ✓ combat, ✓ loot & spells, ◌ bosses) → the running **Grimoire** battle → CTA |
| C | `36c-build-a-game.mp4` | TikTok | "Your words are weapons." | **Illustrated.** Dashed flow: scribble hook → "Text Twist but a roguelike" bubble → 3 sketched systems → dashed Claude node → sketchy **Grimoire** battle (METEOR tiles → 168 dmg) + "it's real." scribble → CTA |

### YouTube (A)

**Title:**
```
I Built a Full Roguelike Game With AI — And I Can't Code (Claude)
```

**Description:**
```
I can't write code. So I built a roguelike game with AI instead — and in it, your words are the weapons.

It's Grimoire: Text Twist crossed with a dungeon crawler. Every monster hands you a scrambled six-letter rack; longer, rarer words hit harder; spell the six-letter word and the monster dies. Loot gear and spellbooks, descend deeper, permadeath.

Claude wrote the whole thing — the word engine, the combat math, the loot, the bosses. Thousands of lines. I wrote zero. You don't need to code to make a game anymore.

🛠️ Built with: Claude · zero code
🟡 Part of Build With AI — a real thing built with AI every episode.

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#buildwithai #claude #nocode #gamedev #roguelike #wordgame #aitools #vibecoding
```

**Pinned comment:**
```
A full roguelike where your words are the weapons — built in Claude, and I can't write a line of code. What game would you make? 👇
```

### Instagram (B)

**Caption:**
```
I can't code. So I built a roguelike game with AI. 🟡 In Grimoire, your words are the weapons — Text Twist meets dungeon crawler.

I described it to Claude and it wrote the whole thing: the word engine, the combat, the loot, the bosses. Zero code. You don't need to code to make a game anymore. Save this. 🔖 (Episode 6 of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #nocode #gamedev #roguelike #wordgame #aitools #vibecoding
```

### TikTok (C)

**Caption:**
```
i can't code so I built a roguelike with AI 🟡 in Grimoire your words are the weapons — text twist meets dungeon crawler. Claude wrote every line. (ep 6 of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #nocode #gamedev #roguelike #wordgame #fyp
```

### Thumbnails

**A — for Variant A (YouTube · dashboard):**
- Icon: 📖  ·  Scheme: Gold
- L1: `WORDS ARE` — White / MD
- L2: `WEAPONS` — Gold / XL
- L3: `BUILT WITH AI` — Gold / LG

**B — for Variant B (Instagram · app-chrome HERO):**
- Icon: 🎮  ·  Scheme: Gold
- L1: `TEXT TWIST +` — Gold / MD
- L2: `A ROGUELIKE` — White / XL
- L3: `ZERO CODE · CLAUDE` — Gold / LG

**C — for Variant C (TikTok · illustrated):**
- Icon: ⚔️  ·  Scheme: Gold
- L1: `I CAN'T CODE` — Gold / MD
- L2: `I MADE A GAME` — White / XL
- L3: `MY OWN GAME · WATCH` — Gold / LG

### Build changes / notes
- Same VO across all 3 cuts (Kokoro `am_adam`, 5 beats: 5.18 / 6.81 / 5.35 / 6.02 / 4.44s ≈ 28s; BGM 0.15). 5-scene **38s**; scenes abut at 0 / 6.5 / 14 / 21.5 / 29.5.
- 🟡 **Gold `#F2C14E` on dark purple `#0C0A12`** + parchment letter tiles (`#EFE6D2`) — deviates from the lime/blue/red rotation to match Grimoire's identity (user said "go"). Fonts: Bebas Neue + IBM Plex Mono (built-in; the real game uses a serif display + system fonts).
- Demo = the user's real **Grimoire** ("TextTwist" folder — pure HTML/CSS/JS, no build step, CrazyGames SDK integrated). Text Twist + roguelike: words are weapons, loot/gear/spellbooks, bosses, jackpot chest, merchant, permadeath, local leaderboard. Recreated faithfully from the source zip (`Grimoire.zip`); **kept the GRIMOIRE name** (user's own game).
- Scene-4 payoff = the battle: 🟢 Green Slime + blood HP bar + the parchment **METEOR** rack (letters with point values) → `cast METEOR · ×4.2 → 168 dmg` (words = weapons). Shared words/combat/descend icon set across B task pills + C ask chips.
- **Sources kept** in-folder (a-youtube/b-instagram/c-tiktok + audio/). A cover baked (+2s). Whisper smell test ≈ 99%.

### Posting cadence
- YouTube Shorts first · Tue/Thu, 12–3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am–1pm EST
- TikTok daily, 7–9am or 7–9pm EST

---

## Video 37 · Build a Workout Program

**Topic:** Build a **real workout program** with AI, zero code — the user's own **Get_Ripped**, a 120-day fat-loss app (5-day training split across 4 phases, macros + meals that scale to bodyweight, workout logging, progress charts, supplement + shopping lists — one HTML file, live at `longvy24.github.io/Get_Ripped`). 🔥 Ember orange-on-navy (`#FF6B35` / `#0F1419`, matches the app's own scheme). **On-screen app recreated faithfully from the user's source zip** — kept the **GET RIPPED** name (it's the user's own program, not a competitor). Angle: *"I was too lazy to get a personal trainer — so I built my own 120-day program, the whole app, with AI."* (the honest motivation was laziness/hassle, not cost — user corrected this 2026-07-03.)

### Renders

| Cut | File | Platform | Hook | Visual |
|---|---|---|---|---|
| A | `37-build-a-workout-program.mp4` (40s, cover baked) | YouTube | "Too lazy to get a trainer. So I built my own." | **Dashboard.** Hook → spec (Claude + 5-Day Plan / Scaling Macros / Meal Rotation / Progress Charts) → build stats (0 lines I wrote / 1 HTML file / 120-day plan) → the **GET RIPPED** dashboard (weight 220 → macro pills 2,500 / 220g / 227g / 79g, Phase 2 · 42%) → CTA |
| B | `37b-build-a-workout-program.mp4` | Instagram | "Just describe the program." | **App-chrome (HERO).** Claude window: the 120-day pitch → 3 systems queued (5-day plan / macros / track) → building piece-by-piece (✓ 4 phases, ✓ meal rotation, ✓ scaling macros, ◌ progress charts) → the live **GET RIPPED** app (weight → reactive macros → Phase 2) → CTA |
| C | `37c-build-a-workout-program.mp4` | TikTok | "No trainer. No code. Just Claude." | **Illustrated.** Dashed flow: scribble hook → "scales to my weight" bubble → 3 sketched asks (plan / macros / track) → dashed Claude node → sketchy **GET RIPPED** dashboard (weight → macro pills → phase bar) + "it's mine." scribble → CTA |

### YouTube (A)

**Title:**
```
I Was Too Lazy to Get a Trainer — So I Built My Own 120-Day Program With AI
```

**Description:**
```
Getting a personal trainer felt like a whole project — the consults, the scheduling, the commitment. I was too lazy for all that. So I built my own 120-day fat-loss program instead — the entire app — with AI, and I can't write a line of code.

It's Get Ripped: a 5-day training split across four phases, macros and meals that recalculate the second I punch in my bodyweight, workout logging, progress charts, supplement and shopping lists. All of it in one file.

I described the program to Claude and it wrote the whole thing. Zero code. You don't need to hire anyone to get a plan that's actually built around you — you need a browser and an afternoon.

🛠️ Built with: Claude · zero code
🔥 Part of Build With AI — a real thing built with AI every episode.

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#buildwithai #claude #nocode #fitness #workoutplan #fatloss #aitools #vibecoding
```

**Pinned comment:**
```
A whole 120-day program that re-scales my macros the second I log my weight — built in Claude, zero code. What would you build a plan for? 👇
```

### Instagram (B)

**Caption:**
```
I was too lazy to get a personal trainer. So I built my own 120-day program with AI instead. 🔥 Get Ripped: a 5-day split, four phases, and macros + meals that re-scale to my bodyweight.

I described it to Claude and it wrote the whole app — one file, zero code. I punch in my weight and everything reacts. Save this. 🔖 (Episode 7 of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #nocode #fitness #workoutplan #fatloss #aitools #vibecoding
```

### TikTok (C)

**Caption:**
```
too lazy to get a trainer so I built my own 120-day program with AI 🔥 Get Ripped scales my macros + meals to my bodyweight. Claude wrote every line, zero code. (ep 7 of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #nocode #fitness #gymtok #fatloss #fyp
```

### Thumbnails

**A — for Variant A (YouTube · dashboard):**
- Icon: 💪  ·  Scheme: Ember
- L1: `I BUILT MY OWN` — White / MD
- L2: `120-DAY PLAN` — Ember / XL
- L3: `ZERO CODE · CLAUDE` — Ember / LG

**B — for Variant B (Instagram · app-chrome HERO):**
- Icon: 🏋️  ·  Scheme: Ember
- L1: `TOO LAZY FOR` — Ember / MD
- L2: `A TRAINER` — White / XL
- L3: `SO I BUILT ONE` — Ember / LG

**C — for Variant C (TikTok · illustrated):**
- Icon: 🔥  ·  Scheme: Ember
- L1: `I CAN'T CODE` — Ember / MD
- L2: `MY OWN COACH` — White / XL
- L3: `BUILT IT · WATCH` — Ember / LG

### Build changes / notes
- Same VO across all 3 cuts (Kokoro `am_adam`, 5 beats: 5.44 / 7.15 / 7.15 / 6.06 / 3.93s ≈ 30s; BGM 0.15). 5-scene **38s**; scenes abut at 0 / 6.5 / 14 / 21.5 / 29.5.
- 🔥 **Ember orange `#FF6B35` + amber `#FFA726` on navy `#0F1419`** — matches the real Get_Ripped app scheme (not the lime/blue/red rotation; user chose "match the app"). Fonts: Bebas Neue + IBM Plex Mono (built-in). Added an **Ember** row to the thumbnail-maker palette table.
- **VO1 + VO5 reframed 2026-07-03 from a cost angle to a laziness angle** — user: *"I was too lazy to get a personal trainer, not can't afford."* New VO1 "I was too lazy to get a trainer. So I built my own 120-day program with AI." = 5.44s; new VO5 "You don't need a trainer. Describe your program to Claude, and start tomorrow." = 3.93s. VO2/3/4 unchanged. On-screen hook now "TOO LAZY TO / GET A TRAINER. / SO I BUILT MY OWN."; scene-5 pre "You don't need a trainer." All 3 cuts re-rendered, A re-baked, thumbnail B reworked ("NO $200 COACH" → "TOO LAZY FOR / A TRAINER / SO I BUILT ONE"). No cost/"$200" claim anywhere now.
- Demo = the user's real **Get_Ripped** (single-file 120-day fat-loss app + SQLite dashboards). Weight-reactive macros (2,500 cal / 220g P / 227g C / 79g F @ 220 lbs), four phases (Ramp-Up / Build / Push / Peak-Cut), meal rotation, supplements, shopping lists, "The Four Rules That Don't Break." Recreated faithfully from `Get_Ripped.zip`; **kept the GET RIPPED name** (user's own program). Scene-4 payoff across all cuts = punch in weight → macros/meals/phase all react.
- **Sources kept** in-folder (a-youtube/b-instagram/c-tiktok + audio/). A cover baked (+2s). Whisper smell test ≥ 95%.

### Posting cadence
- YouTube Shorts first · Tue/Thu, 12–3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am–1pm EST
- TikTok daily, 7–9am or 7–9pm EST

---

## Video 38 · Build a Landing Page

**Topic:** Build a **real landing page** with AI, zero code — the actual **AIToolsDaily24** landing page (*the site these blog posts live on*). Recreated the real homepage hero faithfully from `Go_Live/index.html`: tag "AIToolsDaily24 · by Ryu Vy", hero **"THE AI / ARMS RACE / IS ON."** (Arms Race lime, "ON." outlined), tagline "Don't get left behind…", CTA **↓ Watch The Series** + **Free Cheatsheet**, stat strip **10 Techniques · 3 Platforms · ∞ Applications**. 🟢 **Lime `#84E000` on near-black `#0A0C0A`** — matches BOTH the real site's scheme AND the series lime rotation (no deviation this time). Meta capstone: *"the landing page for the site you're reading this on — built with AI too."*

### Renders

| Cut | File | Platform | Hook | Visual |
|---|---|---|---|---|
| A | `38-build-a-landing-page.mp4` (40s, cover baked) | YouTube | "Every project needs a page. So I built mine." | **Dashboard.** Hook → spec (Claude + Hero+Tagline / One CTA / Stat Strip / On-Brand) → build stats (0 lines I wrote / 1 HTML file / 100% responsive) → the **AIToolsDaily24** landing page (nav + "THE AI ARMS RACE IS ON." + CTA buttons + 10/3/∞ stat strip) → CTA |
| B | `38b-build-a-landing-page.mp4` | Instagram | "Just describe the page." | **App-chrome (HERO).** Claude window: the channel-page pitch → 3 blocks queued (hero/CTA/stats) → building block-by-block (✓ hero, ✓ CTA buttons, ✓ stat strip, ◌ responsive) → the live page in a browser (`aitoolsdaily24.com` URL bar, full hero) → CTA |
| C | `38c-build-a-landing-page.mp4` | TikTok | "No designer. No code. Just Claude." | **Illustrated.** Dashed flow: scribble hook → "lime on black" bubble → 3 sketched blocks (hero/CTA/stats) → dashed Claude node → sketchy **AIToolsDaily24** page (hero + CTA + stat cells) + "it's live." scribble → CTA |

### YouTube (A)

**Title:**
```
I Built the Landing Page for My Whole Channel With AI — Zero Code (Claude)
```

**Description:**
```
Every project needs a landing page — so I built one for my entire channel with AI, and I can't write a line of code.

This is the real AIToolsDaily24 landing page: the bold hero ("The AI Arms Race Is On."), the tagline, one clear call-to-action, and a stat strip — lime on black, fully on brand. It's the exact page the write-up for this video lives on.

I described what I wanted to Claude and it wrote the whole thing: the layout, the headline, the buttons, the sections, the responsive breakpoints. One HTML file, zero code. You don't need a designer or a developer to ship a landing page that looks the part — you need a browser and a clear description.

🛠️ Built with: Claude · zero code
🟢 Part of Build With AI — a real thing built with AI every episode.

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#buildwithai #claude #nocode #landingpage #webdesign #webdev #aitools #vibecoding
```

**Pinned comment:**
```
This is the actual landing page for my channel — hero, CTA, stat strip, all built in Claude, zero code. The blog for this video lives on it. What would you put a landing page in front of? 👇
```

### Instagram (B)

**Caption:**
```
Every project needs a landing page. So I built one for my whole channel with AI. 🟢 This is the real AIToolsDaily24 page — "The AI Arms Race Is On.", one CTA, a stat strip, lime on black.

I described it to Claude and it wrote the whole page: layout, headline, buttons, responsive. One file, zero code. No designer, no dev. Save this. 🔖 (Episode 8 of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #nocode #landingpage #webdesign #webdev #aitools #vibecoding
```

### TikTok (C)

**Caption:**
```
every project needs a landing page so I built one for my whole channel with AI 🟢 the real AIToolsDaily24 page — hero, one CTA, a stat strip, lime on black. Claude wrote every line, zero code. (ep 8 of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #nocode #landingpage #webdesign #fyp
```

### Thumbnails

**A — for Variant A (YouTube · dashboard):**
- Icon: 🚀  ·  Scheme: Lime
- L1: `EVERY PROJECT` — White / MD
- L2: `NEEDS A PAGE` — Lime / XL
- L3: `BUILT WITH AI` — Lime / LG

**B — for Variant B (Instagram · app-chrome HERO):**
- Icon: 🖥️  ·  Scheme: Lime
- L1: `MY WHOLE` — Lime / MD
- L2: `CHANNEL PAGE` — White / XL
- L3: `ZERO CODE · CLAUDE` — Lime / LG

**C — for Variant C (TikTok · illustrated):**
- Icon: 🎯  ·  Scheme: Lime
- L1: `NO DESIGNER` — Lime / MD
- L2: `NO CODE` — White / XL
- L3: `BUILT IT · WATCH` — Lime / LG

### Build changes / notes
- Same VO across all 3 cuts (Kokoro `am_adam`, 5 beats: 4.99 / 6.85 / 6.53 / 5.33 / 4.57s ≈ 28s; BGM 0.15). 5-scene **38s**; scenes abut at 0 / 6.5 / 14 / 21.5 / 29.5.
- 🟢 **Lime `#84E000` + `#9FFF00` on near-black `#0A0C0A`** — the ONE video where the real project's scheme = the series-rotation theme (no deviation to flag). Fonts: Bebas Neue + IBM Plex Mono (built-in; the real site uses DM Sans body).
- Demo = the **real AIToolsDaily24 landing page** — recreated faithfully from `Go_Live/index.html` (hero "THE AI ARMS RACE IS ON." with "ON." outlined, Watch-The-Series + Free-Cheatsheet CTAs, 10/3/∞ stat strip, Ryu Vy tagline). **Kept all real brand copy.** Scene-4 payoff across all cuts = that hero landing page. Meta capstone — the page hosts this video's own blog post (ties into the V32/V33/V36 "this site was built the same way" thread).
- **Sources kept** in-folder (a-youtube/b-instagram/c-tiktok + audio/). A cover baked (+2s). Whisper smell test ≥ 95%.

### Posting cadence
- YouTube Shorts first · Tue/Thu, 12–3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am–1pm EST
- TikTok daily, 7–9am or 7–9pm EST

---

## Video 39 · Build a Browser Extension

**Topic:** Build a **real browser extension** with AI, zero code — **"Gist," a highlight-to-summarize Chrome extension powered by Claude**. Select any text on any page → a floating popup gives you the gist, with three modes: **Summarize · Explain · Rewrite**. 🔴 Red `#EF4444` on near-black `#100B0B` (series red slot; red carries the "stop reading walls of text" pain/stop hook). **Invented demo** (user picked the *type* — "AI assistant popup" — not a real repo; like V31/V32). Kept it Claude-native ("powered by Claude"), no competitor tools. Note: a *real* build of this needs the user's own Claude API key at runtime (stated honestly in the blog).

### Renders

| Cut | File | Platform | Hook | Visual |
|---|---|---|---|---|
| A | `39-build-a-browser-extension.mp4` (40s, cover baked) | YouTube | "Stop reading walls of text. So I built this." | **Dashboard.** Hook → spec (Claude + Highlight→Ask / 3 Modes / Any Website / One-Click Load) → build stats (0 lines I wrote / 3 files / 1 click) → the **Gist** popup on a page (highlighted paragraph → TL;DR + bullets) → CTA |
| B | `39b-build-a-browser-extension.mp4` | Instagram | "Just describe the extension." | **App-chrome (HERO).** Claude window: the extension pitch → 3 files queued (highlight/3 modes/any page) → building file-by-file (✓ manifest.json, ✓ popup UI, ✓ content script, ◌ Claude wiring) → the live page (`developer.blog` URL) with highlighted text + the **Gist** popup → CTA |
| C | `39c-build-a-browser-extension.mp4` | TikTok | "Highlight it. Claude does the rest." | **Illustrated.** Dashed flow: scribble hook → "highlight any text → get the gist" bubble → 3 sketched asks (highlight/3 modes/any page) → dashed Claude node → sketchy highlighted line → dashed **Gist** card (TL;DR) + "the gist." scribble → CTA |

### YouTube (A)

**Title:**
```
I Built a Chrome Extension With AI — Highlight Any Text, Get the Gist (Zero Code)
```

**Description:**
```
I read a lot of long, dense articles — so I built a browser extension that reads them for me, with AI, and I can't write a line of code.

It's Gist: highlight any text on any page and a little popup hands you the gist — summarize it, explain it simpler, or rewrite it. Powered by Claude.

I described it to Claude and it wrote the whole extension: the manifest, the popup UI, the content script that reads your selection. Three files. I loaded it into Chrome unpacked in one click. Zero code. A browser extension used to be the definition of "you'd need a developer" — not anymore.

🛠️ Built with: Claude · zero code
🔴 Part of Build With AI — a real thing built with AI every episode.

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#buildwithai #claude #nocode #chromeextension #browserextension #aitools #productivity #vibecoding
```

**Pinned comment:**
```
Highlight any text → a popup gives you the gist, powered by Claude. Three files, loaded into Chrome in one click, zero code. What would your extension do? 👇
```

### Instagram (B)

**Caption:**
```
I got tired of reading walls of text. So I built a Chrome extension with AI. 🔴 It's Gist — highlight any text on any page and a popup gives you the gist: summarize, explain, or rewrite. Powered by Claude.

I described it to Claude and it wrote the whole extension — manifest, popup, content script. Three files, loaded in one click, zero code. Save this. 🔖 (Episode 9 of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #nocode #chromeextension #browserextension #aitools #productivity #vibecoding
```

### TikTok (C)

**Caption:**
```
got tired of reading walls of text so I built a chrome extension with AI 🔴 highlight any text → get the gist. summarize, explain, or rewrite, powered by Claude. 3 files, zero code. (ep 9 of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #nocode #chromeextension #browserextension #productivity #fyp
```

### Thumbnails

**A — for Variant A (YouTube · dashboard):**
- Icon: 🧩  ·  Scheme: Red
- L1: `STOP READING` — White / MD
- L2: `WALLS OF TEXT` — Red / XL
- L3: `BUILT WITH AI` — Red / LG

**B — for Variant B (Instagram · app-chrome HERO):**
- Icon: 🔖  ·  Scheme: Red
- L1: `HIGHLIGHT IT` — Red / MD
- L2: `GET THE GIST` — White / XL
- L3: `ZERO CODE · CLAUDE` — Red / LG

**C — for Variant C (TikTok · illustrated):**
- Icon: ✨  ·  Scheme: Red
- L1: `NO DEV NEEDED` — Red / MD
- L2: `I BUILT IT` — White / XL
- L3: `CHROME EXT · WATCH` — Red / LG

### Build changes / notes
- Same VO across all 3 cuts (Kokoro `am_adam`, 5 beats: 5.18 / 7.00 / 6.31 / 6.40 / 5.65s ≈ 31s; BGM 0.15). 5-scene **38s**; scenes abut at 0 / 6.5 / 14 / 21.5 / 29.5.
- 🔴 **Red `#EF4444` + `#F87171` on near-black `#100B0B`** (series red rotation slot). Fonts: Bebas Neue + IBM Plex Mono (built-in).
- Demo = **"Gist"** — an INVENTED but believable highlight-to-summarize Chrome extension (user chose the *type* "AI assistant popup," not a real repo). Kept **Claude-native** ("✦ Gist · powered by Claude") per the everything-Claude rule; no competitor tools. Scene-4 payoff across all cuts = highlight a dense paragraph ("How Context Windows Work") → the Gist popup with `TL;DR:` + 2 bullets + Summarize/Explain/Rewrite tabs. Honest caveat carried into the blog: a real build calls the Claude API, so it needs the user's own API key at runtime.
- **Sources kept** in-folder (a-youtube/b-instagram/c-tiktok + audio/). A cover baked (+2s). Whisper smell test ≥ 95%.

### Posting cadence
- YouTube Shorts first · Tue/Thu, 12–3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am–1pm EST
- TikTok daily, 7–9am or 7–9pm EST

---

## Video 40 · What's Actually Usable  *(THE FINALE)*

**Topic:** The season finale. A **capstone build** — **"The Stack," a personal hub page** that collects all 9 prior builds into one place, one click to open each. It's the 10th build *and* the wrap: "what's actually usable" = the whole season in one page. 🟢 Lime `#84E000` on near-black `#0A0C0A` (results/triumph slot; matches the AIToolsDaily24 brand). **User chose "one capstone build"** for the finale (over an honest-ranking recap or a rapid montage). Hub tiles = the real series: 🧾 Invoice Maker (app) · 🏔️ PeakForm (website) · 📬 Sidebar (hustle) · 📊 Trend Analyzer (tool) · 🧠 Reddit → Script (custom AI) · 📖 Grimoire (game) · 💪 Get Ripped (workout) · 🚀 Landing Page (site) · 🧩 Gist (extension).

### Renders

| Cut | File | Platform | Hook | Visual |
|---|---|---|---|---|
| A | `40-whats-actually-usable.mp4` (40s, cover baked) | YouTube | "Nine builds. Zero code. Here's the 10th." | **Dashboard.** Hook → spec (Claude + One Page / A Tile Per Tool / One-Click Open / On-Brand) → finale stats (10 things built / 0 lines I wrote / 1 human) → **The Stack** hub (3×3 grid of all 9 builds) → CTA "build your ten" |
| B | `40b-whats-actually-usable.mp4` | Instagram | "Just describe the hub." | **App-chrome (HERO).** Claude window: the hub pitch → 3 parts queued (grid/links/on-brand) → building (✓ 9 tiles, ✓ links wired, ✓ lime layout, ◌ responsive) → the live **The Stack** (`aitoolsdaily24.com/stack`, 9-tile grid) → CTA |
| C | `40c-whats-actually-usable.mp4` | TikTok | "One hub. Every tool. Just Claude." | **Illustrated.** Dashed flow: scribble hook → "one page → every tool I built" bubble → 3 sketched asks (grid/links/on-brand) → dashed Claude node → sketchy **The Stack** grid (9 dashed tiles) + "that's the season." scribble → CTA |

### YouTube (A)

**Title:**
```
I Built 10 Real Things With AI and Zero Code — Here's Every One (Claude)
```

**Description:**
```
Nine builds this season — a real app, a website, a side hustle, a custom tool, a custom AI, a game, a workout program, a landing page, a browser extension. All with AI, all zero code. So for the finale I built a tenth: one hub that holds them all.

It's The Stack — a single page with a tile for every tool I made, one click to open each. I described it to Claude and it wrote the whole thing. One file, zero code, on brand.

That's the whole point of Build With AI: you don't need to code to build real, usable things anymore. You need an idea and the willingness to describe it. Ten times over, this season proved it.

🛠️ Built with: Claude · zero code
🟢 The finale of Build With AI — a real thing built with AI every episode.

Music from #InAudio: https://inaudio.org/
Infraction-Never-Leave-Short-Version.
```

**Hashtags:**
```
#buildwithai #claude #nocode #aitools #vibecoding #buildinpublic #sidehustle #productivity
```

**Pinned comment:**
```
That's the season — 10 real things built with AI, zero code, one human who can't write a line of it. The Stack holds them all. Which build should I turn into a full tutorial? 👇
```

### Instagram (B)

**Caption:**
```
Nine builds this season, all with AI, all zero code. So I built a tenth — The Stack, one hub that holds them all. 🟢 A tile for every tool, one click to open each.

An app, a website, a side hustle, a tool, a custom AI, a game, a workout program, a landing page, an extension — and now the hub. I can't write a line of code. Claude wrote all of it. Save this and start yours. 🔖 (The finale of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #nocode #aitools #vibecoding #buildinpublic #productivity
```

### TikTok (C)

**Caption:**
```
nine builds this season, zero code, all with AI 🟢 so I built a tenth — one hub to hold them all. The Stack: a tile for every tool, one click each. that's the season. Claude wrote every line. (the finale of Build With AI 🛠️)
```

**Hashtags:**
```
#buildwithai #claude #nocode #aitools #vibecoding #fyp
```

### Thumbnails

**A — for Variant A (YouTube · dashboard):**
- Icon: 🗂️  ·  Scheme: Lime
- L1: `NINE BUILDS` — White / MD
- L2: `ZERO CODE` — Lime / XL
- L3: `THE 10TH` — Lime / LG

**B — for Variant B (Instagram · app-chrome HERO):**
- Icon: 🏆  ·  Scheme: Lime
- L1: `10 THINGS` — Lime / MD
- L2: `ONE HUB` — White / XL
- L3: `ALL WITH AI` — Lime / LG

**C — for Variant C (TikTok · illustrated):**
- Icon: 🔟  ·  Scheme: Lime
- L1: `NO CODE` — Lime / MD
- L2: `I BUILT 10` — White / XL
- L3: `THE FINALE · WATCH` — Lime / LG

### Build changes / notes
- Same VO across all 3 cuts (Kokoro `am_adam`, 5 beats: 4.95 / 5.72 / 5.14 / 5.16 / 4.12s ≈ 25s; BGM 0.15). 5-scene **38s**; scenes abut at 0 / 6.5 / 14 / 21.5 / 29.5.
- 🟢 **Lime `#84E000` + `#9FFF00` on near-black `#0A0C0A`** (results/finale slot; also the AIToolsDaily24 brand color — the hub is a launcher for that brand). Fonts: Bebas Neue + IBM Plex Mono (built-in).
- Demo = **"The Stack"** — a hub/launcher page (invented as the capstone; user picked "one capstone build"). Scene-4 payoff across all cuts = a **3×3 grid of all 9 season builds** (emoji + name + category tag), "10 built · 0 code." Closes the "this site was built the same way" thread (V32/V33/V36/V38) — the hub belongs to AIToolsDaily24. CTA copy shifts from "follow for the build" to a season wrap ("that's the season · thank you for watching").
- **Sources kept** in-folder (a-youtube/b-instagram/c-tiktok + audio/). A cover baked (+2s). Whisper smell test ≥ 95%. **Series COMPLETE: 40/40.**

### Posting cadence
- YouTube Shorts first · Tue/Thu, 12–3pm EST
- Instagram Reels follow-up · Mon/Wed, 11am–1pm EST
- TikTok daily, 7–9am or 7–9pm EST

---

## Output locations

- **Videos:** `Videos/Build_With_AI/<NN-slug>/<NN-slug>.mp4` (+ `NNb`, `NNc`) — MP4-only, Vol 2 style
- **Blog posts:** `Go_Live/build-with-ai/<NN-slug>.html`
- **Thumbnail generator:** [`Apps/thumbnail-generator-v4.html`](Apps/thumbnail-generator-v4.html) — now supports a **focal photo/screenshot** (upload, replaces the emoji); the `thumbnail-maker` agent reads `Image: <path>` from a cut's spec. Source photos in `Assets/pexels/`. **Rule: give each cut a distinct focal visual — never reuse one emoji across cuts** (the C/TikTok cuts all shared 👀 until 2026-06-28, now Pexels photos).
- **Blog template:** [`blog-post-template.html`](blog-post-template.html)
- **Series brief:** [`Prompt Files/Vol4-BuildWithAI.md`](Prompt%20Files/Vol4-BuildWithAI.md)
