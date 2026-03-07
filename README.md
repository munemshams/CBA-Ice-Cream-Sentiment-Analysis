# CBA Ice Cream Sentiment Analysis Project

This project analyzes the relationship between **customer sentiment, product performance, and operational factors** within an ice cream company called **Cross Bridge Assuming Ice Cream** using R Studio.

The analysis combines **sales data and customer feedback** to identify which flavors customers prefer, which products underperform, and how sentiment varies across different customer locations and production sites.

The goal of the project is to generate **data-driven insights** that support decision-making for marketing, management, and production teams.

---

# Project Overview

Customer reviews and product performance metrics provide valuable insight into consumer preferences. This project applies **text mining and sentiment analysis techniques** to customer feedback in order to better understand how product perception relates to sales outcomes.

The analysis focuses on:

• Sales performance across ice cream flavors  
• Customer sentiment extracted from product reviews  
• Word frequency and sentiment patterns in feedback  
• Relationships between sentiment and product performance  

By combining these analyses, the project identifies opportunities for **product improvement, marketing strategies, and operational decisions**.

---

# Dataset

The dataset used in this project is stored in an R data file.

| File | Description |
|-----|-------------|
| productsalescomments.RDS | Dataset containing product sales and customer comment data |

This dataset includes customer feedback that can be analyzed to determine sentiment patterns and word usage across product reviews.

---

# Project Workflow

The project follows a structured **text analytics and sentiment analysis workflow**.

## 1. Data Loading

The dataset is loaded from the RDS file and prepared for analysis within R Studio.

The data contains information about:

• Ice cream flavors  
• Customer feedback comments  
• Product performance data  

---

## 2. Sales Analysis

Sales data is analyzed to identify:

• Top-performing flavors  
• Underperforming products  

This helps determine which products contribute most to revenue and which may require improvement.

---

## 3. Sentiment Analysis

Customer comments are analyzed using the **AFINN sentiment lexicon** to assign sentiment scores to each review.

Sentiment scores help determine whether customer feedback is generally:

• Positive  
• Neutral  
• Negative  

---

## 4. Word Frequency Analysis

Text mining techniques are used to identify commonly used words in customer feedback.

This helps highlight:

• Common product strengths mentioned by customers  
• Recurring complaints or negative feedback  

---

## 5. Word Network Analysis

Bigram analysis is used to examine relationships between words appearing together in customer comments.

Word networks help reveal patterns such as:

• Flavor-related descriptors  
• Product quality discussions  
• Customer experience themes  

---

## 6. Sentiment Patterns Across Locations

Sentiment scores are analyzed by:

• Customer locations  
• Parlor sites  
• Production facilities  

This allows the company to understand how customer perception varies across different operational areas.

---

# Visualizations

The project generates multiple visual outputs to support the analysis.

Examples include:

• Word frequency charts  
• Sentiment distribution plots  
• Bigram network diagrams  
• Sales performance visualizations  

All generated visuals are stored in the folder:

Generated visuals

---

# Files Included

| File | Description |
|-----|-------------|
| README.md | Project documentation |
| final_productsentiment.Rmd | Full R Markdown analysis |
| final_productsentiment.docx | Knitted Word report |
| final_productsentiment.html | Knitted HTML report |
| productsalescomments.RDS | Dataset used for the analysis |
| My Analysis.docx | Written analysis summary |
| Presentation Slides Shams.pptx | Project presentation slides |
| Generated visuals | Folder containing all visualizations produced in the analysis |

---

# R Libraries Used

| Library | Purpose |
|-------|--------|
| tidytext | Text mining and sentiment analysis |
| ggplot2 | Data visualization |
| dplyr | Data manipulation and transformation |
| tidyr | Data reshaping |
| ggraph | Word network visualization |
| igraph | Graph structure for bigram networks |

---
