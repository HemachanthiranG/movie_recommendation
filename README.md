
# **🎬 FilmGraph: A Movie Recommendation System Using Graph Theory**  

## **📌 Project Overview**  
**FilmGraph** is a **graph-based movie recommendation system** that models **users, movies, and their interactions** as a **graph structure** to provide highly **personalized and accurate movie recommendations**.  

✔ **Graph-Based Approach:** Uses **Graph Theory** to represent movies, users, and relationships.  
✔ **Advanced Algorithms:** Implements **Collaborative Filtering, Community Detection, and Content-Based Filtering**.  
✔ **Efficient Graph Traversal:** Uses **depth-first & breadth-first search** for exploring movie relationships.  
✔ **Interactive User Interface:** Allows users to **discover personalized recommendations with explainability**.  

---

## **🛠 Tech Stack**  
🔹 **Python** (Pandas, NumPy)  
🔹 **Graph Theory** (NetworkX, Graph Traversal Algorithms)  
🔹 **Machine Learning** (Scikit-learn, TF-IDF, Cosine Similarity)  
🔹 **Natural Language Processing (NLP)** (Difflib, TF-IDF Vectorizer)  
🔹 **Flask** (Web Framework)  
🔹 **Front-End:** HTML, CSS, Jinja2  

---

## **📂 Project Structure**  
```
📁 filmgraph-movie-recommendation  
 ├── 📜 movies.csv                    # Cleans and structures movie dataset   
 ├── 📜 app.py                        # Flask app for user interaction  
 ├── 📜 templates/index.html          # Web UI (HTML, CSS, Bootstrap)  

```

---

## **🚀 How to Run the Project**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/HemachanthiranG/movie_recommendation.git
cd movie_recommendation
```

### **2️⃣ Install Dependencies**  
```bash
pip install pandas numpy scikit-learn flask networkx nltk
```

### **3️⃣ Start the Recommendation System**  
```bash
python app.py
```


📌 Open your browser and visit: **`http://127.0.0.1:5000/`**  

---

## **📊 Key Features**  
✔ **Graph-Based Movie Representation** – Models **users and movies as nodes, interactions as edges**.  
✔ **Collaborative Filtering** – Uses **community detection** to suggest movies based on user clusters.  
✔ **Content-Based Filtering** – Analyzes **movie genres, cast, and keywords** to find similar movies.  
✔ **Graph Traversal for Exploration** – Uses **depth-first & breadth-first search** to uncover **hidden movie connections**.  
✔ **Flask-Powered Web UI** – Simple **interactive interface** for real-time recommendations.  

---

## **📈 Results & Impact**  
✔ **Personalized recommendations** based on user history and movie attributes.  
✔ **Explains why a movie is recommended** using graph relationships.  
✔ **Faster and more accurate** than traditional recommendation systems.  

---

## **📄 Future Enhancements**  
🔹 Integrate **Deep Learning (Graph Neural Networks - GNNs)** for more advanced recommendations.  
🔹 Add **real-time user feedback** to improve recommendation quality.  
🔹 Deploy as a **full-scale web application with user login & preferences**.  

---

🤝 Feel free to **fork, contribute, or suggest improvements**! 🚀  

