Checkout the website :https://movie-recommender-system-aiffssrmb2n8u6qxmwr3ro.streamlit.app/

---


## 📽️ Movie Recommendation System

A content-based movie recommender system built using Python, pandas, scikit-learn, and Streamlit. It recommends movies based on similarity scores between movie descriptions using cosine similarity.


![App Demo](https://user-images.githubusercontent.com/your-image-link/demo.gif) <!-- Optional demo gif/image -->


---

## 🔧 Features

* 🔍 Search for a movie and get 5 similar movie recommendations
* 🧠 Uses cosine similarity on movie metadata (genre, cast, etc.)
* 🌐 Built with Streamlit for an interactive UI
* 🧾 Clean UI and fast performance

---

## 📁 Project Structure

```
📦 Movie-Recommendation-System/
┣ 📂 .streamlit/
┃ ┗ config.toml
┣ 📂 data/
┃ ┗ similarity.pkl  # (Handled via Git LFS)
┣ 📜 app.py          # Streamlit app
┣ 📜 movies.csv      # Movie metadata
┣ 📜 requirements.txt
┣ 📜 README.md
```

---

## 🚀 Demo

Run it locally in your browser using:

```bash
streamlit run app.py
```

---

## 🛠️ Installation & Setup

### 1. Clone the repo

```bash
git clone https://github.com/Aaryan-Lunis/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

### 2. Setup virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Make sure Git LFS is installed

This is needed to fetch `similarity.pkl`:

```bash
git lfs install
git lfs pull
```

### 5. Run the app

```bash
streamlit run app.py
```

Open your browser and go to: `http://localhost:8501/`

---

## 📦 Requirements

* Python 3.8+
* pandas
* scikit-learn
* streamlit
* Git LFS (for large file support)

Install them using:

```bash
pip install -r requirements.txt
```

---

## 📌 Example

Enter any movie title like `The Dark Knight`, and get 5 recommendations such as:

* Batman Begins
* The Dark Knight Rises
* Inception
* Interstellar
* Joker

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---



---
