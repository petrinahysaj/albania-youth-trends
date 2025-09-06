## Youth Emigration and NEET Trends in Albania (2016–2023)

This project analyzes the socio-economic situation of Albanian youth between **2016 and 2023**.  
The focus is on **NEET rates** (Not in Employment, Education, or Training), **youth emigration**, **higher education enrollment**, **population structure**, **wages**, and **asylum applications**.  
The goal is to understand how these factors interact and what story they tell about the challenges young people face in Albania.

## Project Structure

- `data/`
  - `albania_youth_data.csv` → raw dataset  
  - `cleaned_albania_youth_data.csv` → cleaned dataset  
  - `images/`
     - Saved charts and figures for the README  

- `notebooks/`
  - `data_cleaning.ipynb` → loads and cleans raw data  
  - `exploratory_analysis.ipynb` → descriptive analysis, correlations, trends  
  - `visualizations.ipynb` → visual storytelling with plots  


## Research Questions

- How has the **NEET rate** evolved from 2016 to 2023?  
- Is there a relationship between **wages** and **emigration of young people**?  
- Does higher **tertiary enrollment** reduce NEET rates?  
- What role do **asylum applications abroad** play in explaining migration trends?  

## Tools & Libraries

- **Python 3**  
- **Pandas**, **NumPy** → data wrangling  
- **Matplotlib**, **Seaborn** → visualizations  
- **Jupyter Notebook** → analysis workflow  

## Key Insights

- The **NEET rate** has been decreasing, but remains high compared to EU averages.  
- **Youth emigration** is persistent, even as wages rise.  
- **Education enrollment rates** are increasing, yet not fully offsetting job market challenges.  
- **Asylum applications** correlate with broader migration trends.  


## Example Visuals

- Line chart: NEET rate over time
  <img width="800" height="500" alt="neet_rate_trend" src="https://github.com/user-attachments/assets/79251a4b-176e-4935-9d50-ea9f803547d1" />
  
- Bar chart: Youth emigrants per year
  <img width="800" height="500" alt="emigration_per_year" src="https://github.com/user-attachments/assets/5c377fed-203b-4783-a972-66500787d72e" />

- Correlation heatmap of socio-economic indicators
  <img width="800" height="500" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/159683ab-4ce9-4328-afc2-1ac094fede7a" />

- Dual-axis plot: Wages vs Emigration
  <img width="800" height="500" alt="emigration_vs_wage" src="https://github.com/user-attachments/assets/43049cea-80fd-40c2-ab45-910ee9a1350a" />
  
## Data Source


The dataset is compiled from **INSTAT (Albanian Institute of Statistics)** and other official publications.  
Values cover the period **2016–2023** and include indicators on youth emigration, NEET rate, education enrollment, wages, and asylum applications.

## How to Run

Clone the repo and install requirements:

```bash
git clone https://github.com/yourusername/albania-youth-trends.git
cd albania-youth-trends
pip install -r requirements.txt
