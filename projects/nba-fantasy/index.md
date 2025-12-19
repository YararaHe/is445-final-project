---
layout: default
title: "🏀 NBA Fantasy Points Across Eras: A Data-Driven Public Visualization"
author: "Yiran He"
---

**Author:** Yiran He  
**Group members:** Yiran He (Individual submission)

---

## Why Fantasy Points?
NBA fantasy points combine many box-score stats (points, rebounds, assists, steals, blocks, etc.) into one number. For public readers, that’s useful because it turns “overall impact” into a single score that is easier to compare across players and seasons.

In this project, I use player regular-season data from **1996–97 to 2022–23** to explore how fantasy production changed across eras—and what factors (like age) relate to higher fantasy impact. The goal is to make trends readable for non-experts while keeping the visuals interactive and transparent.

---

## ⭐ Central Interactive Visualization: Average Fantasy Points by Season
This main interactive chart shows how **average NBA fantasy points per season** change over time. Hover to see the season value and look for long-term shifts across eras.

<div style="margin: 14px 0 24px 0;">
  <iframe src="main_fantasy_trend.html" width="900" height="560" style="border:none;"></iframe>
</div>

**What to notice:** Modern seasons tend to show higher fantasy production. This is consistent with well-known NBA changes like increased pace, spacing, and high-usage offensive stars.

---

## Context Visualization 1: Fantasy Points vs Age
A common fan question is: **what age is a player’s “prime”?** This chart looks at the relationship between player age and fantasy points (sampled for smooth loading).

<div style="margin: 14px 0 24px 0;">
  <iframe src="fantasy_by_age.html" width="900" height="560" style="border:none;"></iframe>
</div>

**Interpretation:** Many high-output seasons cluster in the mid-to-late 20s, while younger seasons often show more variance as players develop and roles change.

---

## Context Visualization 2: Top Fantasy Performances (Single Season)
To connect the big-picture trend to real examples, this visualization highlights some of the most dominant fantasy seasons in the dataset.

<div style="margin: 14px 0 24px 0;">
  <iframe src="top_fantasy_players.html" width="900" height="560" style="border:none;"></iframe>
</div>

These “peak seasons” provide concrete anchors for what “high fantasy production” looks like in practice.

---

## Data & Methods (Beginner-friendly)
- **Dataset file in this repo:** `player_stats_scoring_rs.csv` (player-season regular season stats, 1996–2023)  
- **Unit of analysis:** one row = **one player in one season**
- **Key fields used here:**
  - `SEASON` (season label)
  - `AGE`
  - `NBA_FANTASY_PTS` (fantasy metric)

All visualizations were created in Python using **Pandas + Altair**, exported as standalone HTML files, and embedded into this GitHub Pages article.

---

## Sources & Citations
- **Primary dataset:** (PASTE YOUR EXACT DATASET SOURCE LINK HERE — Kaggle / GitHub repo / class-provided link)  
- **Additional context:** NBA era trends (pace/spacing/3-point growth) are discussed as general league-wide patterns.

---

## Notebook Links
- **Analysis / visualization notebook:** (UPLOAD your `.ipynb` into this repo, then paste its GitHub link here)

---

## Conclusion
Fantasy points offer a simple way to compare “overall box-score impact” across time. By combining one central interactive trend with two contextual views (age relationship and top seasons), this article provides a public-friendly view of how fantasy production evolves across NBA



