# The LeBron Multiplier — DataFest 2025

**Team D11 — Kirtan Bhatt, Derek Diaz, Daren Sathasivam, Ethan Shahzad**  
UCLA DataFest 2025 | Los Angeles & South Bay Market

---

## Project Overview
This project explores whether companies can **optimize lease timing** by monitoring **vacancy rates** to predict **future rent growth**.  
Using proprietary commercial real estate data provided by the DataFest organizers, our team focused on identifying actionable thresholds and classifying economic regimes to guide leasing decisions.

---

## Key Findings
- **Vacancy ↔ Rent Correlation:** Strong relationship with a Pearson coefficient of **0.92**.  
- **Market Threshold:** A **~20% vacancy rate** effectively separates tenant-favorable and landlord-favorable conditions.  
- **Economic Regimes:**  
  - **Expansion:** Declining vacancy with positive rent growth.  
  - **Contraction:** Rising vacancy with softening rents.  
  - **Stagnation:** Flat trends in both indicators.

---

## Strategic Insights
- **Falling vacancy + rising rent → expansion:** act quickly to secure favorable terms.  
- **Rising vacancy + softening rent → contraction:** delay commitments or negotiate aggressively.  
- **High vacancy rates** signal tenant leverage, while **low vacancy rates** favor landlords.

---

## Methods
- Calculated **forward rent growth** (t + 2 quarters) against vacancy rates.  
- Conducted **threshold scans** to identify optimal splits (~18–20%).  
- Classified **economic regimes** based on vacancy trend direction and rent growth sign.

---