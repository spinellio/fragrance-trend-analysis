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
│   ├── GT_Notes_Merged_Monthly.csv                # Google Trends Notes Data
│   ├── GT_Categories_Merged_Monthly.csv           # Google Trends Categories Data
│   ├── Fragrantica_Cleaned.csv                    # Cleaned + Structured Data (ready for analysis)
│   ├── Fragrance_Notes_Master.csv                 # Notes Calculations (ready for analysis)
│   ├── Fragrance_Categories_Master.csv            # Categories Calculations (ready for analysis)
│
├── script/
│   ├── Fragrance_Full_R_Scrip.txt     # Full R script
│
├── visuals/
│   ├── Fragrance_Categories_Visuals_&_Dashboards.twb           # Tableau charts & Dashboard for Categories
│   ├── Fragrance_Notes_Visuals_&_Dashboards.twb                # Tableau charts & Dashboard for Notes
│   ├── Fragrance_Notes_Categories_Visuals_&_Dashboards.twb     # Tableau charts & Dashboard for Notes by Category
│
├── report/    # Final written report  
│   ├── Fragrance_Opportunity_Insights_Case_Study_Report.pdf     # Final Written Report
│   ├── Fragrance_Opportunity_Insights_Deck.pptx                 # Final Presentation Slides
├── README.md  
 ``` 

---
## 📈 Key Insights
**Biggest whitespace:** rediscovering underused notes while reinventing classics.  

- **Green & Rediscovery Opportunity:** *Leather, Amber, Oakmoss, Moss* are highly underused yet show strong consumer pull → whitespace for distinctive launches.
- **High-Growth US Disruptors:** *Saffron, Peach, Oud, Ginger, Lavender* lead US momentum → bold experimentation and trend-driven launches.
- **UK Heritage Anchors:** *Rose, Vanilla, Musk, Pear, Apple* dominate → innovation best introduced through limited editions and familiar blends.  
- **Dual-Market Anchors:** *Vanilla, Rose, Jasmine, Woody* remain stable across both regions → require modern reinvention to avoid saturation.  
- **Cross-Market Dynamic:** US = faster adoption of experimental notes; UK = heritage stability → **green revival acts as a shared growth bridge.**

---
## 📦 Deliverables

This case study includes both a full written report and a visual presentation deck. These deliverables summarize the project’s methodology, findings, and strategic recommendations.

- [📄 **Case Study Report — Fragrance Opportunities Insights (PDF)**](report/Fragrance_Opportunity_Insights_Case_Report.pdf)  
  A comprehensive report outlining the data sources, methodology (including Opportunity Score and Buzz Score calculations), key insights, and market strategy recommendations.

- [📊 **Fragrance Opportunities Insights Report (PPTX)**](report/Fragrance_Opportunitiy_Insights_Deck.pptx)  
  A visual summary presentation featuring Tableau dashboards, trend heatmaps, note/category opportunity matrices, and cross-market comparisons for stakeholders.

You can find both files in the root directory of this repository.

---
## 📌 How to Use This Repo  
1. Explore `/data/` for final datasets  
2. Review `/script/` for R-based cleaning & merging workflows  
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
