# IPL Score Predictor Using Neural Networks

This project implements a machine learning model to predict the final score of an IPL (Indian Premier League) match based on current match conditions. It combines data visualization, feature engineering, label encoding, and a neural network built with Keras and TensorFlow to forecast match totals in real time.

## 📊 Features

- Visual analysis of key trends like:
  - Matches per venue
  - Top batsmen and bowlers
  - Correlation heatmaps
- Categorical feature encoding with `LabelEncoder`
- Feature scaling using `MinMaxScaler`
- Neural network model trained with Huber Loss for robust regression
- Real-time prediction interface using `ipywidgets` in Jupyter Notebook

## 🛠 Tech Stack

- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Keras, TensorFlow, ipywidgets  
- **Modeling**: Multi-layer dense neural network with ReLU and linear activation  
- **Loss Function**: Huber Loss  
- **Interface**: Interactive score prediction via dropdowns and numeric inputs

## 🧠 How It Works

1. The dataset is preprocessed by encoding categorical variables (team names, venues, players).
2. Input features include team names, venue, current runs, wickets, overs, and batter/bowler identity.
3. A feedforward neural network is trained to regress on the target variable: total match score.
4. An interactive widget interface lets users input match context and receive a predicted score instantly.

## 🔍 Visualization Examples

- Number of matches played per venue
- Top 10 batsmen by runs
- Top 10 bowlers by wickets
- Feature correlation heatmap
