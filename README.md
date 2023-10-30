# README for Laser Powder Bed Fusion (LPBF) Experiments Repository

## Introduction
This GitHub repository hosts a series of Jupyter notebooks aimed at exploring, analyzing, and visualizing data collected from Laser Powder Bed Fusion (LPBF) experiments. The primary objective is to understand transitions in melting regimes and to set up a structured pipeline for data analysis, which can be extended for future experiments and real-time monitoring systems.

## Setup
### Prerequisites
- Python 3.x
- Jupyter Notebook
- Libraries: [List libraries based on the notebooks; likely includes Pandas, Matplotlib, Numpy, Scipy, etc.]

### Installation
1. Clone the repository to your local machine.
2. Install the required libraries: `pip install -r requirements.txt`
3. Launch Jupyter Notebook and open the desired notebook.

## Notebooks
### 1. Angle of Detection Calculations (`0_Angle_of_Detection_Calculations.ipynb`)
- **Purpose**: To calculate the angle of detection $(\alpha)$ for various cube samples with different distances to the detector.
- **Sequence**: This is the first notebook to be executed.
- **Data**: Sample distances and detector heights.

### 2. Design of Experiment (`1_Design_of_Experiment.ipynb`)
- **Purpose**: To provide the theoretical background and experimental setup for the LPBF experiments.
- **Sequence**: This is a reference notebook and should be read before or alongside other notebooks.
- **Data**: Experimental parameters and LPBF machine settings.

### 3. Database Creation for Cubes (`2_Database_creation_CubeX.ipynb`)
- **Purpose**: To process and analyze data collected from LPBF experiments, where `X` can be any cube number (1 to 5).
- **Sequence**: Should be run after the angle of detection calculations and with the knowledge of the experimental design.
- **Data**: Optical emission and reflection data from the LPBF experiments.

### 4. Exploratory Data Analysis (`3_EDA.ipynb`)
- **Purpose**: To analyze and visualize the processed optical data using statistical methods, Fourier Transform analysis, and clustering techniques.
- **Sequence**: Should be run after data has been processed in the "Database Creation for Cubes" notebooks.
- **Data**: Processed and stored optical data.

## Usage
To maximize the benefit from this repository, it is recommended to execute the notebooks in the sequence listed above.

## Acknowledgements
Special thanks to Lucas Maximilian Schlenger and Jamasp Jhabvala for running the machines. Without their invaluable contributions, there would be no data to analyze.

## Future Work
- Perform advanced statistical analyses on the processed data to discern patterns or transitions in melting regimes.
- Develop machine learning models for predictive analytics.
- Implement these analyses into a real-time monitoring system for LPBF processes.

## License
This project is under the [TBD] License. Please refer to the `LICENSE.md` file for more details.

---
We welcome your contributions and feedback to make this project even more comprehensive. Thank you for visiting!
