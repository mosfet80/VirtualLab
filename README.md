# TokaLab - Virtual Laboratory

**TokaLab** is an open-access, open-source GitHub project designed to support multiple objectives:

* **Collaboration and knowledge sharing** – Provide a common platform where researchers working on nuclear fusion and tokamak physics can collaborate, share algorithms, and exchange knowledge.
* **Education and training** – Create an educational environment for students and researchers by offering computational tools with different levels of physical fidelity.
* **Data and algorithm development** – Build a flexible framework for data generation, algorithm validation, and machine learning model training.

---

## 🔬 VirtualLab - Overview

**VirtualLab** is the core component of TokaLab.
It enables users to build a custom virtual tokamak or use existing configurations, generate plasma scenarios, develop and compute synthetic diagnostics, and produce datasets for benchmarking and AI training.

It is designed to be **modular**, **object-oriented**, and to follow a **multi-fidelity physics** approach — ranging from simple educational codes to more advanced, research-grade tools.

**VirtualLab** is actively maintained in both **MATLAB** and **Python**.

You can also use the MATLAB version directly online:

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=TokaLab/VirtualLab)

---

## 🧩 Modules

### ⚛️ SimPLa — *Simulated Plasma*
Solves the Grad–Shafranov equation on a fixed boundary to generate equilibrium plasma configurations. It is the primary physics engine of VirtualLab and serves as input provider for the other modules.

### 🩺 SynDiag — *Synthetic Diagnostics*
Includes codes for simulating a variety of plasma diagnostics. Given a plasma scenario from SimPLa, SynDiag computes the expected diagnostic signals, supporting both validation workflows and synthetic data generation.

### ☢️ SimRad — *Simulated Radiation*
Generates tokamak-like radiation patterns from plasma equilibria. SimRad provides synthetic emissivity and line-of-sight integrated radiation signals, useful for tomographic reconstruction studies and machine learning tasks.

### 📊 TokaPlot — *Advanced Automated Plotting*
A dedicated visualization module for automated, publication-ready plotting of plasma equilibria, diagnostic signals, and radiation patterns. TokaPlot standardizes the graphical output across all other modules.

### 🗄️ DataGen — *Dataset Generator*
A collection of scripts to rapidly generate large, parametric datasets from VirtualLab simulations. DataGen is designed for benchmarking numerical methods and training AI/ML models on tokamak physics scenarios.

---

## 📚 Documentation

See our [Wiki](https://github.com/TokaLab/VirtualLab/wiki) for setup instructions, examples, and detailed explanations of each module.

---

## 🗂 Repository Structure

```plaintext
VirtualLab/
│
├── VirtualLab_MATLAB/           # MATLAB implementation
│   ├── docs/
│   ├── examples/
│   ├── SimPLa_MATLAB/
│   ├── SynDiag_MATLAB/
│   ├── SimRad_MATLAB/
│   ├── TokaPlot_MATLAB/
│   ├── DataGen_MATLAB/
│   ├── Validation/
│   └── VirtualLab_init.m
│
├── VirtualLab_Python/           # Python implementation
│   ├── SimPLa_Python/
│   ├── SynDiag_Python/
│   ├── SimRad_Python/
│   ├── TokaPlot_Python/
│   ├── DataGen_Python/
│   └── ...
│
├── Citations.md
├── Contributing.md
├── Contributors.md
├── License
└── README.md
```

> **Note:** The repository structure above reflects the intended layout. Some modules may still be in active development — refer to the [Wiki](https://github.com/TokaLab/VirtualLab/wiki) for the current status of each module.

---

## 🤝 Contributing

TokaLab is open-access and open-source — we warmly welcome new contributors!
Please check the [Contributing](./Contributing.md) guidelines to learn how to get started.

---

## 📄 License

TokaLab is released under the BSD 3-Clause License.
See the [License](./License) file for full details.

---

## 👥 TokaLab Team

The team and list of contributors are available [here](./Contributors.md).

---

## 🧪 Research Outputs

TokaLab has already been used in research activities such as inverse problem algorithm validation and machine learning model training and testing. Explore our [Research Outputs](https://tokalab.github.io/Publications/) for more details.

---

## 📬 Contact

For questions, suggestions, or collaborations:

📧 Email: [tokalab.fusion@gmail.com](mailto:tokalab.fusion@gmail.com)
🌐 Website: [tokalab.github.io](https://tokalab.github.io/)
💼 Social: [LinkedIn](https://www.linkedin.com/company/tokalab-fusion/)
