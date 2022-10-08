# Quantum_Chemistry_for_Simulating_Hydrides_And_Optimization
• Simulated the properties of molecules and chemical reactions • Studied the applications and differences of several simulating approaches • Optimized the measuring process, making it 4 times more efficient  
This notebook demonstrates:
1. NaH dissociation curve using VQE with UCCSD: plot graphs of the ground state energy of the Sodium Hydride (NaH) molecule over a range of inter-atomic distances using VQE and UCCSD. It is compared to the same energies as computed by the NumPyMinimumEigensolver.

2. LiH dissociation curve using VQE with UCCSD variational form: plot graphs of the ground state energy of the Lithium Hydride (LiH) molecule over a range of inter-atomic distances using VQE and UCCSD. It is compared to the same energies as computed by the NumPyMinimumEigensolver 

3. LiH dissociation curve using NumPyMinimumEigensolver: plot graphs of the ground state energy and dipole moments of a Lithium Hydride (LiH) molecule over a range of inter-atomic distances.

4. H2O ground state computation: compute the ground state energy of a water (H2O) molecule using VQE and UCCSD.

5. H2 ground state energy computation using Iterative QPE 

6. Measurement Optimization: We went from 2110 required measurements evaluations to 556 (just over two thousand down to five hundred !!, we successfully make it 4 times more efficient ).
This problem of measurement optimization no longer just applies to the VQE algorithm (the algorithm it was born from). Instead, there are a multitude of algorithms that could benefit from these measurement optimization techniques (QAOA being a prime example).
