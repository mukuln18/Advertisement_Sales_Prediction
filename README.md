# 📊 Advertising Sales Prediction

This project explores the relationship between advertising spending and product sales using a machine learning approach. The objective is to predict sales based on investments in various advertising channels, specifically focusing on TV and Radio ads.

## 📁 Dataset

The dataset contains 200 records with the following columns:

- `TV`: Budget spent on TV advertisements  
- `Radio`: Budget spent on Radio advertisements  
- `Newspaper`: Budget spent on Newspaper advertisements  
- `Sales`: Corresponding sales revenue

## ⚙️ Technologies Used

- **Language**: Python  
- **Environment**: Jupyter Notebook  
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – Machine learning and evaluation

## 🧠 Project Workflow

1. **Data Exploration**
   - Loaded the dataset and explored its structure
   - Visualized data using box plots and correlation heatmaps

2. **Feature Selection**
   - Selected `TV` and `Radio` as independent variables
   - Dropped `Newspaper` due to weaker correlation with `Sales`

3. **Model Training**
   - Split data into training and testing sets (80/20)
   - Applied Polynomial Linear Regression using `scikit-learn`

4. **Evaluation**
   - Measured model performance with RMSE and R² metrics

## 📈 Results

- The model demonstrates a strong linear relationship between TV/Radio advertising and sales.
- Polynomial features helped capture non-linear interactions, improving accuracy.

## 🚀 Getting Started

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/advertising-sales-prediction.git
   cd advertising-sales-prediction
   ```

2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook ASP.ipynb
   ```

## 🧑‍💻 Use Case

This project is ideal for:
- Demonstrating basic regression modeling
- Learning how to evaluate model performance
- Understanding the impact of advertising budget allocation
