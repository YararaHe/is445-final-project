# 🏀 NBA Fantasy Points Across Eras: A Data-Driven Public Visualization  
**Author: Yara He**  
**Group members: Yara He (Individual submission)**

---

## Why Fantasy Points?
NBA fantasy points combine many box-score stats (points, rebounds, assists, steals, blocks, etc.) into one number.  
For public readers, this is useful because it turns “overall impact” into a single score that is easier to compare across players and seasons.

In this project, I use player regular-season data from **1996–97 to 2022–23** to explore how fantasy production changed across eras, and what factors (like age) relate to higher fantasy impact.

---

## ⭐ Central Interactive Visualization: Average Fantasy Points by Season
This main interactive chart shows how **average NBA fantasy points per season** change over time.  
You can hover over each season to see the exact values and observe long-term trends.

<iframe src="main_fantasy_trend.html" width="820" height="520" style="border:none;"></iframe>

**What to notice:** In modern seasons, fantasy production tends to be higher. This aligns with changes in league pace, spacing, and star usage.

---

## Context Visualization 1: Fantasy Points vs Age
A common question for fans is: **what age is a player’s “prime”?**  
This plot shows the relationship between player age and fantasy points.

<iframe src="fantasy_by_age.html" width="820" height="520" style="border:none;"></iframe>

**Interpretation:** Most players cluster around higher output in their mid-to-late 20s, while younger players show larger variance and older players often decline.

---

## Context Visualization 2: Top Fantasy Performances (Single Season)
To anchor the trend with real examples, this chart highlights some of the highest fantasy seasons in the dataset.

<iframe src="top_fantasy_players.html" width="820" height="520" style="border:none;"></iframe>

This helps readers connect “era trend” to actual star seasons.

---

## Data & Methods (Beginner-friendly)
- **Dataset:** `player_stats_scoring_rs.csv` (player-season regular season stats, 1996–2023)  
- Each row represents **one player in one season**.
- Key columns used:
  - `SEASON` (season label)
  - `AGE`
  - `NBA_FANTASY_PTS` (fantasy metric)

All visualizations were created in Python using **Pandas + Altair**, exported as HTML, and embedded into this GitHub Pages article.

---

## Sources & Citations
- **Primary dataset:** NBA player statistics dataset (1996–2023).  
  (Put your exact dataset source link here — Kaggle / GitHub repo / class-provided source)
- **NBA context references:** General NBA historical context (pace, three-point era) based on widely known league trends.

---

## Notebook Links
- Analysis notebook (Part 2 / Part 3 development):  
  - Link: (upload your `.ipynb` to this repo, then paste the GitHub link here)

---

## Conclusion
Fantasy points provide a simple way to compare player impact across time.  
By combining an interactive season trend with contextual views (age relationship and top seasons), this article shows how both the NBA and player careers have evolved across eras.


