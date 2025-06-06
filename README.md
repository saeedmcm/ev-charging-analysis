# Electric Vehicle Charging Station Analysis
## Multi-Output Deep Learning and Policy Analysis for Urban EV Infrastructure

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Commit](https://img.shields.io/github/last-commit/saeedmcm/ev-charging-analysis)](https://github.com/saeedmcm/ev-charging-analysis/commits/main)
[![Repo Size](https://img.shields.io/github/repo-size/saeedmcm/ev-charging-analysis)](https://github.com/saeedmcm/ev-charging-analysis)

### Core Technologies
![Python](https://img.shields.io/badge/Python-3.9-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0-red)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2-F7931E)
![XGBoost](https://img.shields.io/badge/XGBoost-1.7-darkgreen)
![Optuna](https://img.shields.io/badge/Optuna-3.0-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-4c72b0)

## Published Research
This project has led to two peer-reviewed publications:

1. [A multi-output deep learning model for energy demand and port availability forecasting in EV charging infrastructure](https://doi.org/10.1016/j.energy.2025.134582)
   - Published in Energy (2025)
   - DOI: 10.1016/j.energy.2025.134582
   - Develops a novel multi-output deep learning approach for simultaneous prediction of energy demand and port availability
   - Demonstrates improved forecasting accuracy through joint learning of related tasks

2. [Policy interventions and urban characteristics in modeling electric vehicle charging infrastructure utilization](https://doi.org/10.1016/j.cstp.2024.101309)
   - Published in Case Studies on Transport Policy (2024)
   - DOI: 10.1016/j.cstp.2024.101309
   - Analyzes the impact of policy interventions on EV charging infrastructure usage
   - Examines how urban characteristics influence charging station utilization patterns

## Project Overview
This project analyzes electric vehicle (EV) charging station usage patterns and their optimization in urban environments. The analysis focuses on understanding the impact of policy interventions, specifically fee policies, while developing predictive models for energy consumption and port availability.

### Key Features
- Comprehensive analysis of EV charging station utilization patterns
- Evaluation of fee policy impact on station usage
- Time series forecasting for energy consumption
- Multi-output prediction models for port availability
- Interactive geospatial visualizations
- Statistical analysis of usage patterns

## Data Source
- **Provider:** City of Palo Alto Open Data Portal
- **Time Period:** July 2011 - December 2020
- **Format:** CSV file
- **Access Method:** Direct URL download

## Project Structure
1. **Project Introduction**
   - Purpose and objectives
   - Research motivation
   - Key research questions
   - Methodology overview

2. **Data Acquisition and Preprocessing**
   - Data collection and cleaning
   - Feature engineering
   - Temporal data processing
   - Spatial data preprocessing

3. **Exploratory Data Analysis**
   - Temporal pattern analysis
   - Spatial distribution visualization
   - Statistical analysis
   - Correlation studies

4. **Policy Impact Analysis**
   - Pre-post fee policy implementation comparison
   - Statistical significance testing
   - User behavior pattern analysis

5. **Predictive Modeling**
   - Time-series forecasting
   - Multi-output prediction models
   - Model validation and performance assessment

## Key Findings

### Deep Learning Model Performance
- Developed a novel multi-output deep learning architecture that simultaneously predicts energy demand and port availability
- Achieved superior forecasting accuracy compared to single-task models
- Successfully captured temporal dependencies and seasonal patterns in charging behavior
- Demonstrated robust performance across different urban contexts and charging station types

### Policy Impact Analysis
- Identified key urban characteristics that influence charging station utilization
- Quantified the effectiveness of various policy interventions on infrastructure usage
- Provided evidence-based recommendations for policy makers and urban planners
- Developed a framework for assessing policy impacts on charging infrastructure

### Urban Infrastructure Optimization
- Created data-driven insights for optimal charging station placement
- Analyzed the relationship between urban features and charging demand patterns
- Developed recommendations for infrastructure scaling based on urban characteristics
- Identified critical factors for successful EV charging infrastructure deployment

## Requirements
```python
# Core Data Processing
pandas>=1.3.0
numpy>=1.20.0
missingno>=0.4.2

# Machine Learning
scikit-learn>=0.24.2
xgboost>=1.4.2
catboost>=0.26
pytorch>=1.9.0
prophet>=1.0
optuna>=2.10.0

# Visualization
matplotlib>=3.4.2
seaborn>=0.11.1
folium>=0.12.1
keplergl>=0.3.2

# Geospatial Analysis
pgeocode>=0.3.0

# Time Series Analysis
statsmodels>=0.12.2
holidays>=0.11.1
```

## Installation
1. Clone this repository:
```bash
git clone [your-repository-url]
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage
1. Open the Jupyter notebook:
```bash
jupyter notebook Final_EV_Notebook.ipynb
```

2. Follow the notebook sections sequentially to:
   - Load and preprocess the data
   - Perform exploratory analysis
   - Evaluate policy impacts
   - Train and evaluate predictive models

## Results and Findings
- Detailed analysis of EV charging patterns
- Impact assessment of fee policy implementation
- Predictive model performance metrics
- Recommendations for infrastructure optimization

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Contact
[Your Name] - [Your Email]

Project Link: [https://github.com/yourusername/your-repo-name]

## Citations
If you use this work in your research, please cite our published papers:

```bibtex
@article{makaremi2025multi,
  title={A multi-output deep learning model for energy demand and port availability forecasting in EV charging infrastructure},
  author={Makaremi, Seed and [Other Authors]},
  journal={Energy},
  volume={},
  pages={134582},
  year={2025},
  publisher={Elsevier},
  doi={10.1016/j.energy.2025.134582}
}

@article{makaremi2024policy,
  title={Policy interventions and urban characteristics in modeling electric vehicle charging infrastructure utilization},
  author={Makaremi, Seed and [Other Authors]},
  journal={Case Studies on Transport Policy},
  volume={},
  pages={101309},
  year={2024},
  publisher={Elsevier},
  doi={10.1016/j.cstp.2024.101309}
}
``` 