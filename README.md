# CCUS Pathways – Interactive Simulator

Personal project exploring the trade-offs in **Carbon Capture, Utilization and Storage (CCUS)** with a simple, transparent Python model.

- Adjust assumptions (costs, energy use, grid carbon intensity, deployment scale)
- Explore multiple simulation modes
- View interactive outputs via Voilà

[![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mmarkko/CCUS-Sim/HEAD?urlpath=voila%2Frender%2FCCUS_App.ipynb)

---

## Quick start (local)

```bash
# Clone this repository
git clone https://github.com/mmarkko/CCUS-Sim.git
cd CCUS-Sim

# (Recommended) Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Voilà
voila CCUS_App.ipynb
