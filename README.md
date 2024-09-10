# MVX
MVX

# MVX - Co-Simulation Framework for Vehicular Communication

Welcome to the official repository for **MVX**, a Co-Simulation Framework for Advanced Digital Twin AI Applications in Vehicular Communication. This repository contains the code, dataset, and resources associated with the paper, *"MVX Co-Simulation Framework: A Database for Advanced Digital Twin AI Applications in Vehicular Communication"*.

## Table of Contents

- [About MVX](#about-mvx)
- [Features](#features)
- [Getting Started](#getting-started)
- [Dataset](#dataset)
- [Code Usage](#code-usage)
- [Citation](#citation)
- [License](#license)
- [Contributing](#contributing)
- [Contact](#contact)

## About MVX

MVX is a configurable and scalable co-simulation framework that integrates realistic physical world simulation and accurate ray-tracing wireless simulation. It is designed for generating multi-agent and multimodal datasets for AI-driven digital twin applications in vehicular communication systems.

MVX aims to help researchers, developers, and engineers simulate and optimize real-time communication between vehicles, leveraging digital twin technology and AI integration.

## Features

- **High-Fidelity Co-Simulation**: Combines CARLA and Sionna simulators for realistic co-simulation.
- **Configurability**: Easily adjust the physical and wireless environment parameters.
- **Scalable Solutions**: Designed for large-scale vehicular communication systems.
- **Multimodality**: Supports multiple data modalities to simulate complex vehicular scenarios.
- **Efficient Database Management**: Manages large datasets for vehicular communication simulations.

## Getting Started

### Prerequisites

Before running the MVX code, ensure that you have the following installed:

- Python 3.8 or higher
- CARLA Simulator
- Sionna Simulator
- NumPy, Pandas, and other required Python packages (see `requirements.txt`)

### Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/mvx-repository.git
    cd mvx-repository
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Install **CARLA Simulator** and **Sionna Simulator** following their official documentation.

4. (Optional) Create a virtual environment to manage dependencies:

    ```bash
    python -m venv mvx-env
    source mvx-env/bin/activate  # For Windows: mvx-env\Scripts\activate
    ```

## Dataset

The MVX dataset for vehicular communication scenarios will be released soon. Stay tuned for updates!

Once available, the dataset will include:

- Simulation data from the CARLA and Sionna environments.
- Multimodal datasets for various vehicular communication scenarios.
- Pre-processed datasets for easy AI model integration.

## Code Usage

### Running the Co-Simulation Framework

To run the co-simulation, execute the following command:

```bash
python mvx_simulation.py --config=config.yaml
