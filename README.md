# Fokker–Planck PINN

This repository contains a reproducible Jupyter workflow for approximating
the solution of a one-dimensional Ornstein–Uhlenbeck Fokker–Planck 
equation
using a physics-informed neural network (PINN) implemented in PyTorch.

## Requirements

The workflow uses:

- Python 3.11
- PyTorch 2.2.2
- NumPy 1.26.4
- Matplotlib
- Jupyter Lab

Dependencies are specified in `pyproject.toml`, while the complete 
resolved
software environment is stored in `uv.lock`.

## Running the workflow

Clone the repository:

    git clone https://github.com/aanisimovaite/fokker-planck-pinn.git

Enter the project directory:

    cd fokker-planck-pinn

Recreate the environment:

    uv sync

Start Jupyter Lab:

    uv run jupyter lab

Open `PINN.ipynb` and run all cells from top to bottom.

## Reproducibility

The notebook uses fixed random seeds for NumPy and PyTorch.

The Python version and software dependencies are recorded using
`.python-version`, `pyproject.toml`, and `uv.lock`.

The notebook contains the model parameters, training procedure, evaluation
steps, analytical comparison, and generated outputs required to reproduce
the experiment.

## License

This project is released under the MIT License.
