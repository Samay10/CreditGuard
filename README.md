# CreditGuard

CreditGuard is a robust machine learning application that assesses creditworthiness using predictive modeling. By comparing Logistic Regression and LightGBM models, it provides comprehensive insights into credit scoring through detailed evaluation metrics, confusion matrices, and feature importance analysis.

## Overview

CreditGuard implements a complete machine learning pipeline for credit risk assessment, featuring:

- Automated data preprocessing for both numerical and categorical features
- Comparative analysis of Logistic Regression and LightGBM models
- Comprehensive model evaluation metrics and visualizations
- Feature importance analysis for better model interpretability

## Features

### Data Processing
- Automated handling of missing values
- Intelligent categorical feature encoding
- Numerical feature scaling
- Data validation and integrity checks

### Model Implementation
- Logistic Regression with optimized hyperparameters
- LightGBM with gradient boosting capabilities
- Cross-validation for robust model evaluation
- Model performance visualization

### Analytics & Visualization
- Interactive confusion matrix displays
- Feature importance rankings and plots
- Performance metric dashboards
- Model comparison reports

## Installation

### Prerequisites
- Python 3.8+
- pip package manager
- Virtual environment (recommended)

### Setup

1. Clone the repository:
```bash
git clone https://github.com/Samay10/CreditGuard.git
cd CreditGuard
```

2. Create and activate a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## Project Structure

```
CreditGuard/
├── 10imp_CreditGuard.png     # Feature importance visualization
├── CreditRisk.ipynb          # Main Jupyter notebook containing the analysis
├── creditguard CMs.png       # Confusion matrices visualization
├── LICENSE                   # GNU General Public License v3.0
└── README.md                 # Project documentation
```

## Usage

1. Ensure you have all prerequisites installed
2. Open `CreditRisk.ipynb` in Jupyter Notebook or JupyterLab:
```bash
jupyter notebook CreditRisk.ipynb
```
3. Follow the step-by-step instructions in the notebook to:
   - Load and preprocess your data
   - Train the models
   - Evaluate performance
   - Visualize results

## Visualizations

The project includes two key visualization files:
- `10imp_CreditGuard.png`: Shows the top 10 most important features identified by the model
- `creditguard CMs.png`: Displays confusion matrices for model performance comparison

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch:
```bash
git checkout -b feature/your-feature-name
```
3. Commit your changes:
```bash
git commit -m "Add some feature"
```
4. Push to your fork:
```bash
git push origin feature/your-feature-name
```
5. Open a Pull Request

### Development Guidelines

- Follow PEP 8 style guidelines
- Add appropriate comments and documentation
- Test your changes thoroughly
- Update visualizations as needed

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Author

**Samay Deepak Ashar**
- GitHub: [@Samay10](https://github.com/Samay10)

## Acknowledgments

- **Libraries**: scikit-learn, LightGBM, pandas, numpy, matplotlib
- **Community**: Thanks to all contributors and the open-source community
- **Inspiration**: Credit risk assessment best practices and industry standards

## Support

For support and questions:
- Open an issue on GitHub
- Contact the maintainer through GitHub

---
*Note: This project is actively maintained. For the latest updates and features, please check the GitHub repository.*
