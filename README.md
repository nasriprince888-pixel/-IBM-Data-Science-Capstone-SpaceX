# IBM Data Science Capstone - SpaceX Falcon 9 Landing Prediction

## Project Overview
This project predicts whether the Falcon 9 first stage will land successfully.
SpaceX can reuse the first stage if it lands, saving ~$100M per launch.
If we can predict landing success, we can estimate launch cost.

**Author:** Nasri Prince
**Course:** IBM Applied Data Science Capstone - Coursera

## Repository Structure
- `SpaceX_Data_Collection_API.ipynb` - Data collection via SpaceX API
- `SpaceX_Web_Scraping.ipynb` - Web scraping Falcon 9 launches from Wikipedia
- `SpaceX_EDA_Data_Wrangling.ipynb` - Data wrangling, create Class label
- `SpaceX_EDA_SQL.ipynb` - EDA with SQL queries (10 Tasks)
- `SpaceX_EDA_Visualization.ipynb` - EDA with Seaborn / Matplotlib
- `SpaceX_Interactive_Map.ipynb` - Interactive map with Folium
- `SpaceX_Dashboard.py` - Interactive dashboard with Plotly Dash
- `SpaceX_ML_Prediction.ipynb` - Machine Learning prediction

## Key Findings
- Success rate increases over years
- ES-L1, GEO, HEO, SSO orbits have highest success rate
- CCAFS SLC-40 is the most used launch site
- NASA (CRS) total payload = 45,596 kg
- First successful ground pad landing: 2015-12-22

## Machine Learning Results
| Model | Accuracy |
|-------|----------|
| Decision Tree | 87.5% - BEST |
| Logistic Regression | 84.64% |
| SVM | 84.64% |
| KNN | 83.93% |

**Best Model:** Decision Tree with 87.5% accuracy

## Tools Used
Python, Pandas, Numpy, SQL, BeautifulSoup, Folium, Plotly Dash, Scikit-learn, Matplotlib, Seaborn
