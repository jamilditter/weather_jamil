# Seattle vs Portland Precipitation

> This project seeks to compare the city of Portland, OR, and the city of Seattle, WA, and see which has more average rainfall.

---

## Project Overview

This project seeks to determine whether Portland or Seattle has more average rainfall. This project uses NOAA weather data measuring precipitation for both cities to answer this question. By looking at mean daily precipitation, mean monthly precipitation, and mean monthly proportion of days with precipitation, this project came to the conclusion that there is no significant difference in the rainfall of Portland and Seattle.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebook
├── reports/              # Communication report
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** All data was sourced from NOAA.
- portland_rain.csv: https://www.dropbox.com/scl/fi/oqkze3lflgr9zxs6jlgyp/portland_rain.csv?rlkey=3xpm7bhelvc54wvkkzz5ftzru&st=3mkvcl10&dl=0
- seattle_rain.csv: https://www.dropbox.com/scl/fi/4umev6eq3ktdzjtlj3t5z/seattle_rain.csv?rlkey=7b6ssbeirc02q30ikyanhz5su&st=hvo70jxa&dl=0
- **Description:** This data was imported from NOAA (National Oceanic and Atmospheric Administration), and records daily precipitation values over the period of 2018-2022. This data was downloaded as a pair of csv files, one for Seattle weather data and one for Portland weather data.
---

## Analysis

The notebook used in this analysis is the weather_final.ipynb notebook, located in the code folder. This was the only notebook used in this analysis, and should be run in the order specified in the document. The data was processed by merging the two datasets together, filling in NAs in the Seattle dataset by taking the same day across each year and averaging the results, and using this number to fill in any missing data. 

---

## Results

My results showed that under all three circumstances considered, Seattle and Portland had very similar levels of rainfall. Thus, the conclusion drawn from this data shows that there is no significant difference in rainfall between the cities of Seattle and Portland. 

---

## Authors

- Jamil Ditter - [@jamilditter](https://github.com/jamilditter)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


---

## Acknowledgements

- NOAA Weather Observation Data
- Brian Fischer
