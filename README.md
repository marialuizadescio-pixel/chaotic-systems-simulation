# Chaotic Systems Simulation: The Lorenz Attractor 🌀
*(Simulação de Sistemas Caóticos: O Atrator de Lorenz)*

<img width="567" height="581" alt="lorenzattractor" src="https://github.com/user-attachments/assets/81e0a8a6-7480-4b34-800d-41a742db2f73" />

## English Description
This repository contains a numerical implementation of the **Lorenz System**, a set of three coupled ordinary differential equations (ODEs) that describe atmospheric flow. This project was developed as part of my preparation for a **Master's in Physics** (focusing on Nonlinear Dynamics and Complex Systems), during my undergraduate studies at **UNESP**.

The goal is to demonstrate how deterministic systems can exhibit chaotic behavior, famously known as the **"Butterfly Effect"** (sensitivity to initial conditions).

### The Physics Behind It
The system is defined by the following equations:

$$\frac{dx}{dt} = \sigma(y - x)$$

$$\frac{dy}{dt} = x(\rho - z) - y$$

$$\frac{dz}{dt} = xy - \beta z$$

Where:
- **$\sigma$ (Prandtl number)**: Related to the fluid viscosity.
- **$\rho$ (Rayleigh number)**: Related to the temperature difference in the fluid.
- **$\beta$**: Related to the physical dimensions of the system.

### Technologies Used
- **Python 3**
- **NumPy & SciPy**: For numerical integration (ODE solver).
- **Matplotlib**: For 3D state space visualization.
- **Google Colab**: Environment used for development.

---

## Descrição em Português
Este repositório contém uma implementação numérica do **Sistema de Lorenz**, um conjunto de três equações diferenciais ordinárias (EDOs) acopladas que descrevem o fluxo atmosférico. Este projeto foi desenvolvido como parte da minha preparação para o **Mestrado em Física** (foco em Dinâmica Não-Linear e Sistemas Complexos), durante minha graduação na **UNESP**.

O objetivo é demonstrar como sistemas determinísticos podem exibir comportamento caótico, conhecido como o **"Efeito Borboleta"** (sensibilidade às condições iniciais).

### Conceitos Explorados
- **Integração Numérica**: Uso do integrador `odeint` para resolver as trajetórias.
- **Espaço de Fases**: Visualização da evolução temporal das variáveis $x, y, z$.
- **Atratores Estranhos**: Observação da trajetória que orbita em uma região específica sem nunca se repetir.

## How to run / Como rodar
You can run this project directly in your browser via Google Colab. 
*(Você pode rodar este projeto diretamente no seu navegador via Google Colab.)*

1. Open the `.ipynb` file in this repository.
2. Click on the "Open in Colab" button.
3. Run all cells to see the interactive 3D plot.

---
**Author:** Maria Luiza Descio

*Physics Undergraduate - UNESP (Guaratinguetá)*
