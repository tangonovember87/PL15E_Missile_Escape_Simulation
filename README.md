# PL-15E Missile Escape Simulation

This project simulates how different types of Electronic Warfare (EW) behavior and aircraft maneuvers impact a fighter jet’s chances of escaping an incoming PL-15E air-to-air missile.

---

## 📌 Key Features
- Missile seeker activation at **25 km** with **±60° FOV**
- Realistic **pilot reaction delays** based on EW behavior:
  - Autonomous: 0.5–1.2s
  - Semi-Auto: 1.5–3.0s
  - Manual: 2.0–5.0s
- 4 evasive maneuvers with G-limit constraints:
  - Break Turn (6.5–9.0g)
  - Split-S (6.0–8.5g)
  - Barrel Roll (5.0–7.0g)
  - Zoom Climb (4.5–6.5g)
- ECM effectiveness modeled by tier:
  - Autonomous: 0.80
  - Semi-Auto: 0.65
  - Manual: 0.45
- Monte Carlo simulation with **1000 trials per behavior type**

---

## 📊 Visualizations Included
- Escape rate vs EW system
- Escape rate by maneuver
- Escape rate vs reaction delay
- Maneuver × EW heatmap
- G-load vs delay scatter
- Boxplot of reaction time distribution

---

## 📁 Files
- `PL15E_SIM.ipynb`: Full simulation notebook with logic & plots
- `summary_infographic.png`: Optional visual summary (if generated)
- `README.md`: Project overview and documentation

---

## 💡 Insights
- Delay and maneuver aggressiveness impact survival dramatically
- Autonomous EW (like SPECTRA) consistently provides higher escape rates
- Combining ECM + high-G evasive maneuvers improves success probability

---

> ✈️ Built using Python, Matplotlib, Seaborn, and Data Science logic for realistic air combat simulation

