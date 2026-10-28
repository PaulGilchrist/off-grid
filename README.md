# Brinkley Model Z 2680 — Victron Off-Grid Build (24 V)

A single-page reference site documenting the off-grid electrical expansion for a **Brinkley Model Z 2680** travel trailer, built around Victron Energy gear on a **24 V** system: a **MultiPlus-II 24/3000-70** inverter/charger, two extra **MPPT 100/50**s (three total — factory roof + two portable MC4 inlets), an **Orion XS 1400 12/24-50** DC-DC charger (alternator charging via a dedicated 4 AWG + Anderson truck feed — the XS input-limits at 50 A, so 1 AWG would be overkill), an **Orion IP67 24/12-100** converter feeding the factory 12 V panel (the WFCO stays in place but is fully disabled), a **SmartShunt**, a bolt-stacked pair of **Lynx Distributors** (each has only 4 fused branch slots, so six circuits need two), and a 6-battery **LiFePO4** bank in 2S3P (24 V · 900 Ah · ~21.6 kWh).

**🌐 Live site: <https://paulgilchrist.github.io/off-grid/>**

## What's in it

The site is a self-contained build reference — everything you need to plan, buy, fabricate, and commission the system:

| Section | Contents |
|---|---|
| **System Diagram** | Existing (factory) vs. new wiring, colour-coded. Only two factory cuts are required: the shore/generator splice at the Power Center and the WFCO converter output (disabled). The truck feed is a 4 AWG circuit + MRBF 60 A to an Anderson quick-disconnect at the hitch. Everything else is additive. |
| **Wire Schedule** | Gauges and estimated lengths for every run — 2/0 for the MultiPlus and battery series/parallel links, 4 AWG for the DC-DC units and the truck feed, 2 AWG for the 12 V panel feed — with the rule: *measure before you cut*, add 10–20% slack, flexible stranded only (Class K welding cable ≥ 6 AWG, never solid house wire in a vehicle). |
| **Cable Guide** | A beginner's walkthrough of fabricating cables: vocabulary, tool kit, the 6 rules of a proper crimp, torque cheat sheet, step-by-step cable recipes, and assembly/polarity discipline. |
| **Battery Tray** | Tray sizing for the Vatrers LiFePO4 batteries (15.12″W × 7.64″D × 9.76″H, M8 top terminals, + upper-right / − lower-right) — the factory GC27 slots can't take them, so a flat tray is built; 2×3 layout (45.36″W × 15.28″D, all six required) — pairs wired in series front-to-back, then all three paralleled. |
| **Parts List** | Major components, protection & distribution, terminals, consumables, and mounting hardware. |
| **Monitoring & Comms** | Which devices speak Bluetooth (MPPTs, Orion XS, SmartShunt) and which don't — the MultiPlus-II 120 V gets a VE.Bus Smart dongle for Bluetooth plus an MK3-USB for firmware; the Orion IP67 has no comms (metered via the SmartShunt). Includes VE.Smart network setup and the Cerbo GX/VRM upgrade path (deliberately skipped). |
| **Tool List** | Everything needed to make the cables and do the install. |
| **Install Instructions** | Phased plan: verify (½ day) → practice weekend → battery bank & tray (three series pairs, equalize, parallel) → MultiPlus-II (the core job) → MPPT #2 + #3 + two MC4 inlets → Orion XS + Orion IP67 DC-DC → commissioning checklist. |
| **Budget** | Cost breakdown for the whole build. |

## How it works

No framework, no build step — just one `index.html` with inline CSS and SVG diagrams. GitHub Pages serves it straight from the `main` branch.

## Contributing

1. Clone the repo and open `index.html` in a browser — that's the whole dev environment.
2. Make your changes, keep the section structure and colour-coding conventions intact (blue/gray/purple = factory, orange/red/green = new).
3. Push to `main` and GitHub Pages republishes automatically.

## License

[MIT](LICENSE)
