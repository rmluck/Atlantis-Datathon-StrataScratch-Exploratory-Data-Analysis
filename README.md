# Atlantis Datathon StrataScratch Exploratory Data Analysis

*By Rohan Mistry - Last updated June 15, 2025*

---

## 📖 Overview

This project was developed as part of the **2024 UC Irvine Atlantis Datathon**, using a dataset provided by [StrataScratch](https://www.stratascratch.com/) that contains data related to the Airbnb market in Dublin, Ireland. The goal of the analysis was to uncover actionable insights related to market demand and supply, aiming to elevate the Airbnb experience for guests and hosts through data exploration, transformation, and visualization.

🏆 Received the 1st Place Prize for **Best Analysis of Airbnb Market in Dublin [Sponsored by StrataScratch]**

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
* **Data Analysis**: __pandas__, __numpy__, __scikit-learn__
* **Machine Learning**: __scikit-learn__
* **Visualization**: __seaborn__, __matplotlib__
* **Presentation**: DeepNote, Alteryx Designer

---

## 🙏 Contributions / Acknowledgements

This project was completed along with **Atlantis Datathon** participants Alex Ngo, Rahul Joshi, and Colin Yee.