# 🎬 Movie Recommendation System - Frontend

This repository contains the frontend implementation for the **[Movie Recommendation System](https://github.com/joyjeetcoding/movie-recommender-system?tab=readme-ov-file)** using **Streamlit**.

⚠️ **Note:** The `.pkl` files are not included in this repository due to their large size (~187 MB). Please download them from the backend repository and place them in the appropriate directory.

## 📥 Setup Instructions

1️⃣ **Copy & Paste Pickle Files**
- After executing the `pickle.dump` command in the backend, copy the generated `.pkl` files from the **Movie Recommendation System** backend.
- Paste them into this frontend project directory.

2️⃣ **Load Pickle Files**
- Ensure that the pickle files are correctly loaded in the frontend application for recommendations.

3️⃣ **Create the Frontend using Streamlit**
- Build an interactive UI using **Streamlit**.
- Display recommended movies based on user input.

4️⃣ **Implement the `recommend` Function**
- Create a function `recommend(movie_name)` to return **5 similar movies** based on the model.

## 🚀 Running the Application
Run the following command in the terminal:
```bash
streamlit run app.py
```
This will launch the Streamlit web application.