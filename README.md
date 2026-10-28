# Charged-Particle Motion in a Uniform Magnetic Field

This project explores the motion of a charged particle in a uniform magnetic field using Python and numerical methods. The equations of motion are solved numerically, and the resulting particle trajectories are visualized in three dimensions.

The project was completed as part of a Python course exercise at **Sharif Summer School — Session 1**, organized by the **Physics Scientific Association at Sharif University of Technology**.

## 🧲 Physical Model

The motion of the charged particle is described by the **Lorentz force**. In this project, the electric field is set to zero and the magnetic field is assumed to be uniform, time-independent, and directed along the z-axis:

$$
\mathbf{E}=0,
\qquad
\mathbf{B}=B\hat{z}
$$

The equation of motion is:

$$
m\frac{d\mathbf{v}}{dt}
=
q(\mathbf{v}\times\mathbf{B})
$$

where \(m\) is the particle mass, \(q\) is its charge, \(\mathbf{v}\) is its velocity, and \(\mathbf{B}\) is the magnetic field.

## 🎯 What This Project Covers

The numerical simulation demonstrates several important features of charged-particle motion in a uniform magnetic field:

- **Circular motion:** When the initial velocity is perpendicular to the magnetic field, the particle follows a circular trajectory.
- **Helical motion:** When the initial velocity has a component parallel to the magnetic field, the trajectory becomes helical.
- **Charge-to-mass ratio:** Changing the sign of \(q/m\) changes the direction of rotation.
- **Magnetic-field strength:** Changing the magnetic-field strength affects the radius of the particle's circular motion.

## 📊 Numerical Simulation

The equations of motion are solved numerically using `scipy.integrate.solve_ivp`.

The simulation uses the particle position and velocity as the state variables and produces three-dimensional trajectory plots for different physical conditions.

The notebook investigates:

1. Circular motion
2. Helical motion
3. The effect of the charge-to-mass ratio
4. The effect of magnetic-field strength

## 🛠️ Tools and Technologies

- **Python**
- **NumPy**
- **SciPy**
- **Matplotlib**
- **Jupyter Notebook**

## ⚙️ How to Run

1. Clone or download this repository.

2. Install the required packages:

   ```bash
   pip install numpy scipy matplotlib jupyter
   ```

3. Open `charged_particle_motion.ipynb` using Jupyter Notebook or VS Code.

4. Run the notebook cells in order to reproduce the numerical calculations and visualizations.

## ⚠️ Limitations

The model is intentionally simplified for educational purposes.

- The magnetic field is assumed to be uniform and time-independent.
- The electric field is set to zero.
- The equations of motion are classical and nonrelativistic.
- Effects beyond the idealized Lorentz-force model are not included.

## 🎓 Acknowledgment

**Sharif Summer School — Session 1 Project**

**Sharif University of Technology — Physics Scientific Association**

**Instructor:** Bahareh Khishkhah