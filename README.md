# K-Means-Clustering-Analysis-of-Protein-Consumption


# 🌍🍽️ **K-Means Clustering: European Protein Consumption Patterns**

Unsupervised machine learning meets nutrition data!
This project uses **K-Means Clustering** to explore how 25 European countries differ in their **protein intake sources**, including red meat, white meat, eggs, milk, fish, cereals, starch, nuts, and fruits & vegetables.

---

## 📊 **Project Summary**

We analyzed a multivariate dataset of protein consumption to:

* 🧠 Identify **clusters of countries** with similar dietary habits
* 🔍 Visualize **nutrition patterns** using dimensional plots
* 🗺️ Explore how culture, region, and diet intersect across Europe

---

## 🧾 **Dataset Features**

| Feature     | Description                  |
| ----------- | ---------------------------- |
| `RedMeat`   | % daily intake from red meat |
| `WhiteMeat` | % from white meat            |
| `Eggs`      | % from eggs                  |
| `Milk`      | % from milk and dairy        |
| `Fish`      | % from fish                  |
| `Cereals`   | % from cereals               |
| `Starch`    | % from starchy foods         |
| `Nuts`      | % from nuts and seeds        |
| `Fr.Veg`    | % from fruits and vegetables |

Each row = 1 European country 🇪🇺

---

## 🛠️ **Tools & Technologies**

* **Language:** R
* **Libraries:** `ggplot2`, `factoextra`, `cluster`, `gridExtra`
* **Techniques:** Data normalization, K-Means clustering, cluster visualization

---

## 🧪 **Methodology**

### 🔹 1. Simple Clustering (k = 3)

* Variables used: `RedMeat` & `WhiteMeat`
* Countries grouped into 3 clusters:

  * 🍖 High red meat lovers (e.g. France, UK, Belgium)
  * 🥗 Moderate eaters from Southern/Eastern Europe
  * 🍗 Poultry-preferred regions in Central/Northern Europe

### 🔹 2. Full Clustering (k = 7)

* Used all 9 features (scaled)
* Clusters reflect **complex dietary differences** including:

  * Fish-heavy diets 🐟
  * High dairy intake 🥛
  * Cereal/starch-based consumption 🌾

### 📌 Bonus Visualization

* Combined red/white meat, milk (as point size), and fish (as shape) into one **4D scatter plot**!

---


---

## 💡 **Key Insights**

* **Western Europe** → high red meat and dairy
* **Southern/Eastern Europe** → lower meat, more plant/starch-based diets
* **Central Europe** → balanced across protein types
* Cluster analysis revealed **hidden similarities** across distant countries

---

## 📁 **Files Included**

* `protein.csv` — original dataset
* `protein_analysis.R` — R script with full clustering workflow
* `protein_cluster_visuals.pdf` — optional plots and interpretations
* `README.md` — you're here!

---

## 🧠 **Conclusion**

This project showcases how **K-Means clustering** can:

* Classify population behaviors without supervision
* Help governments or health orgs understand **diet trends**
* Guide **data-driven policy** for nutrition and wellness

---

## ✍️ **Author**

**Amandeep Randhawa**
*Data Analytics | Public Health | R Enthusiast*
