# Unemployment Analysis with Python

## Project Overview

This project explores unemployment data in India using Python. It
examines monthly trends, compares rural and urban areas, and
investigates changes during the early COVID-19 period.

## Objectives

- Clean and explore unemployment data.
- Visualize monthly unemployment trends.
- Compare rural and urban unemployment rates.
- Compare regional rates before and during the early COVID-19 period.
- Examine whether the available data supports seasonal analysis.
- Suggest areas for further policy investigation.

## Dataset

The project uses two files from the
[Unemployment in India dataset on Kaggle](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india):

- `Unemployment in India.csv`: May 2019 to June 2020, including
  rural and urban records.
- `Unemployment_Rate_upto_11_2020.csv`: January to October 2020.

The files were analyzed separately because their coverage and
levels of detail differ.

## Tools Used

- Python
- Pandas
- Matplotlib
- KaggleHub
- Google Colab

## Key Findings

- In Dataset 1, the average recorded unemployment rate rose from
  10.70% in March 2020 to 23.64% in April and peaked at 24.88%
  in May.
- Both rural and urban averages rose sharply in April 2020.
- Among 47 region-area combinations with complete coverage for
  the selected comparison periods, Puducherry urban had the largest
  recorded increase: 74.70 percentage points.
- Dataset 2 showed a similar rise and decline, with its average
  recorded rate reaching 23.24% in May 2020.
- The available data was insufficient to establish a reliable
  seasonal pattern.

## Limitations

Monthly averages are unweighted averages of available records and
are not necessarily national unemployment rates. Regional coverage
can change between months. The comparison is descriptive and does
not establish that COVID-19 caused the observed changes. Unusually
large values should be verified against the original source.

## How to Run

1. Open the `.ipynb` notebook in Google Colab.
2. Run the cells in order.
3. The notebook uses KaggleHub to download the dataset and Python
   to clean, analyze, and visualize it.
