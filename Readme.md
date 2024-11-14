# MLflow Experiment Tracking

This project uses **MLflow** to track, organize, and visualize machine learning experiments. By using MLflow, you can log model parameters, metrics, and artifacts, enabling easy comparison across different experiment runs.

## Table of Contents
- [Setting Up a Virtual Environment](#setting-up-a-virtual-environment)
- [Installation](#installation)
- [MLflow Interface](#mlflow-interface)
- [Logging Experiments](#logging-experiments)
- [License](#license)
- [Author](#author)


## Setting Up a Virtual Environment
To avoid dependency conflicts, create a virtual environment specifically for this project:

Using conda:
```bash
   conda create -n mlflow_env python=3.8
   conda activate mlflow_env
```

## Installation

1. Clone this repository and navigate to the project directory.
2. Install **MLflow** with the following command:
   ```bash
   pip install mlflow
   ```
## MLflow Interface
Once MLflow is installed, start the MLflow User Interface (UI) to visualize experiments:
Note: Run this command in cmd/terminal.
```bash
mlflow ui
```
You can access the MLflow UI at http://127.0.0.1:5000. The UI provides a dashboard where you can view experiment parameters, metrics, and artifacts.
## Logging Experiments
Run the notebook file to log the experiments and to store artifacts in mlflow.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Author
Srinath R
- Email: srinathranganathan432@gmail.com
- LinkedIn: https://www.linkedin.com/in/srinath2003/
- GitHub: https://github.com/srinath2003

