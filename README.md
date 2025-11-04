# NEST Simulator Tutorials — Introduction to Spiking Neural Network Modeling

This repository contains a series of tutorials introducing **[NEST Simulator](https://nest-simulator.readthedocs.io)**, a widely used tool for simulating large-scale networks of spiking neurons.  
The goal is to provide a introduction to:

- The **Leaky Integrate-and-Fire (LIF)** neuron models
- Exploring neuronal dynamics and simple synaptic interactions  

---

## 🧠 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/marialauradeg98/Brain_modeling_05_11_2025.git
cd Brain_modeling_05_11_2025
```

### 2. Create the environment
All dependencies are managed using **conda** .  
The environment file `environment.yml` defines all necessary packages, including NEST.

To create the environment:
```bash
conda env create -f environment.yml
```

### 3. Activate the environment
Once the installation is complete, activate the environment:

```bash
conda activate nest-env
```

### 4. Verify the installation
To make sure NEST was installed correctly, run:

```bash
python -c "import nest"
```