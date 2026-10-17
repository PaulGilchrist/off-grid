# Brinkley Model Z 2680 — Victron Off-Grid Build

A single-page reference site documenting the off-grid electrical expansion for a **Brinkley Model Z 2680** travel trailer, built around Victron Energy gear: a **MultiPlus-II** inverter/charger, a second **MPPT** for a portable solar array, an **Orion-Tr Smart** DC-DC charger (alternator charging), a **SmartShunt**, and a 3–4 battery **LiFePO4** bank.

**🌐 Live site: <https://paulgilchrist.github.io/off-grid/>**

## What's in it

The site is a self-contained build reference — everything you need to plan, buy, fabricate, and commission the system:

| Section | Contents |
|---|---|
| **System Diagram** | Existing (factory) vs. new wiring, colour-coded. Only two factory cuts are required: the shore/generator splice at the Power Center and the fused 7-way tap for the DC-DC charger. Everything else is additive. |
| **Wire Schedule** | Gauges and estimated lengths for every run — with the rule: *measure before you cut*, add 10–20% slack, flexible stranded only (Class K welding cable ≥ 6 AWG, never solid house wire in a vehicle). |
| **Cable Guide** | A beginner's walkthrough of fabricating cables: vocabulary, tool kit, the 6 rules of a proper crimp, torque cheat sheet, step-by-step cable recipes, and assembly/polarity discipline. |
| **Battery Tray** | Tray sizing for the Vatrers LiFePO4 batteries (15.12″D × 7.64″W × 9.76″H, M8 top terminals) — the factory GC27 slots can't take them, so a flat tray is built. |
| **Parts List** | Major components, protection & distribution, terminals, consumables, and mounting hardware. |
| **Tool List** | Everything needed to make the cables and do the install. |
| **Install Instructions** | Phased plan: verify (½ day) → practice weekend → battery bank & tray → MultiPlus-II (the core job) → MPPT #2 + MC4 inlet → Orion-Tr DC-DC → commissioning checklist. |
| **Budget** | Cost breakdown for the whole build. |

## How it works

No framework, no build step — just one `index.html` with inline CSS and SVG diagrams. GitHub Pages serves it straight from the `main` branch.

## Contributing

1. Clone the repo and open `index.html` in a browser — that's the whole dev environment.
2. Make your changes, keep the section structure and colour-coding conventions intact (blue/gray/purple = factory, orange/red/green = new).
3. Push to `main` and GitHub Pages republishes automatically.

## License

[MIT](LICENSE)
