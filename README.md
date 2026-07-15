<div align="center">

  <a href="https://saeidbahrami.com">
    <img src="banner.jpg" alt="Saeid Bahrami - Interactive SciML & CFD Dashboard Banner" width="100%" style="border-radius: 8px;" />
  </a>

  <br />
  <br />

  [![Research - BSC](https://img.shields.io/badge/Research-BSC%20%7C%20Barcelona%20Supercomputing%20Center-0054A6?style=for-the-badge&logo=cpu-filled&logoColor=white)](https://www.bsc.es)
  [![Education - Grenoble INP](https://img.shields.io/badge/M.Sc.-Fluid%20Mechanics%20%7C%20Grenoble%20INP-009A44?style=for-the-badge&logo=education&logoColor=white)](https://www.grenoble-inp.fr)
  [![Patent - US11124953](https://img.shields.io/badge/US%20Patent-11%2C124%2C953-D2691E?style=for-the-badge&logo=lighthouse&logoColor=white)](https://patents.google.com/patent/US11124953B2/en)

</div>

### Scientific Machine Learning (SciML) & Deployable Physics
I bridge the gap between advanced Computational Fluid Dynamics (CFD) and Scientific Machine Learning. My primary focus is developing **hardware-agnostic surrogate models** (Neural Operators, PINNs) optimized for **Model Predictive Control (MPC)** and energy transition applications. 

Driven by reproducible science, I engineer pure-Python inference pipelines that transform state-of-the-art literature into lightweight, vectorized solvers capable of executing *live* directly in the browser via Pyodide.

---

### Core Credentials
* **CFD Researcher** @ BSC (Barcelona Supercomputing Center)
* **M.Sc. Fluid Mechanics** (Grenoble INP)
* **Inventor** (US Patent 11,124,953: Thermal/Fluid Systems)

---

### Software Architecture & DRY Principles

To overcome the "technical debt" often found in academic codebases, my repositories strictly adhere to a decoupled architecture. I separate the core mathematical engines from project-specific deliverables, ensuring scalable, production-grade research software:

```text
Saeid-Bahrami/ (Profile Anchor & Reproducibility Hub)
│
├── ⚙️ SciML-Thermal-Core/            # THE ENGINE: Single Source of Truth
│   ├── sciml_core.solvers/           # Vectorized NumPy baseline physics solvers
│   ├── sciml_core.neural_ops/        # Barebone architectures (FNO, DeepONet)
│   ├── sciml_core.mpc_controller/    # Model Predictive Control (MPC) optimization loop
│   └── sciml_core.pyodide_bridge/    # WASM serialization for Web UI rendering
│
├── 📂 Archetypes/       # THE DELIVERABLES: Micro-Projects & Live Deployments
│   │
│   ├── 🎯 Project 1_HVAC_Surrogate/    # Archetype: Neural surrogate for building energy MPC
│   │   ├── weights/                  # Pre-trained lightweight checkpoints (.npy / .pt)
│   │   ├── main_inference.py         # Lightweight script calling SciML-Thermal-Core
│   │   └── index.html                # <py-script> integration for LIVE browser execution
│   │
│   └── 🎯 project 2_Digital_Twin/      # Archetype: Sensor fusion & data assimilation framework
│       └── ...
│
└── ...
```
Hardware-Agnostic Inference: Heavy training is decoupled. The archetype repositories rely on pre-trained weights and dense NumPy vectorization to perform lightning-fast inference, proving architectural viability without requiring HPC access.

Zero-Install Reproducibility: By bridging Python algorithms with WebAssembly (Pyodide), physical simulations and neural network inferences can be evaluated instantly by researchers and reviewers globally, directly in their browsers.

---

<div align="center">
  <h3>📬 Academic Collaborations & Full-Time Research Roles</h3>
  <p>My objective is to bridge advanced Computational Fluid Dynamics with strong engineering intuition, delivering creative and reproducible solutions for complex physical challenges.</p>
 <p> I am actively open to full-time academic research positions and collaborative roles within high-impact grant projects.</p>
  <p>
    <a href="https://saeidbahrami.com"><b> Explore My CFD Portfolio & Lab </b></a> • 
    <a href="mailto:mail@saeidbahrami.com"><b> Email Me </b></a> • 
  </p>
</div>
