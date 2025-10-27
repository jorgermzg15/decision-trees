# Decision Trees for Predictive Modeling

This repository contains Jupyter Notebooks focused on Decision Trees for both Classification and Regression tasks. The project is designed to help students understand and implement these powerful predictive modeling techniques.

## Project Overview

The project includes implementation and analysis of Decision Trees, covering:

- Decision Trees for Regression
- Decision Trees for Classification
- Tree Visualization and Interpretation
- Model Evaluation and Validation
- Hyperparameter Tuning
- Data Preprocessing and Feature Engineering

## Project Structure

- `Decision Trees para Regresion.ipynb`: Jupyter notebook covering Decision Trees for regression problems
- `Decision Trees para Clasificación.ipynb`: Jupyter notebook focusing on Decision Trees for classification tasks
- `requirements.txt`: List of Python packages required for this project
- `car_price_data.csv`: Dataset for regression analysis
- `phone_classification.csv`: Dataset for classification tasks
- `diamonds.db`: SQLite database for additional practice
- `SQLite_databases_for_learning_data_science/`: Directory containing various SQLite databases for practice

## Tools and Technologies

- Python (3.x recommended)
- Jupyter Notebook
- Data Analysis Libraries:
  - Pandas (≥2.3.1)
  - Plotly (≥6.3.0)
  - Scikit-learn (≥1.7.1)
  - Category Encoders (≥2.8.1)
  - SciPy (≥1.16.1)
  - NumPy (≥2.3.2)
  - pydotplus (for tree visualization)

## Installation Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/jorgermzg15/decision-trees.git
   cd decision-trees
   ```

2. Create a virtual environment:
   ```bash
   # On macOS/Linux
   python -m venv .venv
   source .venv/bin/activate

   # On Windows
   python -m venv .venv
   .\.venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Open either `Decision Trees para Regresion.ipynb` or `Decision Trees para Clasificación.ipynb` in your browser and start learning!

## Troubleshooting

If you encounter any issues:

1. Make sure your virtual environment is activated (you should see `(.venv)` in your terminal)
2. Try upgrading pip before installing requirements:
   ```bash
   pip install --upgrade pip
   ```
3. If you have problems with tree visualization:
   ```bash
   pip install pydotplus graphviz
   ```
   Note: You might need to install Graphviz separately on your system:
   - macOS: `brew install graphviz`
   - Linux: `sudo apt-get install graphviz`
   - Windows: Download from [Graphviz website](https://graphviz.org/download/)

4. If you encounter kernel issues in Jupyter:
   ```bash
   python -m ipykernel install --user
   ```

## For Students

This repository is designed to provide hands-on experience with Decision Trees. To get the most out of it:

1. Follow the installation instructions carefully
2. Execute the notebook cells in order
3. Pay special attention to the tree visualization sections
4. Experiment with different hyperparameters to understand their impact
5. Try the models with different datasets from the provided SQLite databases
6. Complete any exercises or challenges provided in the notebooks

## License

This project is available for educational purposes. Feel free to use and learn from it!

## Database Credits

The SQLite databases used in this project are sourced from the [SQLite Databases for Learning Data Science](https://github.com/davidjamesknight/SQLite_databases_for_learning_data_science) repository by David James Knight.
