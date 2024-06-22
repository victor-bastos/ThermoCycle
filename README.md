# ThermoCycleSim

## Overview

Welcome to ThermoCycleSim, a Jupyter Notebook project designed to automate the simulation of thermodynamic cycles. By leveraging Python and NASA's Chemical Equilibrium with Applications (CEA) program, this project provides a streamlined method to calculate and analyze various parameters in a thermodynamic cycle. The automated process simulates the behavior of fluids through different components like ducts, valves, pumps, and turbines, making it an efficient tool for both educational and research purposes.

## Features

- **Automated Thermodynamic Cycle Calculation**: Perform detailed simulations of thermodynamic cycles with minimal manual intervention.
- **CEA Integration**: Automatically compute combustion and other chemical equilibrium properties using NASA's CEA program.
- **Flexible and Adaptable**: The modular code structure allows for easy adjustments to different cycle configurations and fluid properties.
- **Comprehensive Output**: Generates detailed tables and outputs for all critical parameters, including pressures, temperatures, flow rates, and performance metrics.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Required Python libraries: numpy, pandas, scikit-learn, re, numpy, pyCEA

### Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/thermocyclesim.git
    cd thermocyclesim
    ```

2. Install the required Python libraries:
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1. Open the Jupyter Notebook:
    ```sh
    jupyter notebook ThermoCycleSim.ipynb
    ```

2. Follow the instructions within the notebook to run the simulations. The notebook includes cells for data loading, preprocessing, model execution, and results display.

### Dataset

The dataset used for simulations includes:
- Fluid properties
- Initial conditions for pressure, temperature, and flow rates

Ensure that you have access to these datasets and have placed them in the appropriate directory as specified in the notebook.

## Results

The results demonstrate the capability of ThermoCycleSim to accurately simulate thermodynamic cycles, producing detailed outputs for all stages of the cycle. Key parameters such as pressure, temperature, and flow rates are calculated and tabulated automatically.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
