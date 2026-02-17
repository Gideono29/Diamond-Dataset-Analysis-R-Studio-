# Diamond Dataset Analysis (R Studio)
## Project Overview

This project analyzes the Diamonds Dataset in RStudio to investigate how physical attributes—particularly carat weight and cut quality—influence diamond pricing. Through exploratory data analysis (EDA), statistical summaries, and ggplot2 visualization, the study identifies key value drivers and distribution patterns in the diamond market.

The analysis demonstrates how R can be used to uncover pricing relationships and support data-driven valuation in retail or luxury goods analytics.
<img width="774" height="265" alt="Screenshot 2026-02-16 150650" src="https://github.com/user-attachments/assets/1862c5bf-3694-46b9-93a8-95f977c86105" />
<img width="975" height="635" alt="Screenshot 2026-02-16 145049" src="https://github.com/user-attachments/assets/e3d89f11-6041-4d77-b28e-6a0766840843" />
<img width="971" height="632" alt="Screenshot 2026-02-16 145324" src="https://github.com/user-attachments/assets/155745eb-12d8-425d-b269-6b923d0244f1" />
<img width="990" height="630" alt="Screenshot 2026-02-16 150632" src="https://github.com/user-attachments/assets/29f8e222-8dbc-46a3-8e66-3fbad4d92128" />

## Key Analytical Questions
- How does carat weight affect diamond price?
- What is the distribution of diamond sizes in the dataset?
- Which cut quality appears most frequently?
- Are price and carat normally distributed or skewed?
- Is there a clear relationship between size and value?
- What summary statistics best represent a “typical” diamond?

## Analytical Methods (Performed in R Studio)
- The analysis was conducted using:
- ggplot2 → Data visualization
- summary(), mean(), median() → Descriptive statistics
- Histogram → Distribution of carat
- Bar chart → Frequency of cut categories
- Scatterplot → Relationship between carat and price

# Key Findings
## 1. Ideal Cut Diamonds Dominate the Dataset

The bar chart shows:
- Ideal cut diamonds are the most common, followed by Premium and Very Good.
- Fair and Good cuts occur much less frequently.

## 2. Carat Distribution Is Right-Skewed
Histogram results show:
- Most diamonds fall between 0.3–1.2 carats.
- Large diamonds are rare.
Statistics:
- Mean carat = 0.80
- Median carat = 0.70

Since mean > median → positive skew.

## 3. Strong Positive Relationship Between Carat and Price
The scatterplot reveals:
- Price rises sharply as carat increases.
- The relationship is non-linear and widens for larger stones.

Interpretation:
Carat weight is the strongest determinant of price.

## 4. Price Distribution Is Highly Skewed
- Mean price = $3,932
- Median price = $2,401
- The difference indicates high-value outliers pulling the average upward.
Interpretation:
Luxury diamonds heavily influence pricing averages.
