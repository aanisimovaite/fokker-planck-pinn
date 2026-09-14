# Fokker–Planck PINN

This repository contains a reproducible Jupyter workflow for approximating
the solution of a one-dimensional Ornstein–Uhlenbeck Fokker–Planck 
equation
using a physics-informed neural network (PINN) implemented in PyTorch.

## Requirements

The workflow uses Python 3.11 together with PyTorch, NumPy, Matplotlib and
Jupyter Lab.

Dependencies are specified in `pyproject.toml`, while the complete 
resolved
environment is stored in `uv.lock`.

## Running the workflow

Clone the repository:

    git clone https://github.com/aanisimovaite/fokker-planck-pinn.git

Enter the project directory:

    cd fokker-planck-pinn

Recreate the environment:

    uv sync

Start Jupyter Lab:

    uv run jupyter lab

Open `fokker_planck_pinn.ipynb` and run all cells from top to bottom.

## Reproducibility

The notebook uses fixed random seeds for NumPy and PyTorch.

The tested software environment is recorded using `pyproject.toml`,
`.python-version`, and `uv.lock`.

## License

This project is released under the MIT License.
# Fokker–Planck PINN

This repository contains a reproducible Jupyter workflow for approximating
the solution of a one-dimensional Ornstein–Uhlenbeck Fokker–Planck 
equation
using a physics-informed neural network (PINN) implemented in PyTorch.

## Requirements

The workflow uses Python 3.11 together with PyTorch, NumPy, Matplotlib and
Jupyter Lab.

Dependencies are specified in `pyproject.toml`, while the complete 
resolved
environment is stored in `uv.lock`.

## Running the workflow

Clone the repository:

    git clone https://github.com/YOUR_USERNAME/fokker-planck-pinn.git

Enter the project directory:

    cd fokker-planck-pinn

Recreate the environment:

    uv sync

Start Jupyter Lab:

    uv run jupyter lab

Open `fokker_planck_pinn.ipynb` and run all cells from top to bottom.

## Reproducibility

The notebook uses fixed random seeds for NumPy and PyTorch.

The tested software environment is recorded using `pyproject.toml`,
`.python-version`, and `uv.lock`.

## License

This project is released under the MIT License.
