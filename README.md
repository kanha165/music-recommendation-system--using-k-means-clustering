# 🎵 Hindi Song Recommendation System (ML Project)

A Machine Learning based **Content-Based Music Recommendation System** that suggests similar Hindi songs using **audio features** from Spotify dataset.  
The system is trained using **Cosine Similarity** and works using a **saved `.pkl` model file**.

---

## 📌 Project Features

✅ Recommends similar songs based on audio features  
✅ Uses Machine Learning (Cosine Similarity)  
✅ Fast recommendations using a trained `.pkl` model  
✅ Command-line based recommendation system  
✅ Easy to extend with Streamlit / Web App  
✅ Works on real Spotify audio data  

---

## 🧠 Machine Learning Technique Used

- **Feature Scaling:** StandardScaler  
- **Similarity Metric:** Cosine Similarity  
- **Model Type:** Content-Based Filtering  
- **Data Source:** Spotify Audio Features CSV  

---

## 📂 Project Folder Structure
K-means clustering/
│
├── dataset.csv
├── train_model.py
├── test_model.py
├── song_recommender.pkl
└── README.md



---

## ⚙️ Installation & Setup

### 🔹 1. Clone the Project or Copy Files
Place all files in one folder.

---

### 🔹 2. Install Required Libraries

```bash
pip install pandas numpy scikit-learn

🔹 3. Train the Model
Run this only once to generate the .pkl file:>>>>>python train_model.py

this will create >>>song_recommender.pkl



🔹 4. Run Recommendation System >>>>python test_model.py



🧪 How It Works

1.User enters a song name

2.Model searches that song in dataset

3.Audio features are compared using cosine similarity

4.Top 5 similar songs are recommended




Enter a song name: Sadka

🎵 Recommended Songs:
➡️ Zehnaseeb — Vishal-Shekhar
➡️ Surili Akhiyon Wale — Rahat Fateh Ali Khan
➡️ Hona Tha Pyar — Atif Aslam
➡️ Rait Zara Si — Arijit Singh
➡️ Tu / You — Armaan Malik




📊 Audio Features Used for Recommendation

acousticness

danceability

duration_ms

energy

speechiness

tempo

valence

instrumentalness

liveness

loudness




🚀 Future Enhancements

✅ Streamlit Web UI
✅ Song Search with Thumbnail
✅ Spotify Link Redirection
✅ Genre-based Filtering
✅ Artist-based Recommendation
✅ Cloud Deployment



🧑‍💻 Author

Name: Kanha Patidar
Branch: B.Tech (CSIT)
3rd year 
Interest Areas: Machine Learning, Data Science, Python Development
Location: Indore, India





📜 License

This project is open-source and free to use for educational purposes.


⭐ Support

If you like this project, don’t forget to star it ⭐ and share it with others!

