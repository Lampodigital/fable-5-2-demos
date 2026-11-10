# Claude Fable 5.2: the demos worth seeing

A curated, sourced list of what people built with Anthropic's Claude Fable 5.2 in its first day. It covers videos, playable builds, official showcases and the sceptical takes. Every item links to the original post, and each one is labelled by how far it can be verified.

Curated by **Stefano Rossi (Lampodigital)**. Snapshot: 10 November 2026. Metrics are public X counts at the time of the snapshot, where "views" means impressions, and they keep changing. The machine-readable list is in [`demos.json`](demos.json) and [`demos.csv`](demos.csv).

> No video files are hosted here. All media belongs to its authors; follow the links to watch.

## What Anthropic says (official facts)
Sources: [announcement](https://www.anthropic.com/claude-fable-and-mythos-5-2) · [model docs](https://platform.claude.com/docs/en/models/fable-5-2/overview) · [Mythos docs](https://platform.claude.com/docs/en/models/mythos-5-2/overview) · [system card (PDF)](https://assets.claude.com/27d60918d218125e7504bc7354c4b4626ec56b11.pdf)

- **Release:** 9 Nov 2026. Model ID `claude-fable-5-2`, 1M-token context, 128K max output.
- **Price:** $8 / $40 per million input/output tokens, down from $10 / $50. Fast mode (up to 2.5× faster) costs $16 / $80. Output is up to 30% faster than Fable 5.1.
- **Fable vs Mythos:** the same underlying model. Fable is generally available with cybersecurity and biology safeguards. Mythos is limited to vetted organisations through Anthropic's Cyber and Life Sciences Verification Programs.
- **Positioning:** Anthropic recommends Opus 5.5 as the everyday model and Fable for the most ambitious, open-ended technical work.
- **Examples Anthropic reports from prerelease testing:**
  - A prototype operating system built from an empty folder by more than 1,000 subagents over 8 days. It boots on a laptop.
  - Three working electronic devices designed from a one-paragraph prompt and manufactured with Diode.
  - Fermat's Last Theorem formalised in Lean by 1,000 agents in 30 hours.
  - Two open problems in black-hole physics solved. The preprints are not yet peer-reviewed.
  - Real robot arms controlled through Claude Code.
- **Selected benchmarks (Anthropic's table):**
  - FrontierSWE v2: 69.9%
  - FrontierCode 2.0: 49.1% (Xhigh effort)
  - OSWorld 2.1: 89.3%
  - RoboDojo Sim: 64.9%
  - Humanity's Last Exam with tools: 74.2%
  - On AutomationBench, Gemini 4 Carbon scores higher (53.9% vs 51.4%).
- **No official video of the operating system build was found** on Anthropic's X accounts or YouTube channel as of this snapshot.

## Verification labels
- **Official (Anthropic):** published by Anthropic or Claude accounts.
- **Author's claim, corroborated:** the author's own account, plus something checkable: a playable build, a live stream with witnesses, an independent reproduction, or published code.
- **Author's claim only:** posted by the author, with nothing independent found.
- **Vendor promo, author's claim:** a company promoting its own tool alongside Fable.
- **Unverified (small account):** low reach and no corroboration.

"One prompt" and "one-shot" are always the authors' wording. Costs and times are self-reported unless marked official.

## The demos (ranked by visual impact)
| # | Demo | Author | What it shows | Views / likes | Length | Verification |
|---|---|---|---|---|---|---|
| 1 | [Saltline: browser FPS built from one-shot prompts](https://x.com/felixrieseberg/status/2119925633564463609) | Felix Rieseberg (@felixrieseberg, Anthropic) | Photoreal first-person shooter in a rainy cargo port. Author says every model, sound and texture was generated from scratch in about 8 hours for about $550 at API pricing (445M input tokens, mostly cached; 2.7M output). | 897,598 / 6,409 | 72 s | Author's claim, corroborated |
| 2 | [Destructible voxel city in the browser](https://x.com/mattshumer_/status/2119870965106483384) | Matt Shumer (@mattshumer_) | Voxel city where buildings, castles and bridges blow apart into debris and fire. The author says it came from a single prompt, and the post links a playable demo. | 189,222 / 656 | 59 s | Author's claim only |
| 3 | [Rainy Tokyo alley written in code](https://x.com/higgsfield_ai/status/2119905141822484595) | Higgsfield (@higgsfield_ai) | Photoreal night alley with rain, neon reflections, a working street mirror and readable signs. The post says no video model was used. | 8,239 / 45 | 15 s | Vendor promo, author's claim |
| 4 | [Cinematic dragon shot in Blender](https://x.com/dinosaurbtuq/status/2120078384231542953) | @dinosaurbtuq | Dragon breathing fire over a snowy peak. Author says Fable built the mesh, rig, fire sim and camera in Blender for $23. | 70 / 5 | 8 s | Unverified (small account) |
| 5 | [Mexico City market in code](https://x.com/higgsfield_ai/status/2119906341078945977) | Higgsfield (@higgsfield_ai) | Market street scene with paper flags, a piñata and fruit stalls with prices, all rendered from code. | 9,991 / 102 | 15 s | Vendor promo, author's claim |
| 6 | [Minecraft-style clone](https://x.com/intheworldofai/status/2119975670650450426) | @intheworldofai | Voxel sandbox game with HDR shaders, volumetric clouds and reflective water. Author claims 24K lines of TypeScript and 859 tests from one prompt. | 4,199 / 104 | 183 s | Author's claim only |
| 7 | ['The Edge': 4K Blender film from one prompt, live on stream](https://x.com/rileybrown/status/2119902109709537708) | Riley Brown (@rileybrown) | Fable wrote Blender code for a full room, animated 13 shots, rented 10 RunPod GPUs and rendered in 4K in 52 minutes for $5.75. Music and SFX were made with ElevenLabs. | 440,715 / 4,739 | 59 s | Author's claim, corroborated |
| 8 | [Fable 5.2 controls real robot arms](https://x.com/claudeai/status/2119867132452221045) | Claude (@claudeai, official) | Two off-the-shelf robot arms driven through Claude Code solve a puzzle cube, unscrew a bottle cap, fit a gear and draw a robot. | 2,006,281 / 8,644 | 23 s | Official (Anthropic) |
| 9 | [1 km² of Indiranagar from map data](https://x.com/anshu4321/status/2119938067758772403) | @anshu4321 | 3D rebuild of a real Bangalore neighbourhood with a day-to-night shift and a metro line, made from map data and one prompt. | 6,452 / 159 | 35 s | Author's claim only |
| 10 | [Rocket launch to orbit simulation](https://x.com/Shannnu_18/status/2120025125076844785) | @Shannnu_18 | Browser rocket simulation from the pad to a 210 km orbit. Author says it uses gravity, drag, thrust and guidance. | 476 / 15 | 135 s | Author's claim only |
| 11 | [Portals: 450+ code-drawn worlds](https://x.com/emollick/status/2119918307457577163) | Ethan Mollick (@emollick) | Endless fly-through of worlds linked by portals. Mollick says 25,000 agent runs built them, and the agents wrote themselves an 87,500-word rulebook. | 68,245 / 1,360 | 70 s | Author's claim, corroborated |
| 12 | [Rigged zombie hand in Blender](https://x.com/higgsfield_ai/status/2119893970897490135) | Higgsfield (@higgsfield_ai) | Rigged hand model that crawls, backflips and gestures. | 42,393 / 677 | 19 s | Vendor promo, author's claim |
| 13 | [Realtime honey simulation in WebGL](https://x.com/deedydas/status/2119930300990177509) | Deedy Das (@deedydas) | Physics-based honey pour rendered in real time in the browser. | 35,580 / 324 | 51 s | Author's claim only |
| 14 | [Home voice-assistant hub designed by Fable](https://x.com/claudeai/status/2119899459761131615) | Claude (@claudeai, official) | Device designed from a one-paragraph prompt: spec, components, four-layer PCB, enclosure and firmware. Diode manufactured the boards. | 2,771,462 / 27,692 | 48 s | Official (Anthropic) |
| 15 | [Fishslop game run](https://x.com/theo/status/2119926277801144695) | Theo (@theo) | Underwater game built in 76 minutes for about $42. The author says it is 'not significantly better than Opus 5.5'. | 103,381 / 1,885 | 77 s | Author's claim only |
| 16 | [Code-painted 'photo' with ~700,000 strokes](https://x.com/jkeatn/status/2119874018706874601) | Jake Eaton (@jkeatn, Anthropic) | Still image of a parking garage painted stroke by stroke in a simulated paint engine. Author says no image model was used. | 213,978 / 1,441 | image | Author's claim only |

### Notes on the three most-shared videos
- **Saltline (Felix Rieseberg):**
  - The author is an Anthropic engineer (per his X bio).
  - The game is playable at [claude.ai/artifact/BGY1SztrAYcJQHSsnHHGmp](https://claude.ai/artifact/BGY1SztrAYcJQHSsnHHGmp).
  - He shared the prompt in a [reply](https://x.com/felixrieseberg/status/2119927483994907024). It begins "You know, you should also build me a FPS", which suggests it ran inside an existing session.
  - The cost (~$550), duration (8 h), token counts and "no human feedback" are self-reported.
- **The Edge (Riley Brown):**
  - Posted as done live on stream. A viewer [says they watched it live](https://x.com/ZeroFoundry/status/2119902437549191569).
  - There is a [making-of artifact](https://claude.ai/artifact/QGWUAjRrzRzZWGcQzSMLfa).
  - Roberto Nickson [got a similar result](https://x.com/rpnickson/status/2119969928304357507) with his own studio photos.
  - The prompt, as quoted by repliers, refers to making a video "using Blender like we have in the past". Riley had shared a Blender video workflow with Opus 5.5 earlier the same day ([post](https://x.com/rileybrown/status/2119651130963537996)), so "one prompt" sat on top of an existing workflow.
  - The $5.75 figure covers the GPU render; token cost was not stated.
- **Robot arms (Anthropic):**
  - Official footage, also on Anthropic's announcement page.
  - On-screen labels show it is sped up with pauses cut (for example "8× · pauses cut").
  - The 64.9% RoboDojo figure is a separate *simulated* benchmark, not a reliability measure for these physical demos ([RobotsBeat](https://robotsbeat.com/claude-fable-5-2-robotics-robodojo-astra-gemini-opus/)).

## Sceptical voices
- **Theo:** a 76-minute, ~$42 run was "not significantly better than Opus 5.5 (esp. for the price)" ([post](https://x.com/theo/status/2119926277801144695)). He also says 5.1→5.2 is a smaller jump than Opus 5→5.5 ([post](https://x.com/theo/status/2119940638603182590)).
- **Ethan Mollick:** calls it "Jagged AGI". In his tests the model did not notice when its own work was too long, joyless or bureaucratic ([essay](https://www.oneusefulthing.org/p/fable-52-and-jagged-agi)).
- **Token use:** Fable 5.2 is cheaper per token but used about 3× more tokens than 5.1 on painting tasks ([kickingkeys](https://x.com/kickingkeys/status/2119945849371525288)). "'One shot' just makes it sound free" ([Vikramaditya_V1](https://x.com/Vikramaditya_V1/status/2119963604888048071)).
- **Hacker News:**
  - Some users find it hard to tell from Opus 5.5 on ordinary coding, and some report it burns through usage limits quickly ([launch thread](https://news.ycombinator.com/item?id=50429068)).
  - One benchmark author saw more game depth but no visual leap ([comment](https://news.ycombinator.com/item?id=50433004)).
- **Claire Vo** (via a podcast summary): strong at motion and 3D, weaker at unassisted web design and standalone images ([summary](https://www.thepodcastsummary.com/episodes/1gYQc4CL_oo/ai-video-generation-tweet-to-animated-explainer.html)).

## Sources
- Anthropic announcement: https://www.anthropic.com/claude-fable-and-mythos-5-2
- System card: https://assets.claude.com/27d60918d218125e7504bc7354c4b4626ec56b11.pdf
- Model docs: https://platform.claude.com/docs/en/models/fable-5-2/overview
- CNBC coverage: https://www.cnbc.com/2026/11/09/anthropic-claude-fable-5-2-mythos-5-2.html
- Ethan Mollick, "Fable 5.2 and Jagged AGI": https://www.oneusefulthing.org/p/fable-52-and-jagged-agi
- Hacker News launch thread: https://news.ycombinator.com/item?id=50429068
- RobotsBeat on the robotics claims: https://robotsbeat.com/claude-fable-5-2-robotics-robodojo-astra-gemini-opus/
- Interesting Engineering on the OS build: https://interestingengineering.com/ai-robotics/anthropic-claude-fable-5-2-operating-system
- Individual demo posts: see the table above and `demos.json`.

Corrections welcome. Open an issue with a source link.
