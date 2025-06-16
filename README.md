# Movie IMDb Rating Predictor

A simple machine learning project that predicts the **IMDb rating** of a movie based on its **release year** and **Rotten Tomatoes score**. Built using Python, pandas, scikit-learn, and visualized with seaborn and matplotlib.

---

##  Dataset

- **Source**: [MoviesOnStreamingPlatforms_updated.csv](https://github.com/amankharwal/Website-data/blob/master/MoviesOnStreamingPlatforms_updated.csv)
- **Rows**: 16,744
- **Key Columns Used**:
  - `Year`
  - `IMDb`
  - `Rotten Tomatoes`

---

## 🔧 Project Steps

1. **Data Loading & Cleaning**
   - Handle missing values
   - Convert percentage strings to float

2. **Visualization**
   - Heatmap showing correlation of features
   - Scatter plot of actual vs predicted IMDb scores

3. **Modeling**
   - Linear Regression with `scikit-learn`
   - Evaluation using R² Score and RMSE

4. **Prediction**
   - Make prediction on a new sample movie

---

## Example Output
Dataset loaded with shape: (16744, 17)

R² Score: 0.37  RMSE: 0.71

Predicted IMDb rating for sample movie: 7.34


---

## Tech Stack

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter

---

## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Duncan1738/movie-imdb-predictor.git
   cd movie-imdb-predictor
Open the .ipynb notebook in Google Colab or Jupyter.

Install required packages:
pip install pandas seaborn matplotlib scikit-learn
Run all cells and customize the prediction inputs!

📈 Future Ideas
Add more features (platform, genre, runtime)

Try non-linear models like XGBoost

Build a web app using Streamlit

🙌 Author
[Duncan Kibet]
MIT LICENCE

