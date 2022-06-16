# Flight-Delays-Predection
Flight Delays Predection
Around $40 billion is the estimated economic loss, thanks to Flight delays. This repository contains the code for a two staged (pipelined) machine learning model which classifies the flights are delayed or otherwise and then predicts the delay in minutes using regression. The model uses weather forecast dataset and the flight dataset.
In an effort to cut costs and keeping in mind the comfort of passengers, this model hopefully helps to reduce the delay prediction of flights and thereby the delay itself. Feel free to check it out!
### Data
We will be working with data from air travel industry. We will have four separate tables:
1. **flights**: The departure and arrival information about flights in US in years 2018 and 2019.
2. **fuel_comsumption**: The fuel comsumption of different airlines from years 2015-2019 aggregated per month.
3. **passengers**: The passenger totals on different routes from years 2015-2019 aggregated per month.
5. **flights_test**: The departure and arrival information about flights in US in January 2020. This table will be used for evaluation. For submission, we are required to predict delays on flights from first 7 days of 2020 (1st of January - 7th of January). We can find sample submission in file _sample_submission.csv_
All data has been stored in a Google Drive folder as the CSV files are too large to upload to GitHub.
# Installation Requirements
## Environment
It is recommended to have a Linux or macOS development environment for convenience, although the code runs on Windows 10. <br>
Use Anaconda to manage your packages and Python 3 (version >= 3.8.0 recommended). <br>
It is also recommended to run the code on <strong>Jupyter Notebook</strong>.

## Dependencies
### With Anaconda, no need to install
- matplotlib
- scikit-learn
- numpy
- pandas
