# Portfolio---Analytics

# 🔍 Virality Analysis of Social Media Posts

This project explores what drives **virality** across platforms like **TikTok, Instagram, YouTube, and Twitter (X)** using a dataset of **5,000 viral posts**.

Through exploratory data analysis (EDA), I examined platform trends, content format performance, hashtag strategies, and audience engagement behavior.

📁 This repository contains:
- `virality_analysis.ipynb` – the complete Jupyter Notebook with code and visualizations
- 📊 A detailed breakdown of **univariate**, **bivariate**, and **multivariate analysis**
- 🔎 Insights that help decode what makes content go viral

---

## 📌 Dataset Overview

- **Source:** Kaggle  
- **Posts Analyzed:** 5,000 viral posts  
- **Platforms:** TikTok, Instagram, Twitter, YouTube  
- **Fields:** Platform, Content_Type, Region, Views, Likes, Shares, Comments, Hashtags, Engagement_Level

---

## 🧮 1. Univariate Analysis

### 🔸 Categorical Variables

| Analysis Goal | Output |
|---------------|--------|
| a. Most-used platforms | ![Platform Distribution](platform_distribution.png) |
| b. Dominance of content types | ![Content Type Frequency](content_type_distribution.png) |
| c. Top regions for viral content | ![Region Count](top_regions_distribution.png) |
| d. Most common viral hashtags | ![Top Hashtags](top_hashtags_barplot.png) |
| e. Engagement label distribution | ![Engagement Level Distribution](engagement_level_distribution.png) |

### 🔸 Numerical Variables

| Analysis Goal | Output |
|---------------|--------|
| a. Distribution and outliers | ![Views Distribution](engagement_metrics_histograms.png) |
| b. Central tendency and spread | ![Stat Summary](metric_distribution_kde.png) |
| c. Total interaction volume | ![Total Engagement Distribution](total_engagement_distribution.png) |
| d. Engagement per view (Efficiency) | ![Engagement Rate Histogram](engagement_rate_distribution.png) |
| e. Hashtag length distribution | ![Hashtag Lengths](hashtag_length_distribution.png) |

---

## 🔁 2. Bivariate Analysis

### 🔸 Categorical vs Categorical

| Analysis Goal | Output |
|---------------|--------|
| a. Platform vs Engagement Level | ![Platform × Engagement](platform_vs_engagement_level.png) |
| b. Format vs Engagement Level | ![Format × Engagement](content_type_vs_engagement_level.png) |
| c. Region vs Engagement Level | ![Region × Engagement](region_engagement.png) |
| d. Hashtag vs Engagement | ![Hashtag × Engagement](hashtag_engagement.png) |
| e. Hashtag length category vs Engagement | ![Short vs Long Hashtag](region_vs_engagement_level.png) |

### 🔸 Categorical vs Numerical

| Analysis Goal | Output |
|---------------|--------|
| a. Platform vs Total Engagement | ![Platform vs Total Interaction](platform_vs_total_engagement.png) |
| b. Format efficiency per view | ![Format Efficiency](content_type_vs_engagement_rate.png) |
| c. Metrics across Engagement Classes | ![Metric Comparison](content_type_violin_engagement_rate.png) |

### 🔸 Numerical vs Numerical

| Analysis Goal | Output |
|---------------|--------|
| a. Views vs Likes/Shares | ![Views vs Likes](views_vs_shares.png) |
| b. Interaction Strength | ![Views vs Total Engagement](interaction_correlation_heatmap.png) |
| c. Efficient content (low views, high interaction) | ![Efficient Posts](efficient_content_scatter.png) |
| d. Engagement Rate vs Comments | ![Rate vs Comments](engagement_rate_vs_comments.png) |

---

## 🔄 3. Multivariate Analysis

| Analysis Goal | Output |
|---------------|--------|
| a. Format × Platform for virality | ![Format × Platform](platform_format_virality.png) |
| b. Format performance by region | ![Format × Region](region_content_type_heatmap.png) |
| c. Hashtag trends by platform | ![Platform Hashtag Trend](platform_hashtag_high_engagement_heatmap.png) |
| d. Content types across engagement levels | ![Content × Engagement Levels](content_type_engagement_levels.png) |
| e. Efficiency mapping (ER per view) | ![Efficiency Grid](region_post_efficiency.png) |
| f. Cluster patterns (views, likes, shares, comments) | ![Cluster Heatmap](engagement_clusters_pairplot.png) |
| g. Feature importance or predictors | ![Feature Importance](feature_importance.png) |
| h. Region vs Platform engagement | ![Region × Platform](platform_dominance_by_region.png) |
| i. Format vs Hashtag Length | ![Hashtag Length × Format](format_hashtag_efficiency_heatmap.png) |
| j. Reels performance by region | ![Reels × Region](reel_efficiency_by_region.png) |
| k. Can shares boost low-view posts? | ![Shares vs Views](shares_vs_views_by_engagement.png) |

---

## 💡 Key Takeaways

> - Platform–format fit is essential for virality  
> - Efficient content = high interaction per view  
> - Hashtag strategy and region-specific trends matter  
> - Engagement Rate is more meaningful than raw views

---

## 📦 Tools & Libraries Used

- Python, Jupyter Notebook, Figma, Kaggle  
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `scikit-learn`

---

## 🙌 About Me

I'm a 2nd-year MBA student at **BIM Trichy**, exploring data analytics, storytelling, and digital strategy — one project at a time.

🔗 LinkedIn: [linkedin.com/in/contactanubhavsingh](https://www.linkedin.com/in/contactanubhavsingh)

---
