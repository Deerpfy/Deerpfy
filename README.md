# Deerpfy

Co-founder and developer at [SZEINER s.r.o.](https://szeiner.com), Czech Republic. I build code-protection tooling, project software, and web tools that run without ads, accounts, or trackers. Video games are the hobby side.

## Products
Check it out:
- **[BetterGuard](https://betterguard.net)**: obfuscation and anti-tamper for C# and .NET, delivered as a hosted service.
- **[Synteum](https://synteum.com)**: project and ticket management: epics, sprints, boards, time tracking. Runs live in the browser, no account required.
- **[BetterPlugins](https://www.fab.com/sellers/SZEINER)**: Unreal Engine plugins on Fab: BetterArgon2, BetterConfig, BetterMyIP, BetterRHI, BetterBPChecker.
- **BetterTranslator** free translation app running entirely on local models. The LM Studio runtime (llmster) serves TranslateGemma and EuroLLM, with a lightweight RAG index carrying terminology and prior decisions across a document set.
- **Cycle**: free cycle tracking app for Android and iOS. Works offline with no account, encrypts entries on device, and
  shares chosen details with one paired partner.

> [!TIP]
> The board at [synteum.com](https://synteum.com) is the real app, not a recording. Paid plans are not open yet.

## Open source
Proud of:
- **[adhub](https://github.com/Deerpfy/adhub)** free browser tools and extensions. No ads, no subscriptions, no telemetry.
- **[bettercapture](https://github.com/Deerpfy/bettercapture)** captures a page as snapshot, meta.json, and offline.html, ready to hand to an AI.
- **[betterbookmarks](https://github.com/Deerpfy/betterbookmarks)** saves prompts as bookmarks. Offline, nothing leaves the browser.

## Hardware
Boards, firmware, and the enclosures around them. Raspberry Pi 5, ESP32, and several Arduino boards.
- **LED and audio visualisation** ESP32-C3 firmware with a Go host driving addressable strips from a live audio signal.
- **Enclosures and controls** 3D-printed parts designed in Fusion 360 and printed on a Bambu A1, including slider knob caps fitted to real potentiometer hardware.

## What I work with

C# and .NET internals, C++, Go, PHP and Laravel, Chromium MV3 extensions, Unreal Engine.

## AI tooling

I build the tooling I work through, not just the products. Everything below is mine and in daily use.

- **Claude Code skills** versioned agents with fixed rule catalogs and hard gates: prompt generation, documentation and PDF auditing, EU compliance review (GDPR, CRA, NIS2, AI Act, ISO 27001 and 42001), secure-coding catalogs for C#, Android, and iOS, and a design system layer.
- **Prompt engineering** the parts that decide whether an agent finishes: harness design around the model, loops that check their own output and re-enter on failure, and context engineering so the window carries the right slice of a repository instead of all of it.
- **Image generation** Nano Banana 2/Pro for product and marketing visuals, driven from a written specification with fixed views, lighting, and negative constraints, so a render can be reproduced instead of re-rolled.
- **Local inference** a translation workflow that plugs into Claude Code CLI and hands the work down to a local model as a subagent. PowerShell drives the passes on the LM Studio runtime, so the translation itself costs no API tokens and runs on hardware I already own.
- **MCP servers** a 72-tool Unreal Engine 5 server, and a generator that exposes only an explicitly allowlisted slice of a project instead of a whole API.

## Contact

[szeiner.com](https://szeiner.com) for company and product questions. Report a vulnerability privately through, never in a public issue.
