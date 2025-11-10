# NEST Simulator Tutorials — Introduction to Spiking Neural Network Modeling

This repository contains a series of tutorials introducing **[NEST Simulator](https://nest-simulator.readthedocs.io)**, a widely used tool for simulating large-scale networks of spiking neurons.  
The goal is to provide a introduction to:

- The **Leaky Integrate-and-Fire (LIF)** neuron models
- Exploring neuronal dynamics and simple synaptic interactions  

---

## Installation guide

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

## ⚠️ Warning for Windows Users

The NEST simulator is **not yet compatible with Windows**.  
You can either install it through **WSL**, or create an account on **[EBRAINS](https://iam.ebrains.eu/auth/realms/hbp/protocol/openid-connect/registrations?response_type=code&client_id=xwiki&redirect_uri=https://wiki.ebrains.eu)** to use their **[JupyterHub](https://lab.ebrains.eu/)** environment.

### Using EBRAINS JupyterHub

Once registered, follow the JupyterHub link and:

1. Select **Jülich Supercomputing Centre (JSC)** as the *Lab Execution Site*;
2. Sign in using **Keycloak** (login with your account if requested);
3. Open a **Terminal** from the launcher and clone the lesson repository:

   ```bash
   git clone https://github.com/marialauradeg98/Brain_modeling_05_11_2025.git
4. Navigate to the notebook folder and run the notebooks using the EBRAINS-25.02 kernel.