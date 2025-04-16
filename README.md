# Bollywood_Films_Analysis
🎬 A complete exploratory data analysis (EDA) project on Indian movies to uncover trends in revenue based on genre, cast, crew, and production features.

# 🎬 Bollywood Movie Revenue Analysis

Welcome to the **Movie Revenue EDA Project** — an insightful data analysis project exploring the financial performance of Indian films based on features like genre, cast, director, release timing, and more! 📊✨

---

## 📁 Dataset Overview

| Feature | Description |
|--------|-------------|
| `Movie_Name` | Name of the movie 🎥 |
| `Release_Period` | Time of release (e.g., Holiday, Normal) 🗓️ |
| `Whether_Remake` | Whether it's a remake 🎞️ |
| `Whether_Franchise` | Part of a franchise 🧩 |
| `Genre` | Genre of the film (e.g., drama, thriller) 🎭 |
| `New_Actor`, `New_Director`, `New_Music_Director` | Whether these roles were new faces 🆕 |
| `Lead_Star`, `Director`, `Music_Director` | Key personnel behind the film 🌟🎬🎶 |
| `Number_of_Screens` | Number of screens released on 🖥️ |
| `Revenue(INR)` | Revenue earned in Indian Rupees 💰 |
| `Budget(INR)` | Production budget in Indian Rupees 🪙 |

---

## 🔍 Project Goals

- 🧹 Clean and preprocess the dataset
- 📊 Perform Exploratory Data Analysis (EDA)
- 📈 Visualize trends and relationships in the data
- 🏆 Identify key factors that influence revenue

---

## 📌 Key Findings

- 🎯 **Revenue is strongly influenced by the number of screens and budget.**
- 🎭 **Genres like thriller and drama tend to show higher revenue variance.**
- 🆕 **Movies with debut actors or directors sometimes outperform expectations.**
- 📅 **Holiday releases generally generate higher revenues.**
- 🧠 **Franchise status does not always guarantee success.**

---

## 📊 Visualizations

Some visual insights created:
- ✅ Revenue vs. Budget scatter plot
- ✅ Revenue distribution by genre
- ✅ Box plots of revenue against new actors/directors/music directors
- ✅ Top 10 movies by revenue (bar chart)
- ✅ Revenue per screen analysis
- ✅ Correlation heatmap of all numeric variables

---

## 💻 How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/movie-revenue-eda.git
cd movie-revenue-eda

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook Movie_EDA.ipynb
