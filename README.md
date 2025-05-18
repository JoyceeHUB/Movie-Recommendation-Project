# Movie Recommendation Project

**Tools:** Python, Pandas, scikit-surprise, Jupyter Notebook  
**Dataset:** MovieLens 100K (https://grouplens.org/datasets/movielens/100k/)

## Project Overview
This project showcases a recommendation system built using collaborative filtering techniques.  
It predicts personalized movie suggestions based on user rating patterns using the MovieLens 100K dataset.

## Key Steps
1. **Data Loading & Cleaning**  
   - Loaded `u.data` (ratings) and `u.item` (movie titles) files.  
   - Merged into a single DataFrame for analysis.

2. **Model Building**  
   - Used the Surprise library’s `KNNBasic` algorithm for user-based collaborative filtering.  
   - Trained on 80% of the data and tested on 20%.

3. **Recommendation Function**  
   - Created `get_top_n_recommendations(user_id, n)` to predict top N movies for any user.  
   - Ranked movies by estimated rating from similar users.

4. **Testing & Results**  
   - Demonstrated recommendations for sample users.  
   - Showed top 10 movie suggestions for each test case.

## How to Run

1. Clone this repo  
   ```bash
   git clone https://github.com/joyceeHUB/movie-recommendation-system.git
   cd movie-recommendation-system
2. Install dependencies & launch notebook 
   ```bash
   pip install pandas scikit-surprise notebook  
   jupyter notebook
3. Launch Jupiter notebook
   ```bash
   jupyter notebook
