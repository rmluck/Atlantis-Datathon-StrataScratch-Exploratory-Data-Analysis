# Atlantis Datathon StrataScratch Exploratory Data Analysis

*By Rohan Mistry - Last updated June 15, 2025*

---

## 📖 Overview

Conducted in-depth exploratory data analysis using [StrataScratch](https://www.stratascratch.com/) datasets. Collaborated with team to visualize insights on market supply and demand, focusing on elevating Airbnb user experience for guests and hosts. Developed and tested decision tree classifier machine learning model using Python that achieved 89.35% accuracy rate leveraging tools like DeepNote and Alteryx Designer.

🏆 Received the 1st Place Prize for **Best Analysis of Airbnb Market in Dublin [Sponsored by StrataScratch]** at the **2024 UC Irvine Atlantis Datathon**.

🔗 **Devpost**: [https://devpost.com/software/lost-in-dublin](https://devpost.com/software/lost-in-dublin)

---

## 📁 Contents

```bash
├── data/                # StrataScratch datasets
├── docs/                # Datathon instructions
├── notebooks/           # Core data analysis and visualization logic
├── output/              # Generated analysis visualizations
├── README.md            # Project documentation
└── requirements.txt     # Python dependencies
```

---

## 🌟 Features

* **Real-World Datasets**: Cleaned and pre-processed large Airbnb datasets provided by StrataScratch
* **Data Explorations**: Conducted data analysis based on variables such as booking status, guest sizes, duration of stays, global search queries, price preferences, room types, host acceptance rates
* **Machine Learning Model**: Constructed simple machine learning model built on decision tree and random forest classifiers, trained/tested and achieved 89.35% accuracy
* **Data Visualizations**: Created custom visual summaries (e.g., bar plots, box plots, performance heat maps, histograms, geographical heat maps using [Natural Earth](https://www.naturalearthdata.com/) datasets, confusion matrices)
* **Data Analysis**: Generated key business insights backed by data
* **Presentation**: Compiled a formal [presentation report](/docs/Airbnbs%20in%20Dublin.pdf) with narrative and statistical context

---

## Installation Instructions

To view or re-run the analysis locally:
1. Clone the repository:
```bash
git clone https://github.com/rmluck/Atlantis-Datathon-StrataScratch-Exploratory-Data-Analysis.git
cd Atlantis-Datathon-StrataScratch-Exploratory-Data-Analysis
```
2. Set up a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Open the notebook:
```bash
jupyter notebook notebooks/data_analysis.ipynb
```

---

## 💡 Usage

Run the Jupyter notebook to view the data analysis and associated visual summaries. See the [output](/output/) folder for sample visualizations.

---

## 🚧 Future Improvements

* Automate analysis with a script-based workflow (__.py__ files)
* Extend analysis with more robust predictive modeling

---

## 🧰 Tech Stack

* Python, Jupyter Notebook
* **Data Analysis**: `pandas`, `numpy`, Alteryx Designer
* **Machine Learning**: `scikit-learn`
* **Visualization**: `seaborn`, `matplotlib`
* **Presentation**: DeepNote, Google Slides
* **Collaboration**: Google Workspace

---

## 🙏 Contributions / Acknowledgements

This project was completed along with **Atlantis Datathon** participants Alex Ngo, Rahul Joshi, and Colin Yee.
