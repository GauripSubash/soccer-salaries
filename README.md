# ⚽ Soccer Salaries  
*Data-driven insights into Major League Soccer (MLS) player compensation*

### By **Gauri Subash**

---

## 🚀 Project Overview
This project explores salary trends within **Major League Soccer (MLS)** using real-world data.  
It demonstrates **data analysis, visualization, and modeling** to understand how factors like player position, age, and experience influence salaries.

The project is built to showcase:
- End-to-end data analysis workflow (from raw CSV → cleaned dataset → model → visualization)
- Technical proficiency in data science tools
- Storytelling with data using **Quarto**

---

## 📂 Repository Structure

| File / Folder | Description |
|----------------|-------------|
| `mls-salaries-2007.csv` | Raw dataset used for analysis |
| `index.qmd` | Main Quarto report – introduction, goals, and key findings |
| `models.qmd` | Statistical and machine learning modeling section |
| `defense.qmd` | Project summary and defense presentation |
| `_site/` | Generated HTML site from Quarto |
| `_quarto.yml`, `_publish.yml` | Quarto configuration and deployment settings |
| `styles.css` | Custom styling for the final report |

---

## 💡 Key Features
- 🔍 **Data Cleaning & Preprocessing** – handled missing values, standardized salary columns, and derived new features (like player age).
- 📊 **Exploratory Data Analysis (EDA)** – created visuals to explore salary by position, experience, and team.
- 🤖 **Modeling** – applied regression and tree-based models to predict salary based on player attributes.
- 🌐 **Quarto Website** – professionally formatted report suitable for sharing with employers or stakeholders.
- 🧠 **Insight-Focused Storytelling** – translated technical analysis into actionable insights.

---

## 🛠️ Installation & Usage

To clone and run this project locally:

```bash
# Clone the repository
git clone https://github.com/GauripSubash/soccer-salaries.git

# Navigate into the project
cd soccer-salaries

# Ensure you have Quarto installed
# https://quarto.org/docs/get-started/

# Render the Quarto report
quarto render index.qmd

# View the generated site
quarto preview _site/index.html
