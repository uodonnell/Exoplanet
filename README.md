# Exoplanet
## Data Source
This [data](https://exoplanetarchive.ipac.caltech.edu/docs/data.html) is from CalTech and NASA, they collected data about objects identified by the Kepler Telescope, known as Kepler Objects of Interest (KOIs). For each KOI there is data on the radius, temperature, orbital period, etc. Most importantly, it has a column that has a classification based on whether or not the KOI is an exoplanet or not, this is what I used for classification.

## Models
I fit several models, which are all explained in the notebook.
- Logistic Regression
  - Accuracy: 0.76
- KNN
  - Accuracy: 0.75
- Tree
  - Accuracy: 0.78
- Random Forest
  - Accuracy: 0.85
- Neural Network
  - Accuracy: 0.80
