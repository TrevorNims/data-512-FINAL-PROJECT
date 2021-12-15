# Data 512: Final Project
This repository contains explorations into two different facets of the effect of Covid-19 in Prince George's County MD. The analysis will explore the effects of masking and vaccines on a time series dataset of confirmed Covid-19 cases, continuing with another time series-based statistical analysis of the effects of Covid-19 on weekly crime rates.

# Getting Started
To clone the project, run the following command in your terminal:
```bash
git clone 'https://github.com/TrevorNims/data-512-FINAL-PROJECT'
```
Next, create a new virtual environment and install all required pakcages by running the following command in your terminal:
```bash
pip install requirements.txt
```
## Data Acquisition

To obtain the data necessary to run the notebooks, download the following four .csv files and place them in a local directory titled 'data'.

1) John's Hopkins Confirmed Covid-19 Case Count Data: 
   
   - **url**: https://www.kaggle.com/antgoldbloom/covid19-data-from-john-hopkins-university
   - **license**: Creative Commons Attribution 4.0 International
   
2) New York Times Masking Usage Survey Responses:
   
    - **url**: https://github.com/nytimes/covid-19-data/tree/master/mask-use
    - **license**: https://github.com/nytimes/covid-19-data/blob/master/LICENSE

3) CDC Mask Mandate Data:
   
    - **url**: https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i
    - **terms of use**: https://www.cdc.gov/nchs/data_access/restrictions.htm

4) Prince George's County MD Crime Reporting Data:
   
    - **url**: https://data.princegeorgescountymd.gov/Public-Safety/Crime-Incidents-February-2017-to-Present/wb4e-w4nf
    - **terms of use**: https://data.princegeorgescountymd.gov/terms-of-use

## Project File Structure
 Initially, the project repository is structured as follows:
 ```
 .
├── A4\ -\ Common\ Analysis.ipynb
├── A5\ -\ Crime\ Analysis.ipynb
├── LICENSE
├── README.md
├── Final\ Report.pdf
└── visualizations
    ├── Mask_Wearing_Proportions.png
    ├── Time_Series_Change_With_Regression_Lines.png
    ├── Time_Series_Total.png
    └── tested_subtypes_box_plot.png
 ```
Once the data has been downloaded, your local directory should look like this:
```
.
├── A4\ -\ Common\ Analysis.ipynb
├── A5\ -\ Crime\ Analysis.ipynb
├── LICENSE
├── README.md
├── Final\ Report.pdf
├── data
│   ├── Crime_Incidents_February_2017_to_Present.csv
│   ├── U.S._State_and_Territorial_Public_Mask_Mandates_From_April_10__2020_through_August_15__2021_by_County_by_Day.csv
│   ├── johns_hopkins_data
│   │   ├── CONVENIENT_global_confirmed_cases.csv
│   │   ├── CONVENIENT_global_deaths.csv
│   │   ├── CONVENIENT_global_metadata.csv
│   │   ├── CONVENIENT_us_confirmed_cases.csv
│   │   ├── CONVENIENT_us_deaths.csv
│   │   ├── CONVENIENT_us_metadata.csv
│   │   ├── RAW_global_confirmed_cases.csv
│   │   ├── RAW_global_deaths.csv
│   │   ├── RAW_us_confirmed_cases.csv
│   │   └── RAW_us_deaths.csv
│   └── mask-use-by-county.csv
└── visualizations
    ├── Mask_Wearing_Proportions.png
    ├── Time_Series_Change_With_Regression_Lines.png
    ├── Time_Series_Total.png
    └── tested_subtypes_box_plot.png
```
## That's It!
Now you are able to run the analyses in both of the .ipynb files, examining the effects of Covid-19 in a metro-suburb of Washington D.C! All visualizations produced by the notebooks will be outputted into the visualizations directory - enjoy checking them out!

## License
This project is licensed under the MIT license, additional information regarding it can be found in the LICENSE file.