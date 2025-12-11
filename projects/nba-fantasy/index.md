---
layout: default
title: "NBA Fantasy Points Across Eras: A Data-Driven Story (1996–2023)"
author: "By Yara He"
---

# 🏀 NBA Fantasy Points Across Eras  
### *By Yara He*

Over the past 27 NBA seasons — from 1996–97 through 2022–23 — the league has transformed dramatically.  
The pace increased. Three-pointers exploded. Stars took on heavier offensive responsibilities.  

Using a dataset of **over 15,000 player-seasons** and **43 statistical features**, this article explores how NBA players produced fantasy impact across time, which ages contribute the most fantasy value, and which players dominated entire eras.

The analysis is based on the dataset `player_stats_scoring_rs`, which includes variables such as:

- **AGE**, **GP (games played)**  
- **PTS, AST, REB, STL, BLK**  
- **EFF%, various opponent ranking metrics**  
- **NBA_FANTASY_PTS**  
- **SEASON** (e.g., 1996-97)

This page presents three visualizations to help readers easily understand the trends and key insights.

---

# 📈 Interactive Visualization 1: Career Fantasy Trends  
*Explore how any player's fantasy production evolves across their career.*

👉 **(嵌入你的互动 Altair 图)**  




This visualization allows the reader to examine the fantasy production arc of any player between 1996 and 2023.

### 🧐 What the data shows  
- Fantasy production typically **peaks between ages 25–30**.  
- Younger players (19–22) show high variance — many are rookies or bench players but some explode early.  
- Older players tend to decline due to reduced minutes, injuries, or changing team roles.

By combining stats such as PTS, REB, AST, STL, BLK, and efficiency metrics from the dataset, the NBA Fantasy Points value gives us a comprehensive indicator of a player’s overall on-court impact.

---

# 📊 Visualization 2: Fantasy Points by Age  
*How does age influence fantasy performance?*

👉 **(嵌入你的年龄分布图位置)**  




### 📝 Insight  
Using the **AGE** column from the dataset, this visualization highlights clear patterns:

- Ages **26–28** are the strongest fantasy years on average.  
- Young players (<22) vary widely — some have breakout seasons, others limited roles.  
- After age 32, fantasy value gradually declines as athleticism and minutes dip.

This mirrors known NBA performance curves, but the fantasy perspective makes the shift even more obvious.

---

# 🏆 Visualization 3: Top Fantasy Players by Season  
*Which players defined each era?*

👉 **(嵌入你的 Top 10 图)**  




### ✨ Highlights from 1996–2023  
- **Late 90s / early 2000s:** dominated by Kevin Garnett, Shaquille O'Neal, and Tim Duncan.  
- **2010s:** LeBron James, James Harden, Russell Westbrook, and Stephen Curry consistently produced elite numbers.  
- **2020s:** Nikola Jokić, Giannis Antetokounmpo, and Luka Dončić lead the modern era with massive usage rates and all-around stat production.

The dataset's **NBA_FANTASY_PTS** column reveals entire eras of dominance.

---

# 📘 Understanding the Dataset

The CSV file used for this project (`player_stats_scoring_rs`) contains **43 different variables** for each player-season:

### 🔍 Player Information  
- PLAYER_ID  
- PLAYER_NAME  
- TEAM_ABBREVIATION  
- AGE  

### 📊 Performance Statistics  
- PTS, AST, REB, STL, BLK  
- FG%, FT%, 3P%  

### 🛡 Advanced Opponent Metrics  
- OPP_PTS_OFF_TOV_RANK  
- OPP_PTS_FB_RANK  
- OPP_PTS_PAINT_RANK  
- BLK_RANK, PF_RANK, etc.

### ⭐ Fantasy Impact  
- **NBA_FANTASY_PTS**  
- **NBA_FANTASY_PTS_RANK**

### 📅 Season  
- SEASON (e.g., “1996-97”)  

This dataset supports both career-level analysis and cross-season comparisons.

---

# 🧩 Connecting the Trends

### **1. The league evolved — and fantasy totals evolved with it.**  
More spacing and faster pace in the 2010s–2020s led to higher elite fantasy scores.

### **2. Fantasy peaks align with athletic prime.**  
Ages 25–30 remain the strongest producers across 27 seasons of data.

### **3. Stars dominate eras more now than before.**  
Usage rates today lead to more “heliocentric” stat lines, boosting fantasy value.

---

# 🔗 Project Files & Citations

### 📄 Jupyter Notebooks  
- Part 1 Notebook: *(Add your notebook link here)*  
- Part 2 Notebook: *(Add your notebook link here)*  

### 📊 Dataset Source  
This dataset comes from the "NBA Statistics Repository for teams and players 1996–2023" dataset.

### 🌐 GitHub Pages  
This article is hosted at:  
`https://yararahe.github.io/projects/nba-fantasy/`

---

# 🙌 Thank You for Reading!

This interactive article was created for IS445 Final Project Part 3, combining public-facing storytelling with exploratory data visualizations.

Feel free to explore the interactive charts above and dive into 27 seasons of NBA data!
