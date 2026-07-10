# Cyril Mathew

Financial advisor (Series 7/63/65) at an RIA. I build the tools I wish existed at work — for the meeting, the data entry, and the trade planning that fill an advisor's actual week. Everything below is software I use in my own workflow, published with synthetic data.

## The advisor tool suite

| [Money Map](https://github.com/cmathew654-dot/money-map) | [eMoney Holdings Injector](https://github.com/cmathew654-dot/emoney-holdings-injector) | [CDS Trade Assistant](https://github.com/cmathew654-dot/cds-trade-assistant) |
|-|-|-|
| [![Money Map canvas](https://raw.githubusercontent.com/cmathew654-dot/money-map/main/docs/media/theme-stewardship.png)](https://cmathew654-dot.github.io/money-map/) | [![Regulated Ledger review](https://raw.githubusercontent.com/cmathew654-dot/emoney-holdings-injector/main/docs/media/landing.png)](https://cmathew654-dot.github.io/emoney-holdings-injector/) | [![Sell workbench](https://raw.githubusercontent.com/cmathew654-dot/cds-trade-assistant/main/docs/media/workbench.png)](https://github.com/cmathew654-dot/cds-trade-assistant) |
| Client-meeting canvas for account flows — tiles, editable money flows, presentation mode. Vanilla JS + SVG, 1,365 tests. **[Live demo](https://cmathew654-dot.github.io/money-map/)** | Human-gated CSV → eMoney holdings entry. Every row verdicted before a bookmarklet types it; Save is always manual. **[Live demo](https://cmathew654-dot.github.io/emoney-holdings-injector/)** | Excel VBA trade planning: holdings → raise-cash scenarios → sell workbench → math audit → trade email draft. ~8,300 lines, screenshots from real runs on synthetic data. |

Together they cover an advisor's data world: the client conversation (Money Map), held-away account entry (Injector), and managed-account trade planning (CDS).

Also: **[Video Compressor Web](https://github.com/cmathew654-dot/video-compressor-web)** — zero-install, in-browser video compression (WebCodecs); files never leave your machine. **[Try it](https://cmathew654-dot.github.io/video-compressor-web/)**

## How these get built

I'm the domain expert and product owner; I design the workflows, write the specs, drive AI-assisted implementation, and gate everything through tests and my own daily use. The safety models (local-only, human-in-the-loop, no auto-save) come from working under a fiduciary standard.

📫 c.mathew654@gmail.com

