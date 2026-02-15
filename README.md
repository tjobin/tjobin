# 👋 Hi, I'm Timothé

🎓 **Master's Student in Quantum Science & Engineering @ EPFL**
*Specializing in Neural Quantum States (NQS), Variational Monte Carlo (VMC), and Hybrid Quantum Algorithms.*

<!---💡 I’m currently working on:
- Developing **neural-network quantum states** with message-passing and kernel attention networks.
- Implementing **pseudopotentials** in **NetKet** for molecular simulations. --->

---

### 🧠 Interests

Quantum chemistry • Computational chemistry • Quantum computing • Machine learning for many-body systems

---

### 🛠 Tech Stack

| Domain | Tools |
| :--- | :--- |
| **Scientific Computing** | ![JAX](https://img.shields.io/badge/JAX-black) ![NumPy](https://img.shields.io/badge/NumPy-blue) ![SciPy](https://img.shields.io/badge/SciPy-blue) |
| **Quantum Frameworks** | ![NetKet](https://img.shields.io/badge/NetKet-blue) ![Qiskit](https://img.shields.io/badge/Qiskit-purple) ![PennyLane](https://img.shields.io/badge/PennyLane-orange) |
| **Machine Learning** | ![Flax](https://img.shields.io/badge/Flax-green) ![PyTorch](https://img.shields.io/badge/PyTorch-red) |

---

### 🔭 Featured Projects

#### ⚛️ [Neural Quantum States: KANs vs MLPs](https://github.com/tjobin/netket-kan)
*Benchmarking Kolmogorov-Arnold Networks (KAN) within a Message Passing Neural Network (MPNN) architecture for VMC.*
- **Method:** Implemented a custom VMC solver in **JAX/Flax**. Compared standard MLP global features against KANs for ground-state energy approximation of LiH and Li2.
- **Key Result:** While KANs showed high expressivity, the simpler Vertex/Edge MPNN ansatz converged faster for small systems, achieving chemical accuracy (1.6 mHa) with fewer fluctuations.
- **Tools:** JAX, Flax, NetKet, jaxkan.

#### 🧪 [Neural Quantum States with Pseudopotentials (ccECP)](https://github.com/tjobin/netket-ccECP)
*Extending Message Passing Neural Network architecture to transition metals for VMC.*
- **Method:** Implemented **core-correlated Effective Core Potentials (ccECP)** to simulate 3rd-row elements (Ga, Kr, Sc, Ti) without explicitly modeling core electrons.
- **Key Result:** Achieved chemical accuracy for Ga and Kr compared to FermiNet baselines.
- **Tools:** JAX, Flax, NetKet, Ferminet_ECP.

#### 🕰️ [Adaptive Quantum Imaginary-Time Evolution (AQITE)](https://github.com/tjobin/adaptive-qite)
*Developing a dynamic time-step algorithm for ground-state preparation on NISQ devices.*
- **Method:** Designed an adaptive algorithm that adjusts the Trotter time-step $\Delta\tau$ based on the angular velocity of the state vector in Hilbert space.
- **Key Result:** The adaptive method proved **3x more robust** to initial parameter selection than standard QITE, successfully reproducing the $H_2$ Potential Energy Surface across all entanglement regimes.
- **Tools:** Qiskit.

#### ⭐️ [VQE Robustness: UCCSD vs EfficientSU2](https://github.com/tjobin/vqe-project)
*Analysis of ansatz performance under depolarizing noise.*
- **Method:** Simulated VQE for LiH using Qiskit's Aer Estimator with injected gate noise (depolarizing channel).
- **Key Result:** Discovered that **EfficientSU2** is significantly more robust to gate errors (up to 1% error rate) than the physically motivated UCCSD, despite UCCSD's superior theoretical convergence rate.
- **Tools:** Qiskit.

<!--- #### 🧬 **[Interpretable ML for Protein Folding](https://github.com/CS-433/ml-project-2-pebkac)**
- Modified an **AttentionDCA** model to accept physics-based molecular representations (SPAHM, SLATM).
- **Key Finding:** By analyzing attention weights, found that the model prioritizes lower electronic energy levels (SPAHM eigenvalues), aligning with physical intuition for protein stability.
<!--- - 🌈 Simulating Liquid Crystal Alignment: The Role of Aspect Ratio
<!--- - ⚛️ [NetKet ECP Extension](https://github.com/yourusername/netket-ecp)
- 📚 [Notes on Quantum Path Integrals](https://github.com/yourusername/path-integrals) ---->

---

### 🤝 Let's Connect
📫 Email: [timothe.jobin@epfl.com](timothe.jobin@epfl.com) <br>
💼 LinkedIn: [linkedin.com/in/timothe-jobin](https://www.linkedin.com/in/timothe-jobin/)
