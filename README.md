# Text Mining: Hotel Price Analysis During the Formula 1 Grand Prix  

This project studies how hotel prices in Barcelona change during the 2025 Formula 1 Spanish Grand Prix compared to a normal weekend, using Seville as a control city. It combines web scraping, text processing, and econometric analysis to measure the event’s impact on accommodation prices.

---

## Overview
- Scrapes hotel listings from Barcelona and Seville using Selenium.  
- Preprocesses hotel descriptions and visualizes results with WordClouds.  
- Applies a Difference-in-Differences (DiD) model to estimate the price effect of the event.  
- Incorporates text-based features (amenities, quality indicators) as additional controls.  

---

## Methodology
1. Web scraping of hotel data for two weekends per city.  
2. Text cleaning, tokenization, and stemming using NLTK.  
3. WordCloud generation before and after preprocessing.  
4. Econometric analysis using DiD with fixed effects for city and time.  
5. Additional model with text-derived hotel quality measures.  

---

## Tools
Language: Python  
Libraries: selenium, pandas, openpyxl, nltk, wordcloud, statsmodels  

---

## Repository Structure
| File | Description |
|------|--------------|
| Text_scraping.ipynb | Web scraping of hotel listings for both cities |
| Text_analysis.ipynb | Text preprocessing, WordClouds, and regression analysis |
| barcelona_16_18.xlsx | Barcelona hotels before the event |
| barcelona_30_01.xlsx | Barcelona hotels during the event |
| seville_16_18.xlsx | Seville hotels before the event |
| seville_30_01.xlsx | Seville hotels during the event |
| HW1_Report.pdf | Full report with results and interpretation |
| README.md | Project documentation |

---

