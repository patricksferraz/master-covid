# Master COVID - Health Data Analysis

[![Python 3.10](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/downloads/)
[![Poetry](https://img.shields.io/badge/poetry-1.0.0-orange.svg)](https://python-poetry.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

This project is a comprehensive health data analysis, focusing on medical diagnoses and outcomes. The project uses modern data processing technologies and machine learning to extract valuable insights from an extensive health dataset.

## 🚀 Features

- Large-scale data processing using PySpark
- Exploratory data analysis with Pandas and Matplotlib
- Predictive modeling with TensorFlow
- Missing data visualization with Missingno
- Feature importance analysis with SHAP
- Interactive notebooks for each processing stage

## 📋 Prerequisites

- Python 3.10
- Poetry (dependency manager)
- Java 8+ (for PySpark)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/patricksferraz/master-covid.git
cd master-covid
```

2. Install dependencies using Poetry:
```bash
poetry install
```

3. Activate the virtual environment:
```bash
poetry shell
```

## 📊 Project Structure

The project is organized in Jupyter notebooks that follow a logical processing flow:

- `0-data-engineering.ipynb`: Initial data engineering and preparation
- `1.diag-data-preparation.ipynb`: Data preparation for diagnosis analysis
- `1.desf-data-preparation.ipynb`: Data preparation for outcome analysis
- `2.diag-modeling.ipynb`: Modeling for diagnosis analysis
- `2.desf-modeling.ipynb`: Modeling for outcome analysis

## 🎯 Usage

1. Execute the notebooks in sequential order:
   - Start with the data engineering notebook
   - Proceed with data preparation
   - Finish with modeling

2. Results will be saved in the `results/` directory

## 🛠️ Technologies Used

- **PySpark**: Distributed data processing
- **Pandas**: Data manipulation and analysis
- **TensorFlow**: Machine learning modeling
- **Matplotlib**: Data visualization
- **SHAP**: Feature importance analysis
- **Missingno**: Missing data analysis

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

* **Patrick Ferraz** - [GitHub](https://github.com/patricksferraz)

## 🙏 Acknowledgments

- Open source community
- Contributors and maintainers of the libraries used
- Everyone who contributed with feedback and suggestions

---

⭐️ If this project helped you, consider giving it a star!
