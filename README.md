# Fragrance Trend Analysis  

**Portfolio Case Study – Data Analytics & Market Insights**

This project analyzes **fragrance categories and notes** across the **US & UK** to identify whitespace opportunities for product innovation. Using Google Trends, TikTok, Instagram, and Fragrantica data, I created a combined **Opportunity Score** to highlight **high-interest, rising, and underused** fragrance spaces. I also developed a **Buzz Score** based on Instagram and TikTok hashtag volumes, a **Weighted Buzz Score** (prioritizing TikTok's influence), and a **Trend Momentum Score** to capture growth velocity across time and platforms.

The report is designed to demonstrate **end-to-end insight analysis**, from raw data collection to visualization and strategic recommendations.

---

## 🚀 Objectives  
- Identify **fragrance categories and notes** with the highest potential for **innovation and market growth**.  
- Pinpoint **emerging opportunities** where consumer demand is high but current product supply is low.  
- Compare adoption patterns between **US vs UK markets** to guide global brand strategy.  
- Showcase **data analytics skills** across R, Tableau, and insight storytelling.  

---

## 🛠️ Tools & Skills Demonstrated  
- **R** (`tidyverse`, `lubridate`, `stringr`, `janitor`) → Data cleaning, CSV merging, feature engineering  
- **Data Structuring** → Merged 120+ Google Trends files, structured Kaggle + social media datasets  
- **Custom Metrics** → Built **Opportunity Score** (Weighted Demand Signal ÷ Median Supply), **Buzz Score**, **Weighted Buzz Score** (TikTok-prioritized), and **Trend Momentum Score** (to quantify rate of trend growth)  
- **Tableau** → Dashboards: growth heatmaps, share vs. growth, emerging notes, cross-market insights  
- **Insight Storytelling** → Translated raw data into **actionable business recommendations**

---

## 📊 Data Sources  
- **Google Trends** – Weekly search interest for fragrance notes & categories (US + UK)  
- **TikTok & Instagram** – Hashtag volumes (manually collected)  
- **Fragrantica Dataset** – Public dataset via Kaggle, cleaned for category/note mapping  

📌 *Note: Raw datasets have been cleaned and anonymized for clarity. Sample inputs are included in `/data/raw/`, with full processed data in `/data/processed/`.*

### Data Attribution
This project uses the [Fragrantica.com Fragrance Dataset](https://www.kaggle.com/datasets/olgagmiufana1/fragrantica-com-fragrance-dataset) available under the **CC BY-NC-SA 4.0** license.  
Derived datasets in the `/data/processed/` folder are shared under the same license terms (**CC BY-NC-SA 4.0**).

---

## 📂 Repository Structure  
```text
fragrance-trend-analysis/
│
├── data/
│   ├── raw/                  # Sample raw files (Google Trends, TikTok, Kaggle)
│   ├── processed/            # Cleaned + structured data (ready for analysis)
│
├── scripts/
│   ├── merge_notes_GT.R      # Merge note-level trend files
│   ├── merge_cats_GT.R       # Merge category-level trend files
│   ├── data_cleaning.R       # Full cleaning & tagging pipeline
│
├── visuals/
│   ├── categories/           # Tableau charts: growth, opportunity, share vs. growth
│   ├── notes/                # Emerging & underused note analysis
│   ├── crossmarket/          # US vs. UK divergence dashboards
│
├── Fragrance_Insights_Report.pdf    # Final written report  
├── Fragrance_Trend_Deck.pptx        # Final presentation slides  
├── README.md  
└── LICENSE
 ``` 

---
## 📈 Key Insights  

 **Green**, **Amber**, and **Gourmand** categories are the most under-leveraged but fast-rising segments.  
- **Peach**, **Saffron**, **Apple**, **Lavender**, and **Ginger** show high trend momentum with low market saturation.  
- **Vanilla**, **Rose**, and **Oud** dominate but risk oversaturation — brands need modern takes or fresh blends.  
- **US** consumers are faster to adopt bold, experimental notes, while the **UK** market favors tradition.  
- A **"Green Revival"** strategy offers a rare shared opportunity across both regions.

---
## 📦 Deliverables

This case study includes both a full written report and a visual presentation deck. These deliverables summarize the project’s methodology, findings, and strategic recommendations.

- 📄 **Fragrance_Insights_Report.pdf**  
  A comprehensive report outlining the data sources, methodology (including Opportunity Score and Buzz Score calculations), key insights, and market strategy recommendations.

- 📊 **Fragrance_Trend_Deck.pptx**  
  A visual summary presentation featuring Tableau dashboards, trend heatmaps, note/category opportunity matrices, and cross-market comparisons for stakeholders.

You can find both files in the root directory of this repository.

---
## 📌 How to Use This Repo  
1. Explore `/data/processed/` for final datasets  
2. Review `/scripts/` for R-based cleaning & merging workflows  
3. Browse `/visuals/` for Tableau chart outputs  
4. Read the full report and deck in the root directory for full insights & strategy  

---

## 📖 Portfolio Use  
This case study is part of my **Insight Analyst Portfolio**, built to highlight:

- Real-world data wrangling and integration  
- Custom metric building for whitespace analysis  
- Visual storytelling in Tableau  
- Strategic thinking applied to the luxury beauty industry  

---

## 📜 License  

This project is provided without a formal license. Educational and personal use is permitted with attribution. **Commercial use is not allowed.**

---

## 📬 Contact  

**Olivia Spinelli**  
📍 Paris, France  
[LinkedIn](https://www.linkedin.com/in/olivia-spinelli) | [Email](mailto:spinellio19@gmail.com)

---
