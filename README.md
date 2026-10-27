# Charged-Particle Motion in a Uniform Magnetic Field

This project explores the motion of a charged particle in a uniform magnetic field using Python. The equations of motion are solved numerically, and the resulting trajectories are visualized in three dimensions.

The project was completed as part of a Python course exercise at Sharif Summer School.

## Physical Model

The motion is described by the Lorentz force, with the electric field set to zero and a constant magnetic field directed along the z-axis.

## What This Project Covers

- Circular motion when the initial velocity is perpendicular to the magnetic field
- Helical motion when the initial velocity has a component parallel to the field
- The effect of changing the sign of the charge-to-mass ratio on the direction of rotation
- The effect of magnetic-field strength on the trajectory radius

## Tools

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## How to Run

1. Clone or download this repository.
2. Install the required packages:

   ```bash
   pip install numpy scipy matplotlib jupyter
   ```

3. Open `charged_particle_motion.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook cells in order.

## Limitations

The model assumes a uniform, time-independent magnetic field and neglects the electric field. It uses the classical, nonrelativistic equation of motion.

## Acknowledgment

Sharif Summer School — Session 1 Project  
Sharif University of Technology, Physics Scientific Association
