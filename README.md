# Electron Scattering Simulator

A Python simulation of an electron moving under the electrostatic repulsion of a fixed electron at the origin.

## Features

* User-defined initial position and velocity
* Coulomb force calculation
* Numerical integration of motion
* 2D trajectory visualisation using Matplotlib

## Physics

The force between the electrons is given by Coulomb's Law:

F = kq²/r²

The resulting acceleration is calculated using Newton's Second Law:

a = F/m

The electron's position and velocity are updated using the Euler method.

##Trajectory outputs

<img width="460" height="375" alt="image" src="https://github.com/user-attachments/assets/8506312b-8ae5-4441-95ea-0dc2ef4f18dd" />

<img width="460" height="375" alt="image" src="https://github.com/user-attachments/assets/b1f5a31a-9501-437f-a91b-51dfd9ad9a95" />






## Requirements

```bash
pip install matplotlib
```

## Usage

```bash
python electron_scattering.py
```

Example inputs:

```text
x = -5e-8
y = 1e-8
vx = 200000
vy = 0
```

## Future Improvements

* Multiple interacting particles
* Electric field visualisation
* Simulation in three dimensions
