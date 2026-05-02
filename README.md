# Model Simulation for Wheat Growth (GroIMP)

This repository contains the source code and configuration files for the model described in our paper. The simulation is implemented using the **GroIMP** (Growth Grammar Interactive Modeling Platform).

## 🛠 Prerequisites

The model requires the GroIMP platform to run:
* **Download/Install:** [https://gitlab.com/grogra/groimp](https://gitlab.com/grogra/groimp)
* **Official Website:** [www.grogra.de](http://www.grogra.de)

## 🚀 Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/你的用户名/你的仓库名.git](https://github.com/你的用户名/你的仓库名.git)

## Parameter Files

- `Parameter.rgg`  
  → General model parameter file  

- `Parameter4.rgg`  
  → Parameter file for cereal simulations  

- `wheatParameters.txt`  
  → Contains the parameter values used in the manuscript, including:  
  - Historical model  
  - Modern model  

---

## Parameter Configuration

- The parameters in `wheatParameters.txt` must be copied into `Parameter4.rgg` before running the model.  
- `Parameter4.rgg` is the active parameter file used for cereal simulations.  

- Modify the density values in `Parameter4.rgg` to simulate:
  - Low-density conditions  
  - High-density conditions  

---

## Running the Model

After completing all parameter settings:

- Click **"Run run"** in GroIMP  
- The model will run automatically  

---

## Output

After the simulation finishes:

- Output results are saved as `.txt` files  
- The output location is defined by the parameter: `pathData`
