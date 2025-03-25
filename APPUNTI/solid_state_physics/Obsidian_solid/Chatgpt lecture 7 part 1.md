# Electromagnetic Waves in Materials: Maxwell's Equations

## Microscopic Dipole Moments and Polarization Field

We started by introducing the concept of a polarization vector, which represents the microscopic dipole moment in a material. A dipole consists of a positive and a negative charge separated by a distance $d$ , where $d = q \times \text{distance between charges}$, and  $q$  is the charge.

This polarization field describes the density of microscopic dipoles within the material. Materials are generally electrically neutral at a macroscopic level, with an equal number of positive nuclei and negative electrons. However, on a microscopic scale, there is a small separation of charge, leading to a slight space charge. This is due to the discrete nature of the charges, where electrons move around the lattice, and the positively charged nuclei are fixed.

This space charge leads to an electric field inside the material, which can be described using a displacement field,  $\mathbf{D}$ , which accounts for both the electric field in vacuum and the contribution from the polarization of the material.

## Displacement Field in Materials

The displacement field $\mathbf{D}$  in materials can be expressed as:

$$
\mathbf{D} = \varepsilon_0 \varepsilon_r \mathbf{E}
$$

Here, $\varepsilon_0$ is the permittivity of free space, and $\varepsilon_r$  is the relative permittivity of the material, which is greater than or equal to 1, and equals 1 in vacuum. This expression takes into account the material’s response to the applied electric field, including the alignment of dipoles that create additional electric field contributions.

## Maxwell's Equations in Materials

We derived Maxwell's equations for a material starting from the vacuum equations, making modifications for the material properties:

1. **Gauss's Law**: In materials, Gauss's law is expressed in terms of the displacement field $\mathbf{D}$ , replacing the electric field  $\mathbf{E}$  with $\mathbf{D}$  and adjusting for the material's permittivity.

2. **Gauss's Law for Magnetism**: This equation remains unchanged, describing how magnetic fields behave.

3. **Faraday's Law of Induction**: This law remains essentially the same, describing how changing magnetic fields produce electric fields.

4. **Ampère-Maxwell Law**: The modified form of this equation is:

$$
\nabla \times \mathbf{H} = \mathbf{J} + \frac{\partial \mathbf{D}}{\partial t}
$$

Where  $\mathbf{J}$  is the current density, and  $\frac{\partial \mathbf{D}}{\partial t}$  accounts for the time variation of the displacement field.

In the material, we replace the vacuum permittivity $\varepsilon_0$  and permeability $\mu_0$  with  $\varepsilon_r$  and  $\mu_r$, respectively. For many materials, we assume $\mu_r = 1$ (neglecting magnetic effects).

## Electromagnetic Wave Propagation in Materials

With Maxwell’s equations in the material, we can describe how an electromagnetic wave propagates. We assume a material with free charges that are able to move (e.g., electrons in semiconductors or metals), and we are interested in how these waves behave when they interact with the material.

For an electromagnetic wave, the electric field oscillates at certain frequencies, and this oscillation can depend on the frequency of the applied electromagnetic field.

### Wave Equation in Materials

To describe wave propagation in materials, we begin by recalling the wave equation in vacuum:

$$
\nabla^2 \mathbf{E} - \frac{1}{c^2} \frac{\partial^2 \mathbf{E}}{\partial t^2} = 0
$$

Where $c$  is the speed of light in vacuum. In a material, we can modify this equation to account for the material properties.

### Maxwell's Equations for Wave Propagation

In the presence of a material, we consider the electric field  $\mathbf{E}$  and magnetic field  $\mathbf{H}$  interacting with each other. The time dependence of both fields introduces a coupling that leads to the wave equation for electromagnetic waves in materials. We start with:

1. The electric field equation, which includes the time derivative of the magnetic field.
2. The magnetic field equation, which includes the conductivity of the material and the time derivative of the displacement field.

We combine these two equations to form a second-order differential equation for the electric field in the material.

$$
\nabla^2 \mathbf{E} - \mu_0 \mu_r \sigma \frac{\partial \mathbf{E}}{\partial t} - \varepsilon_0 \varepsilon_r \frac{\partial^2 \mathbf{E}}{\partial t^2} = 0
$$

Here, $\sigma$  is the conductivity of the material, and  $\mu_r$  and  $\varepsilon_r$  are the relative permeability and permittivity, respectively.

### Simplifying the Wave Equation

If we neglect magnetic effects ( $\mu_r = 1$ ), the wave equation simplifies to:

$$
\nabla^2 \mathbf{E} - \varepsilon_r \mu_0 \sigma \frac{\partial \mathbf{E}}{\partial t} - \varepsilon_0 \varepsilon_r \frac{\partial^2 \mathbf{E}}{\partial t^2} = 0
$$

This is the simplified wave equation for the electric field in the material. It describes how the electric field oscillates and propagates through the material, taking into account its conductivity and permittivity.

## Conclusion

The main takeaway is that the electromagnetic wave equation in materials differs from the one in vacuum due to the material’s properties, such as permittivity  $\varepsilon_r$  and conductivity  $\sigma$ . These material properties affect how the wave propagates, its absorption, and its reflection behaviour. We also need to consider the polarization effects in materials, which are modelled through the displacement field.

---

This concludes the first part of the lecture. The second part will further explore the solution to the wave equation and how materials interact with electromagnetic waves at different frequencies.
