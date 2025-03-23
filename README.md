# 🎬 Movie Recommendation System Frontend

This repository contains the **frontend** for the [Movie Recommendation System](https://github.com/joyjeetcoding/movie-recommender-system?tab=readme-ov-file) built using **Streamlit**.

## ⚠️ Important Note
The `.pkl` files required for the recommendation system are not included in this repository due to their large size (~187 MB). You must generate these files by executing the `pickle.dump` command in the backend and copy them to this project.

## 📥 Setup Instructions

### 1️⃣ Create a Virtual Environment
It is recommended to run the application in a **virtual environment** to avoid dependency conflicts.

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On macOS/Linux
source venv/bin/activate

# On Windows
venv\Scripts\activate
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Copy & Paste Pickle Files
- Run the backend script to generate the `.pkl` files.
- Copy these files from the **backend project** and place them in the appropriate directory in this frontend project.

### 4️⃣ Run the Streamlit Application
```bash
streamlit run app.py
```
This will launch the frontend UI for movie recommendations.

## 🎯 Features
- Load **precomputed movie similarity data** from `.pkl` files.
- Provide **movie recommendations** based on user input.
- Simple and interactive UI built using **Streamlit**.

---

🚀 **Happy Coding!**
