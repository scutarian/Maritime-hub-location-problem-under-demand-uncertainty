# Maritime hub location problem under demand uncertainty (MHLRPU)
## Experiment Data Folder

The **`data/`** directory contains the problem instances used in the computational experiments.  
Each subfolder corresponds to a specific data set **X**, and includes the following files:

1. **Demand flows for scenarios 1–3:**  
   Each folder includes the flow matrices for breakpoints 2–4 of the possibility distribution of flows.  
   For example, the flow matrix of *MED20* at breakpoint 2 is stored as:  
   `flows2_MED20.txt`

2. **`caphubport_X.txt`** – contains:  
   - Row 1: hub capacities  
   - Row 2: hub location costs  
   - Row 3: unit port costs  

3. **`distances_X.txt`** – sea distance matrix.

4. **`names_X.txt`** – list of terminal names for data set *X*.

5. **`shipping_costs_X.txt`** – unit mainline and feeder vessel costs.

6. **`flows_X.txt`** – base flow data for the respective set.

---

# Notes
- File naming follows a consistent pattern for easy reference across data sets.  
- All files are provided in `.txt` format for straightforward use with C++/CPLEX scripts.


# Citation

If you use these data files or refer to this work, please cite:

Butun, C., Petrovic, S., Muyldermans, L., *Hub location–routing under demand uncertainty: A vertical integration perspective in maritime transportation* (Manuscript in review, 2026).


# License

This repository is shared for **academic and research purposes only**.  
Please contact the author for permission before any commercial use.

