Methane Mitigation Simulator
Interactive tool to estimate methane reduction, jobs created, and health co-benefits for dairy and rice supply chains using transparent, IPCC-style assumptions .

Overview
This repo contains a simple Python/Streamlit app that:

Takes basic company inputs (sector, annual volume, number of farms, coverage).

Applies fixed emission factors and intervention effectiveness values for dairy and rice.

Outputs estimated methane reductions, confidence ranges, jobs created, and DALYs averted.

Model assumptions
Sectors: Dairy and rice, selectable via a simple UI control.

Baseline emissions: Constant emission factors per litre of milk or tonne of rice, aligned with Tier 2-style factors you selected during model design.

Interventions: Feed additives / manure management for dairy; DSR / AWD for rice, each with fixed percentage reduction rates.

Co-benefits: Jobs created derived from a fixed jobs-per-tonne multiplier; DALYs and income uplift represented as simple, user-facing summary metrics.

Quick start
Install dependencies (Python 3.x): pip install streamlit numpy

Save the app file (for example methane_simulator.py) in your working directory.

Run locally: streamlit run methane_simulator.py and open the local URL in a browser.

Intended use
This tool is designed for:

Rapid, directional scenario analysis for corporate leaders and partners.

Preparing board- and investor-facing methane commitments with clear, reproducible logic.

It is not a replacement for full inventory development, detailed MRV, or project-level feasibility studies.
