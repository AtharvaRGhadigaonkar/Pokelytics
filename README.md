
# 🧠 Pokélytics – A Machine Learning Exploration of Pokémon Stats

Welcome to **Pokélytics**, where data science meets the Pokédex! This project dives deep into Pokémon base stats and move sets using unsupervised learning and similarity algorithms to uncover hidden patterns and insights among your favorite creatures.

---

## 🌟 Features

Pokélytics applies creative ML techniques to the world of Pokémon:

1. **KMeans Clustering**  
   Groups Pokémon into stat-based archetypes like glass cannons, tanks, or balanced types.

2. **Cosine Similarity Search**  
   Finds the most similar Pokémon based on shared moves and stat profiles.

3. **Radar Plot Visualizations**  
   Beautifully compares any Pokémon to its assigned cluster's average using intuitive radar plots.

4. **Move Matrix Engineering**  
   Transforms complex move lists into a binary matrix to fuel similarity and clustering algorithms.

---

## 🧠 Tech Stack

| Layer        | Technology Used                          |
|--------------|------------------------------------------|
| Language     | Python                                   |
| Libraries    | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn |
| Visualization| Radar Plots, Elbow Graphs, PCA           |
| Data         | Pokémon stats and move data              |

---

## 🧩 Use Cases

- **For Analysts**: Explore clustering behavior of Pokémon based on battle stats.
- **For Fans**: Discover which Pokémon are most similar to your favorites.
- **For Developers**: Use this as a base for building smarter battle or team-building systems.
- **For Recruiters**: See real ML applied in a fun, complex domain.

---

## 🚀 How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/AtharvaRGhadigaonkar/Pokelytics.git
cd Pokelytics
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebooks or Scripts
Open the Jupyter notebooks to explore each module: clustering, similarity search, and visualization.

---

## 🛠️ Folder Structure

```
📁 Pokelytics
├── 📁 data
│   └── pokemon_stats.csv
├── 📁 notebooks
│   ├── clustering.ipynb
│   ├── similarity_search.ipynb
│   └── radar_plot.ipynb
├── 📁 utils
│   └── radar_plot.py
├── 📄 README.md
└── 📄 requirements.txt
```

---

## 🧗‍♂️ Challenges Faced

- **Parsing Move Lists**: Converting deeply nested move structures into usable vectors.
- **Feature Engineering**: Creating a meaningful feature space from both categorical (types) and set-like (moves) data.
- **Dimensionality**: Compressing high-dimensional move data for clustering and visualization.

---

## 💡 Future Improvements

- Add linear regression to predict stat progression or evolution boosts.
- Deploy as an interactive web app using Streamlit or Flask.
- Integrate with PokéAPI to support all Pokémon generations.
- Add team synergy analysis based on type and move coverage.

---

## ✨ Credits

Built with 💚 by Atharva Ghadigaonkar  
*Data science made fun, one Pokéball at a time.*

---
