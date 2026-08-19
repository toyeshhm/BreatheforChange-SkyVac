# BreatheForChange — SkyVac

Concept and public-facing site for **SkyVac**, a proposed fleet of AI-piloted
solar kites and balloons that capture soot, dust, and CO₂ directly from the
troposphere and convert it into usable materials.

**Live site:** https://skyvac.vercel.app

> SkyVac is a design concept with a staged development roadmap, not a deployed
> system. The capture figures below are design targets, not measured results.

## The idea

Ground-level air filtration treats symptoms in a single room. SkyVac targets the
troposphere instead — flying lightweight platforms into pollution hotspots and
pulling particulates out of the air where they actually accumulate, then feeding
the captured carbon back into a circular economy rather than storing it.

## How it works

| Component | Role |
|---|---|
| **Ultra-light electrostatic grids** | Flexible meshes that attract and capture soot, dust, and CO₂ at minimal energy cost |
| **AI navigation** | Steers units toward pollution hotspots in real time to maximize capture efficiency |
| **Self-powered platforms** | Flexible solar panels plus onboard storage keep units running through cloud cover and overnight |
| **Lightweight mesh networking** | Units exchange data and coordinate flight and capture patterns with each other |

## What captured carbon becomes

Rather than sequestering carbon as a cost centre, SkyVac routes it into four
product streams:

- **Carbon-infused concrete and brick** — construction materials with a reduced footprint
- **Verified carbon credits** — revenue from a measurable, auditable capture process
- **Advanced carbon materials** — feedstock for energy storage, water filtration, and industrial use
- **Agricultural enhancers** — soil amendments and fertilizers, closing the loop

## Design targets

| Target | Figure |
|---|---|
| CO₂ captured per unit per day | 100 kg (≈36.5 t/year) |
| Units deployed by 2027 | 1,000+ (≈36,500 t CO₂/year) |
| People reached by cleaner air | 50M across urban and industrial areas |
| Market value potential by 2030 | $2B from credits and materials |

## Roadmap

- **Q3 2025** — Kite and balloon prototypes with basic electrostatic capture; flight and energy-efficiency testing
- **Q4 2025** — AI navigation integration, mesh network testing, capture-algorithm tuning
- **Q2 2026** — Pilot program: 50 units in urban test areas, carbon processing partnerships
- **Q4 2026** — Commercial scale: 500 units across multiple cities, carbon credit program launch
- **2027+** — Global expansion past 1,000 units with franchise operations

## Who it's for

Residents in smoke- and dust-affected areas, schools and hospitals, local
governments taking on air-quality obligations, and operators running SkyVac
units as franchise businesses.

## Running it

A single self-contained `index.html` — no build step and no dependencies.

```bash
python3 -m http.server 8000    # then open http://localhost:8000
```

## Related

Companion to [BreatheforChange-NanoChar](https://github.com/toyeshhm/BreatheforChange-NanoChar),
the biodegradable nanocellulose–biochar air filter research presented at the
New York Academy of Sciences.

---

Part of the **Breath For Change** initiative · info@breathforchange.org
