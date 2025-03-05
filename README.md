# drone-path-planning-z3

This repository explores various approaches for planning drone routes with a focus on battery consumption and path optimization.

## Repository Structure

- **Solution Building**  
  Contains notebooks that build the basic models for drone trajectory planning.
  - [1-drone_incorrect_consumption.ipynb](Solution%20Building/1-drone_incorrect_consumption.ipynb) – Demonstrates scenarios with incorrect battery consumption.
  - [2-drone_correct_consumption.ipynb](Solution%20Building/2-drone_correct_consumption.ipynb) – Shows correct battery consumption calculations and logic.

- **Solution Optimization**  
  Contains notebooks that optimize drone paths.
  - [1-drone_all_possible_paths.ipynb](Solution%20Optimization/1-drone_all_possible_paths.ipynb) – Lists all possible drone trajectories.
  - [2-drone_best_battery_all_possible_paths.ipynb](Solution%20Optimization/2-drone_best_battery_all_possible_paths.ipynb) – Finds drone trajectories with the best battery usage.
  - [3-drone_best_battery_all_possible_paths_Complex.ipynb](Solution%20Optimization/3-drone_best_battery_all_possible_paths_Complex.ipynb) – Advanced exploration of battery optimization strategies.

- **Solution Discussion**  
  Contains notebooks that compare and analyze different approaches.
  - [1-drone_compare_timesteps.ipynb](Solution%20Discussion/1-drone_compare_timesteps.ipynb) – Compares battery consumption and timesteps for drone trajectories.
  - [2-random_drone_best_battery_all_possible_paths_Complex copy.ipynb](Solution%20Discussion/2-random_drone_best_battery_all_possible_paths_Complex%20copy.ipynb) – Additional experiments on battery optimization.

## Requirements

- Python 3.7 or higher
- [Jupyter Notebook](https://jupyter.org/) or [JupyterLab](https://jupyterlab.readthedocs.io) for running the notebooks
- Additional Python libraries as specified within each notebook

## How to Run

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/drone-path-planning-z3.git