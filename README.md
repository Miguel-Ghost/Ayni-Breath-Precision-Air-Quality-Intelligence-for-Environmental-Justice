# Ayni Breath  
### *Air Quality Intelligence with Scientific Rigor & Environmental Justice*

> **"Ayni"** (Quechua): *Reciprocity — the sacred balance of giving and receiving.*  
> In the spirit of *ayni*, **Ayni Breath** gives communities the truth about their air — so they can protect their health, hold polluters accountable, and breathe with dignity.

---

## Overview

**Ayni Breath** is a scientifically precise, retro 2D–inspired mobile application that transforms **NASA’s TEMPO satellite data**, **ground-based air quality sensors**, and **real-time meteorology** into actionable, hyperlocal air health insights for the United States.

Unlike generic AQI apps, Ayni Breath calculates the **official US EPA Air Quality Index (AQI)** with full technical fidelity — including **dynamic unit conversion**, **correct averaging times**, and **strict truncation rules** — ensuring every alert is grounded in atmospheric science, not approximation.

But we go further: by overlaying pollution plumes with EPA facility registries, Ayni Breath reveals **who is likely polluting your air**, empowering environmental justice and community advocacy.

---

## Scientific Foundation

Ayni Breath implements the **exact methodology** defined by the US EPA and detailed in NASA’s technical guidance:

- ✅ **Dynamic unit conversion** (ppb ↔ µg/m³) using real-time temperature:  
  `µg/m³ = (ppb × 12.187 × M) / (273.15 + T)`  
- ✅ **Correct averaging times**:  
  - NO₂: 1-hour  
  - O₃: 8-hour  
  - PM2.5: 24-hour  
- ✅ **Truncation before interpolation** (e.g., PM2.5 = 12.09 → 12.0)  
- ✅ **Dominant pollutant logic** — reports the highest-risk AQI value  
- ✅ **Breakpoint-based linear interpolation** per EPA tables  

> *All formulas and logic derived from NASA’s official documentation and EPA Technical Assistance Document.*

---

## Key Features

- **Retro 2D UI** – Inspired by 90s sci-fi consoles, but fully accessible and mobile-optimized  
- **Source Attribution** – Links TEMPO NO₂ plumes to EPA ECHO industrial facilities  
- **Community Pulse** – Anonymous symptom reports from neighbors (opt-in)  
- **Justice Lens** – Compare your exposure to city/national averages  
- **Offline-Ready Alerts** – Voice-friendly, low-literacy warnings for vulnerable users  
- **Open Data** – Built entirely on public, open-source environmental data  

---

## License

This project is open source under the **MIT License** — because clean air is a public good.

---

## Acknowledgements

- **NASA** and the **International Space Apps Challenge** for open data and global inspiration  
- **EPA**, **OpenAQ**, and **Pandora Network** for ground-truth validation  
- Communities on the frontlines of air pollution — you are our why.

---

> **Breathe well. Demand better. Practice ayni.**
