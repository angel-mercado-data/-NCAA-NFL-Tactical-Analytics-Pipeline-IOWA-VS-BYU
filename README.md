# -NCAA-NFL-Tactical-Analytics-Pipeline-IOWA-VS-BYU
[ Data Scraping & Tracking ]
│
▼
[ Python Data Pipeline ] ──► (Pandas / NetworkX / Matplotlib / Seaborn)
│
├── 1. Passing Networks & Target Allocation
├── 2. Defensive Density Maps (KDE & Box Counts)
├── 3. Correlated Expected Touchdown (xTD) Model
└── 4. Monte Carlo Game Script Simulation (1,000 Iterations)
│
▼
[ Executive X/Twitter Thread ]

* **Network Analysis (`NetworkX`):** Maps offensive passing routes, slot target shares, and defensive coverage alignments (e.g., 3-3-5 Drop 8 vs. 4-2-5 Press).
* **xTD Integration Model:** Blends tactical matchup differentials (*Heatmaps*) with Red Zone opportunity volume to project player touchdown probabilities.
* **Monte Carlo Simulation Engine:** Runs 1,000 game-script iterations to output win probabilities, score distributions, and yardage baselines.
* **X-Thread Formatting Pipeline:** Translates complex data into character-optimized, high-impact tweets for sports betting and tactical communication.

---

## 📊 Sample Case Study: Iowa State vs. BYU

### Key Model Outputs
| Metric | Iowa State Cyclones 🌪️ | BYU Cougars 🐾 | Differential / Advantage |
| :--- | :---: | :---: | :--- |
| **Projected Score** | **17** | **20** | BYU (-2.5) |
| **Monte Carlo Win %** | 40.0% | **60.0%** | BYU (+20%) |
| **Primary Slot Threat** | Jaylin Noel *(0.68 xTD)* | — | ISU +3.5 Matchup Advantage |
| **Ground Game Dominance** | Hansen/Sama *($\le$ 0.32 xTD)* | LJ Martin *(0.78 xTD)* | BYU #9 Rushing Defense (-4.5) |

---

## 📂 Repository Structure

```text
.
├── README.md                   <-- Case study documentation and pipeline overview
├── templates/
│   └── x_thread_template.md    <-- Character-optimized 4-tweet template for X/Twitter
├── notebooks/
│   └── iowa_state_vs_byu.ipynb <-- Full Python pipeline (Scraping, Monte Carlo, xTD)
└── outputs/
    └── visualizations/         <-- Exported passing networks, heatmaps, and simulation plots
