
# RiskyMind

**RiskyMind** is a comprehensive repository for analyzing risky decision-making behaviors. 
This repository includes a behavioral task implemented in Psychtoolbox and provides tools for analyzing 
the data, including participant filtering and outlier detection.

---

## Repository Overview

### 1. **Task Implementation**
- Developed in **Psychtoolbox** (MATLAB) for investigating risk-related decision-making.
- Participants make choices between gambles under varying conditions.

### 2. **Data Analysis Pipeline**
- Outlier detection based on:
  - Null model comparisons.
  - IQR filtering for response times and acceptance rates.
- Analysis of acceptance/rejection patterns across conditions.

### 3. **Key Features**
- Modular code for pre-processing and analysis.
- Visualizations for response time and acceptance rate distributions.
- Easy customization for additional metrics or conditions.

---

## Files and Folders

### 1. **`/task/`**
Contains the Psychtoolbox scripts for running the behavioral experiment.

### 2. **`/data/`**
Sample and processed datasets used in the analyses.

### 3. **`/analysis/`**
Python scripts for pre-processing and analyzing behavioral data.

---

## Setup Instructions

### Prerequisites
- **MATLAB** with **Psychtoolbox** for running the task.
- **Python 3.8+** with required libraries: `pandas`, `numpy`, `scipy`, `matplotlib`.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RiskyMind.git
   cd RiskyMind
   ```
2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

### Running the Task
1. Open MATLAB.
2. Navigate to the `/task/` directory.
3. Run the script:
   ```matlab
   main_task.m
   ```

### Analyzing Data
1. Place your dataset in the `/data/` directory.
2. Run the analysis script:
   ```bash
   python analysis_script.py
   ```

---

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request or open an issue.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact
For questions or collaboration, please reach out at **your.email@example.com**.
