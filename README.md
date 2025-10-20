# American-Option-LSM-Extension
Final exam for Dynamic programming at UCPH. Implementation and analysis of Longstaff–Schwartz Monte Carlo (LSM) for American option pricing including polynomial basis comparison, jump diffusion, quasi-Monte Carlo, and multi-asset extensions with neural network approximation.


---

## Repository structure
- `notebooks/` – Single- and multi-asset LSM implementations  
- `reports/` – Final written report and presentation slides  
- `Multiasset_environment.yml` – Environment file for the multi-asset notebook only  

## Reproducing results
1. Create environment (multi-asset only):
   ```bash
   conda env create -f Multiasset_environment.yml
   conda activate american-lsm
