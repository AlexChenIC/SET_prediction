# SET Pulse Width Prediction using Machine Learning

This project aims to predict Single Event Transient (SET) pulse width under various input conditions using machine learning techniques. The dataset is generated using SPICE simulations, and the project will focus on training models to perform regression tasks based on this data.

## Project Overview

This project includes:
- **Data Processing**: Handling and preprocessing SPICE simulation data.
- **Model Training**: Building machine learning models (e.g., Random Forest, Gradient Boosting) to predict SET pulse width.
- **Model Evaluation**: Evaluating the performance of the trained models and optimizing them.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Activating the Environment](#activating-the-environment)
4. [Running the Project](#running-the-project)
5. [Contributing](#contributing)
6. [License](#license)

---

## Installation

To set up the project environment, follow the instructions below.

### Prerequisites

1. **Anaconda/Miniconda**: Make sure you have Anaconda or Miniconda installed on your system. If not, you can download and install Miniconda from [here](https://docs.conda.io/en/latest/miniconda.html).

2. **Git**: You should have Git installed to clone this repository.

### Cloning the Repository

First, clone the repository from GitHub:
```bash
git clone https://github.com/your-username/SET-prediction.git
cd SET-prediction
```

### Creating the Conda Environment

Once you're inside the project directory, create a Conda environment using the provided `environment.yml` file. This will automatically install all necessary dependencies.

```bash
conda env create -f environment.yml
```

This will create a new Conda environment named `ml_project_env` (as specified in the `environment.yml`).

---

## Usage (First Time)

### Activating the Environment

After creating the environment, you can activate it using the following command:

```bash
conda activate ml_project_env
```

This will activate the virtual environment and set up the necessary paths for all required dependencies.

### Running Jupyter Lab

Once the environment is activated, you can start Jupyter Lab to begin developing or running your analysis:

```bash
jupyter lab
```

This will launch Jupyter Lab in your default web browser, where you can open and run `.ipynb` notebooks.

### Running the Project Script (in Jupyter notebook)

You can view the main code in the notebooks folder, and the default main file is 

```bash
main.ipynb
```

---

## Future Usage

For future use, whenever you want to work on this project, follow approaches:

You can simply run the script to activate the environment and start Jupyter Lab:

```bash
./start_project.sh
```

 Or you can set the process step by step:

1. Open a terminal and navigate to the project directory:
   ```bash
   cd /path/to/SET-prediction
   ```

2. Activate the Conda environment:
   ```bash
   conda activate ml_project_env
   ```

3. Start Jupyter Lab:
   ```bash
   jupyter lab
   ```

4. If necessary, deactivate the environment after you're done:
   ```bash
   conda deactivate
   ```

---

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name:
   ```bash
   git checkout -b feature-new-model
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add new model for pulse width prediction"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-new-model
   ```
5. Open a Pull Request to the `main` branch.

---

## Additional Notes

- The provided `environment.yml` file ensures that all required dependencies for the project are installed in the Conda environment.
- It's important to periodically update your environment to keep up with library changes. To update the environment, you can run:
  ```bash
  conda env update --file environment.yml --prune
  ```

```
