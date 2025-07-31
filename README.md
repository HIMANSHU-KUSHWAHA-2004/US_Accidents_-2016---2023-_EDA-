<div align="center">
  <h1>🚗 US Accidents Analysis (2016-2023)</h1>
  <p><em>Comprehensive Exploratory Data Analysis of US Road Accidents</em></p>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Seaborn">
  <img src="https://img.shields.io/badge/Folium-77B829?style=for-the-badge&logo=folium&logoColor=white" alt="Folium">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
</div>

<br>

<div align="center">
  <img src="https://img.shields.io/github/stars/HIMANSHU-KUSHWAHA-2004/US_Accidents_-2016---2023-_EDA-?style=social" alt="GitHub stars">
  <img src="https://img.shields.io/github/forks/HIMANSHU-KUSHWAHA-2004/US_Accidents_-2016---2023-_EDA-?style=social" alt="GitHub forks">
  <img src="https://img.shields.io/github/watchers/HIMANSHU-KUSHWAHA-2004/US_Accidents_-2016---2023-_EDA-?style=social" alt="GitHub watchers">
</div>

---

## 🎯 Project Overview

A comprehensive analysis of **7.5+ million** US road accidents from 2016-2023, uncovering critical patterns in traffic safety through data visualization and statistical analysis.

| Dataset Info | Value |
|--------------|-------|
| **Records** | 7.5M+ accident reports |
| **Coverage** | 49 U.S. states |
| **Time Span** | 2016-2023 (8 years) |
| **Features** | 47+ columns |
| **Size** | ~2.2 GB |

---

## 📊 Key Findings

### 🏙️ **Top Accident Cities**
- **Miami** leads with **186,949** accidents
- Houston, Los Angeles, Charlotte, and Phoenix complete the top 5

### 📈 **Temporal Patterns**
- **2021** recorded the highest accidents: **1.2M+ incidents**
- **Rush hours** (7-9 AM & 4-6 PM): **500,000+** accidents
- **Safest time**: 12-4 PM with lowest accident rates

### 🌡️ **Environmental Factors**
- **Peak temperature**: 73°F shows highest accident density
- **Seasonal trend**: Accidents decrease Jan-July, increase toward December
- **Weather impact**: Mid and Hot categories account for 1.2M+ accidents

---

## 📋 Dataset Information

**Source:** [US Accidents Dataset on Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)

**Features include:**
- Severity levels, GPS coordinates, timestamps
- Weather conditions (temperature, humidity, visibility)
- Road features (traffic signals, crossings, junctions)
- Geographic information (city, state, county)

> ⚠️ **Note:** Dataset not included due to size (2.2GB). Download from Kaggle before running locally.

---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/HIMANSHU-KUSHWAHA-2004/US_Accidents_-2016---2023-_EDA-.git
cd US_Accidents_-2016---2023-_EDA-
```

### 2. Setup Environment
```bash
# Create virtual environment
python -m venv venv

# Activate (Windows)
venv\Scripts\activate

# Activate (macOS/Linux)
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Download Dataset
Visit [Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents) and download the CSV file to project directory.

### 5. Run Analysis
```bash
jupyter notebook EDA_US_Accidents.ipynb
```

---

## 🛠️ Tech Stack

**Data Processing : ** pandas, numpy  
**Visualization : ** matplotlib, seaborn, folium  
**Environment : ** Jupyter Notebook, Python 3.8+

---

## 📁 Project Structure

```
📦 US_Accidents_EDA
├── 📊 EDA_US_Accidents.ipynb    # Main analysis notebook
├── 📋 requirements.txt          # Dependencies
├── 📖 README.md                # Documentation
├── 📂 assets/                  # Visualizations
│   └── 📈 output_charts_and_visualizations/
└── 📂 data/                    # Dataset (download separately)
    └── 📄 US_Accidents_March23.csv
```

---

## 📈 Analysis Highlights

- **Geographic Heatmaps** - Accident density across US regions
- **Temporal Analysis** - Hourly, daily, and seasonal patterns  
- **Weather Correlation** - Environmental impact on accidents
- **Severity Distribution** - Accident severity level analysis
- **Statistical Insights** - KDE analysis and trend identification

---

## 🤝 Contributing

Contributions welcome! Please feel free to:

- Report bugs or issues
- Suggest new analysis ideas
- Improve visualizations
- Enhance documentation

**To contribute:**
1. Fork the repository
2. Create feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -m 'Add improvement'`)
4. Push branch (`git push origin feature/improvement`)
5. Open Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Himanshu Kushwaha**  
*Data Science Enthusiast*

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HIMANSHU-KUSHWAHA-2004)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-kushwaha-49b360293)

---

<div align="center">
  <h3>⭐ Star this repository if you found it helpful!</h3>
  <p><em>Made with ❤️ for the data science community</em></p>
</div>
