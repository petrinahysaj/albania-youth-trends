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

- `notebook/`
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

- **NEET rate (Not in Employment, Education, or Training)** declined from **30% in 2016** to **25% in 2023**.  
  → This indicates gradual improvement in youth integration into education or work, though the rate remains higher than EU averages.  

- **Youth emigration (ages 15–29)** decreased sharply from **27,790 in 2016** to **11,948 in 2023**.  
  → While fewer young Albanians are leaving, migration is still significant relative to the population size.  

- **Tertiary enrollment (absolute numbers)** fell slightly, from **141,410 in 2016** to **120,063 in 2023**.  
  → But the **enrollment rate (% of age group 18–24)** increased from **55% to 61%**, suggesting that even with a shrinking youth population, more young people are pursuing higher education.  

- **Youth population (20–24)** declined steadily from **256,899 in 2016** to **196,240 in 2023**.  
  → This demographic shrinkage reflects both lower birth rates and persistent emigration.  

- **Average gross monthly wages** increased consistently, from **47,522 ALL in 2016** to **70,539 ALL in 2023**.  
  → Despite wage growth, it has not been enough to fully deter emigration pressures.  

- **Asylum applications (ages 15–29, % of emigrants)** decreased from **30% in 2016** to **25% in 2023**.  
  → This suggests a shift from asylum-driven migration toward other types of mobility (e.g., work or study migration).  


### 🔎 Overall interpretation

Albania’s youth between 2016–2023 faced **contradictory trends**:  
- Education enrollment rates are rising, wages are increasing, and NEET rates are improving.  
- Yet the **youth population is shrinking**, and emigration, while declining, remains a persistent challenge.  

This points to **systemic demographic decline** where opportunities are improving inside the country, but migration remains a strong factor shaping the future of Albania’s young population.



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
git clone https://github.com/petrinahysaj/albania-youth-trends.git
cd albania-youth-trends
