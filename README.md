# Churn Analysis

This repository provides an end-to-end churn analysis solution using data science techniques implemented in Jupyter Notebooks.  
**This project uses Deep Learning, specifically an Artificial Neural Network (ANN) architecture, to build predictive models for customer churn.**  
**Additionally, a Streamlit web app has been developed to provide an interactive interface for users to explore and predict customer churn.**

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Streamlit Web App](#streamlit-web-app)
- [Contributing](#contributing)
- [License](#license)

## Overview

Churn analysis helps businesses understand why customers are leaving and what factors influence their decisions.  
This project leverages data analysis, deep learning (ANN), and a user-friendly Streamlit web app to predict customer churn and provide actionable insights.

## Project Structure


```
.
├── data/                # Raw and processed data files
├── notebooks/           # Jupyter Notebooks for analysis and modeling (including ANN models)
├── src/                 # Source code for utility functions and scripts
├── streamlit_app/       # Streamlit web app source code
├── README.md            # Project documentation
└── requirements.txt     # Python dependencies
```

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/swapnilbilgoji/Churn-Analysis.git
   cd Churn-Analysis
   ```
2. Set up a virtual environment (optional but recommended):
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

Open and run the Jupyter Notebooks in the `notebooks/` directory to explore the data, analysis, and deep learning (ANN-based) predictive models.

```sh
jupyter notebook
```

You can also use scripts in the `src/` directory for data preprocessing or model training.

## Streamlit Web App

The project includes a Streamlit web app for interactive customer churn prediction.

To run the Streamlit app locally:

```sh
cd streamlit_app
streamlit run app.py
```

## Contributing

Contributions are welcome! Please open issues or pull requests with suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
