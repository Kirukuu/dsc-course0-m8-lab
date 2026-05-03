# Aviation Accident Analysis


## Project Overview
Analysis of aviation accident data (1948–2023) to identify the safest aircraft makes 
and models for an airline insurer client. The analysis provides separate recommendations 
for small and large aircraft based on injury rates and destruction rates.

## Key Findings

### Recommended Makes
- **Small aircraft:** Aviat Aircraft Inc and Maule show the lowest injury fractions 
  and destruction rates among small aircraft makes.
- **Large aircraft:** Dehavilland, Cessna, Piper, and Grumman recorded 0% injury 
  fraction and 0% destruction rate. Among commercial manufacturers, 
  Bombardier Inc and Boeing offer the best safety profile.

### Recommended Models
- **Small aircraft:** Cessna 172SP, Diamond DA 20 C1, and Maule M-5-210C — all 
  recorded zero fatal or serious injuries across all incidents in the dataset.
- **Large aircraft:** Boeing 777 (mean injury fraction: 0.0008), Boeing 757 (0.001), 
  and Boeing 787 (0.003) are the top performing large aircraft models.

### Other Factors
- **Weather Condition:** IMC (low visibility) accidents have a mean injury fraction 
  of 0.63 vs 0.23 for VMC — nearly 3x higher risk.
- **Number of Engines:** Single-engine aircraft have the highest destruction rate (7.7%). 
  3 and 4 engine aircraft are significantly safer.

## Repository Structure
- `Aviation_Accidents_Cleaning.ipynb` — data cleaning steps
- `Aviation_Accidents_Data_Analysis.ipynb` — full EDA and recommendations
- `data/cleanedAviationData.csv` — cleaned dataset used for analysis

## Tools Used
- Python, Pandas, NumPy, Matplotlib, Seaborn

