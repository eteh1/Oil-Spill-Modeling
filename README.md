# Oil Spill Modeling

## Overview
Oil spill modeling is crucial for understanding and predicting the behavior of oil spills in marine environments. This repository provides tools and models to simulate oil spill scenarios, analyze their impacts, and support decision-making processes for environmental protection and response planning.

## Features
- **Simulation of oil spills** under various environmental conditions.
- **Prediction of oil dispersion patterns** based on ocean currents, wind, and other physical factors.
- **Visualization tools** for interpreting simulation results.
- **Data analysis tools** to assess environmental impacts.
- **Customization options** for different oil types and spill scenarios.

## Requirements
To run the simulations, ensure you have the following dependencies installed:

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- SciPy
- Geopandas (for spatial data analysis)
- NetCDF4 (for handling oceanographic data)

You can install the dependencies using:
```bash
pip install -r requirements.txt
```

## Installation
Clone the repository using:
```bash
git clone https://github.com/eteh1/Oil-Spill-Modeling.git
cd Oil-Spill-Modeling
```

## Usage
1. Prepare input data (e.g., ocean currents, wind data, spill source information).
2. Run the simulation using the main script:
   ```bash
   python run_simulation.py --config config.yaml
   ```
3. View and analyze results in the output directory.

Example usage:
```bash
python run_simulation.py --config sample_config.yaml
```

## Configuration
The model settings are defined in a YAML configuration file. Example parameters include:
- **Spill location:** Latitude, Longitude
- **Oil type:** Density, viscosity
- **Environmental conditions:** Wind speed, current velocity
- **Simulation duration:** Start and end time

## Output
The simulation outputs include:
- Spill trajectory plots
- Oil concentration maps
- Statistical reports

## Contributing
Contributions are welcome! Feel free to open issues, submit pull requests, or suggest improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments
Special thanks to contributors and open-source projects that made this tool possible.

## Contact
For any inquiries, please reach out via GitHub issues or email at desmondeteh@gmail.com.

