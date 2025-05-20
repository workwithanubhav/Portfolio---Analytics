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
| a. Most-used platforms | ![Platform Distribution](outputs/platform_distribution.png) |
| b. Dominance of content types | ![Content Type Frequency](outputs/content_type_distribution.png) |
| c. Top regions for viral content | ![Region Count](outputs/top_regions_distribution.png) |
| d. Most common viral hashtags | ![Top Hashtags](outputs/top_hashtags_barplot.png) |
| e. Engagement label distribution | ![Engagement Level Distribution](outputs/engagement_level_distribution.png) |

### 🔸 Numerical Variables

| Analysis Goal | Output |
|---------------|--------|
| a. Distribution and outliers | ![Views Distribution](outputs/engagement_metrics_histograms.png) |
| b. Central tendency and spread | ![Stat Summary](outputs/metric_distribution_kde.png) |
| c. Total interaction volume | ![Total Engagement Distribution](outputs/total_engagement_distribution.png) |
| d. Engagement per view (Efficiency) | ![Engagement Rate Histogram](outputs/engagement_rate_distribution.png) |
| e. Hashtag length distribution | ![Hashtag Lengths](outputs/hashtag_length_distribution.png) |

---

## 🔁 2. Bivariate Analysis

### 🔸 Categorical vs Categorical

| Analysis Goal | Output |
|---------------|--------|
| a. Platform vs Engagement Level | ![Platform × Engagement](outputs/platform_vs_engagement_level.png) |
| b. Format vs Engagement Level | ![Format × Engagement](outputs/content_type_vs_engagement_level.png) |
| c. Region vs Engagement Level | ![Region × Engagement](outputs/region_engagement.png) |
| d. Hashtag vs Engagement | ![Hashtag × Engagement](outputs/hashtag_engagement.png) |
| e. Hashtag length category vs Engagement | ![Short vs Long Hashtag](outputs/region_vs_engagement_level.png) |

### 🔸 Categorical vs Numerical

| Analysis Goal | Output |
|---------------|--------|
| a. Platform vs Total Engagement | ![Platform vs Total Interaction](outputs/platform_vs_total_engagement.png) |
| b. Format efficiency per view | ![Format Efficiency](outputs/content_type_vs_engagement_rate.png) |
| c. Metrics across Engagement Classes | ![Metric Comparison](outputs/content_type_violin_engagement_rate.png) |

### 🔸 Numerical vs Numerical

| Analysis Goal | Output |
|---------------|--------|
| a. Views vs Likes/Shares | ![Views vs Likes](outputs/views_vs_shares.png) |
| b. Interaction Strength | ![Views vs Total Engagement](outputs/interaction_correlation_heatmap.png) |
| c. Efficient content (low views, high interaction) | ![Efficient Posts](outputs/efficient_content_scatter.png) |
| d. Engagement Rate vs Comments | ![Rate vs Comments](outputs/engagement_rate_vs_comments.png) |

---

## 🔄 3. Multivariate Analysis

| Analysis Goal | Output |
|---------------|--------|
| a. Format × Platform for virality | ![Format × Platform](outputs/platform_format_virality.png) |
| b. Format performance by region | ![Format × Region](outputs/region_content_type_heatmap.png) |
| c. Hashtag trends by platform | ![Platform Hashtag Trend](outputs/platform_hashtag_high_engagement_heatmap.png) |
| d. Content types across engagement levels | ![Content × Engagement Levels](outputs/content_type_engagement_levels.png) |
| e. Efficiency mapping (ER per view) | ![Efficiency Grid](outputs/region_post_efficiency.png) |
| f. Cluster patterns (views, likes, shares, comments) | ![Cluster Heatmap](outputs/engagement_clusters_pairplot.png) |
| g. Feature importance or predictors | ![Feature Importance](outputs/feature_importance.png) |
| h. Region vs Platform engagement | ![Region × Platform](outputs/platform_dominance_by_region.png) |
| i. Format vs Hashtag Length | ![Hashtag Length × Format](outputs/format_hashtag_efficiency_heatmap.png) |
| j. Reels performance by region | ![Reels × Region](outputs/reel_efficiency_by_region.png) |
| k. Can shares boost low-view posts? | ![Shares vs Views](outputs/shares_vs_views_by_engagement.png) |

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
🔗 LinkedIn: [linkedin.com/in/contactanubhavsingh]([https://www.linkedin.com/in/your-linkedin-username](https://www.linkedin.com/in/contactanubhavsingh/))


---

