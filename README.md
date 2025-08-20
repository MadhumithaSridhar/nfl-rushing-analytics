# 🏈 NFL Rushing Play Analysis

### 📌 Introduction

This project explores how player speed, field position, and defensive alignment affect the success of rushing plays in the NFL. Using player tracking data from the [NFL Big Data Bowl 2020](https://www.kaggle.com/competitions/nfl-big-data-bowl-2020/data), we investigate which factors most influence the number of yards gained during a rushing play.

### 🔍 Research Question

How do a player’s **speed**, **position on the field**, and **the number of defenders in the box** influence the outcome of a rushing play?

---

### 📊 Data Source

* **Dataset**: NFL Big Data Bowl 2020
* **Source**: [Kaggle](https://www.kaggle.com/competitions/nfl-big-data-bowl-2020/data)
* **Content**: Player movement, play outcomes, positions, speed, and more from the 2019 NFL regular season.

---

### ⚙️ Environment

* R version ≥ 4.0
* Required packages:

  * `tidyverse` only

---

### 📈 Key Findings

1. **Player Speed vs. Yards Gained**

   * Max speed shows only a **weak positive correlation** with rushing success.
   * Speed alone does **not strongly predict** outcomes.

2. **Player Position Impact**

   * **Running backs (RBs)** are the most consistent rushers.
   * **Cornerbacks (CBs)** often gain high yardage during rare plays like interception returns.
   * **Wide receivers (WRs)** show high variability, suggesting value in specific play designs.

3. **Defensive Alignment (Defenders in the Box)**

   * Strong **inverse relationship** between defenders in the box and yards gained.
   * Plays against 3–4 defenders yield **10+ yards**, while 9+ defenders reduce gains to **under 3.6 yards**.

---

### 📂 File Description

* `nfl_rushing_analysis.Rmd`: R Markdown file containing the full analysis, including:

  * Data cleaning
  * Visualizations
  * Interpretations
  * Final conclusions

---

### ✅ Conclusion

This project highlights that **rushing success is multi-dimensional**. While player speed is a factor, it's the **combination of position, play context, and defensive setup** that truly drives performance. These insights can help NFL analysts design smarter offensive strategies tailored to player strengths and defensive weaknesses.


