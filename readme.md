# Data Visualization on Old Cars Price Dataset

## About Dataset:
- An Indian dataset on **Old Car Prices**.
- Data extracted from https://www.machinehack.com/course/predicting-the-costs-of-used-cars-hackathon-by-imarticus/
- Original dataset: 'Data_Train.xlsx'
- The dataset originally used on the wesbite has been cleaned by me, which is the one included in the project as 'car_clean.csv'
- Cleaned Dataset has 6019 data points and 14 features.
- The data_viz_slides.html is the final presentation consisting of tutorial.

## Packages used:
- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)

## Some common plots used:
- Histograms
- Bar graphs
- Boxplots
- Violin Plots
- Barplots
- Clustered Bar plots
- Scatterplots
- Heatmaps

## Conclusions:
### Univariate:
- **Top cities of old cars: Mumbai, Hyderabad, Kochi, Coimbatore. least Ahmedabad**
- **Kilometers Driven is almost uniform distribution**
- **Diesel and Petrol constitutes more than 80% of cars**
- **Most cars are manual**
- **Price of Car: first > Second > third > Fourth & Above**
- **log of prices is normally ditributed. ie price is highly right skew**
- **Top 4 cars: Maruti, Hyunday, Honda, toyota constitute more than 80% of cars**

### Bivariate:
- **Order of Mileage: CNG > LPG, Diesel > Petrol**
 - Mileage of ELectric Vehicles are NaN
 - LPG has high variability
 - CNG is highly left skew
- **Highest average price of car in Coimbatore and lowest in Kolkata**
- **Price has a direct correlation with Price**
- **Electric and Diesel cars are expensive, while CNG and LPG are cheaper**
- **Price of Automatic Cars is SIGNIFICANTLY high than Manual cars**
- **Engine_CC and Price: slightly +ve correlation**
- **Power_bhp and price: good +ve correlation**
- **Power_bhp and Engine_CC: Highly =ve correlation**
- **Kilometers Driven and Year: Good -ve correlation**

### Multivariate
- **LPG and CNG lie have lower Engine_CC and Power_bhp**
- **Only Petrol cars lie in the higher Power_bhp and Engine_CC range**
- **In  Manual vs Automatic cars, the trend of Petrol, Electric and Disel car prices is completely reversed**
