MonteCarloMolecularDynamicsIMS
molecular simulation programming with python
# Monte Carlo Code
1. Initialize system, implement PBC, truncated potential with force field.
2. Compute virial pressure, energy of a single particle, and total energy of the system.
2. Perform MC translation move to equilibrate the system, determine the most appropriate translation move step.
4. Write functions to sample averages of random configuration.
3. Verify with experimental results.

# Molecular Dynamics Code
1. Initialize system, assign velocities (3d vectors) satisfy Boltzmann distribution.
2. Compute pair-wise forces with the force field.
3. Implement integrator to solve Newtonian equations of motion. 
4. Write functions to obtain thermodynamic properties.
5. Implement thermostat to control system variables.
6. Equiliburiate system and sample results.
