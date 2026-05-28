# Hi, I'm Dayolabi 👋

Physics researcher working at the intersection of **condensed matter**, **quantum computing**, and **computational science**. Currently on a research internship focused on materials characterisation and quantum simulation.

---

## What I Work On

**Materials Science & SEM Analysis**
- Python pipelines for automated grain-size analysis of SEM images
- Multi-Otsu / equal-width / manual thresholding for phase segmentation of `.tif` images
- Statistical analysis (Gaussian fits, Cramér-Rao bounds) on grain-size distributions across sample series

**High-Performance Computing (OpenMP / C++)**
- Parallel implementations of numerical methods: series evaluation, FFT, density-of-states calculations
- 1D tight-binding density of states (`TBDOS`) with OpenMP parallelisation
- Finite-size scaling and thermodynamic-limit extrapolation of quantum systems

**Quantum Computing (Qiskit)**
- Quantum entanglement protocols: superdense coding, quantum teleportation, entanglement swapping
- Single- and multi-qubit circuit design with `AerSimulator`
- Exploration of Bell states and their applications in quantum communication

**Quantum Sensing & Optics**
- Parameter estimation (transmittance $|T|$, phase $\gamma$) using photon-counting interferometry
- Maximum-likelihood estimators and Cramér-Rao bound analysis for SPDC-based sensors
- Deep dive into *quantum imaging with undetected photons* (Lemos et al., Nature 2014)

**Tight-Binding / Condensed Matter (KITE)**
- Kernel Polynomial Method (KPM) density-of-states calculations
- Electronic structure of low-dimensional systems

---

## Tech Stack

| Domain | Tools |
|---|---|
| Languages | Python · C++ |
| HPC | OpenMP · MPI (intro) |
| Quantum | Qiskit · KITE |
| Data / Viz | NumPy · SciPy · Pandas · Matplotlib |
| Image Processing | Pillow · scikit-image |
| Notebooks | Jupyter |

---

## Selected Projects

- **[SEM Grain Segmentation]** — CLI tool to colour-code grayscale SEM images by intensity class using Multi-Otsu thresholding. Handles 16-bit TIFFs, outputs side-by-side comparisons.
- **[Quantum Sensing Simulator]** — Simulates a two-phase interferometer for joint estimation of transmittance and phase; plots uncertainty vs. photon number and vs. true transmittance.
- **[HPC Course Work]** — Progressive parallelisation of numerical algorithms from serial C++ to OpenMP-parallelised density-of-states solvers.
- **[Qiskit Entanglement Protocols]** — Superdense coding, teleportation, and entanglement-swapping circuits implemented and simulated with `AerSimulator`.

---

## Currently Learning

- Kernel Polynomial Method for large-scale quantum transport
- Finite-element methods for quantum field problems
- MPI for distributed-memory parallelism

---

📫 dayolabi1@gmail.com
