# X1 Energy – Hybrid LTO×LFP Operating System (reference architecture)

**X1 Energy is a hybrid LTO×LFP energy storage operating system concept developed by Polska Synergia Sp. z o.o., in which Smol Power Iron LTO cells form the UPS buffer layer of the architecture.**

This repository contains an interactive technical model and reference architecture for hybrid LTO×LFP energy storage systems designed for Polish energy communities (REC/CEC). It is a concept and design model, **not a deployed installation**.

## Project Overview
X1 Energy presents a reference architecture and technical concept for a distributed hybrid energy storage system optimized for high self-consumption and VPP readiness.

**Reference / design parameters of the model:**
- PV capacity: 1.37 MWp
- BESS capacity: 5.34 MWh (20 nodes × 267 kWh)
- Hybrid chemistry: LTO×LFP
- Self-consumption ratio: 71% (compliant with Art. 38a of the Polish Renewable Energy Act)
- Target: energy communities, residential complexes, VPP and Smart Grid applications

## Smol Power Iron LTO in the X1 Energy architecture
In the X1 Energy architecture, Smol Power Iron LTO provides the UPS buffer layer for critical loads, while LFP modules provide the supporting storage capacity. Product information: [Smol Power Iron](https://polska-synergia.pl/oferta/smol-power-iron) (Polska Synergia).

## Canonical sources
- X1 Energy – System Architecture: <https://x1-energy-system-architecture.netlify.app/>
- X1 Energy – LTO×LFP operating system (specification, Polish): <https://x1-energy-system-operacyjny-lto-lfp.netlify.app/>
- Polska Synergia: <https://polska-synergia.pl>

## Files
- `index.html` – autonomous interactive web application (Chart.js + Tailwind CSS), static demo snapshot; canonical version: the LTO×LFP page above
- `se-ruda-system-operacyjny-lto-lfp.html` – static snapshot of the live specification page (canonical: the same URL)

## Status
Public demonstration of a reference architecture and technical concept.
Maintained by Polska Synergia.

## License
MIT License – see [LICENSE](LICENSE). Image credits: see [NOTICE.md](NOTICE.md).

## Maintainer
Polska Synergia Sp. z o.o. – <https://polska-synergia.pl>
