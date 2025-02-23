# **Content-Based Movie Recommendation System**

### **Summary**
This project demonstrates a content-based filtering approach for movie recommendations. By analyzing movie genres and summaries as well as user queries using TF-IDF and cosine similarity, it helps users find movies that best match their preferences.

### **Dataset**  
[Download the dataset here](https://www.kaggle.com/datasets/moazeldsokyx/the-500-best-movies-imdb)  
This dataset contains the top 500 movies from IMDb, including their ratings, genres, and plot summaries.

Download the dataset (```Top_Movies.csv```).
Place it in the project directory.
The script will automatically read the file using ```pandas```.

### **Setup**
#### **Requirements**
- Python 3.8+
- Jupyter Notebook or Python Script Execution

#### **Installation Steps**
1. Item 1 Clone the Repository
    ```shell
    git clone https://github.com/Reach2sudharsan/lumaa-spring-2025-ai-ml.git
    cd lumaa-spring-2025-ai-ml
    ```
2. Install Dependencies
    ```shell
    pip install -r requirements.txt
    ```

### **Running the Recommendation System**

- You can run the recommendation system using **Jupyter Notebook**:
- Open ```recommendation.ipynb``` and run the cells.

### **Results Example**

#### **Input:**
```shell
"I love action-packed thrillers with a Sci-Fi theme."
```

#### **Output:**

| Movie Name           | Genre                    |
|----------------------|-------------------------|
| Jurassic Park    | Action, Adventure, Sci-Fi |
| Blade Runner     | Action, Drama, Sci-Fi    |
| V for Vendetta   | Action, Drama, Sci-Fi    |
| The Avengers     | Action, Sci-Fi           |
| RoboCop          | Action, Crime, Sci-Fi    |
