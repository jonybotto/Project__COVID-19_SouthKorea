# COVID-19 in South Korea: What can we learn from it?

&nbsp;

## Motivation and Objectives
This project will have as motivation the hypothetical scenario where I am called by the president of my imaginary country to analyse the data they got from the Covid-19 pandemic in South Korea. The goal will be to report to my country's Emergency Council any valuable insights from such analysis, allowing them to come up with a plan to best prepare our own homeland for the next probable wave of the pandemic.

&nbsp;

## Requirements

To run the notebook, first install dependencies using pip:

```Python
pip install -r requirements.txt
```

*Note*: Maps and interactive/animated plots are not visible on GitHub. On Google Colab, the notebook should be run to display such content.

&nbsp;

## Source of the Data
The datasets used for this project were retrieved from [Kaggle](https://www.kaggle.com/datasets/kimjihoo/coronavirusdataset/). However, the primary source of the data was [KDCA (Korea Disease Control and Prevention Agency)](https://www.kdca.go.kr/cdc_eng/).

&nbsp;

## Datasets Descriptions
For a detailed description of the features in each dataset, please check [here](https://www.kaggle.com/code/kimjihoo/ds4c-what-is-this-dataset-detailed-description).

### Case Data
* **Case**: Data of COVID-19 infection cases in South Korea.

### Patient Data
* **PatientInfo**: Epidemiological data of COVID-19 patients in South Korea.

### Time Series Data
* **Time**: Time series data of COVID-19 status in South Korea.
* **TimeAge**: Time series data of COVID-19 status in terms of the age in South Korea.
* **TimeGender**: Time series data of COVID-19 status in terms of gender in South Korea.
* **TimeProvince**: Time series data of COVID-19 status in terms of the Province in South Korea.

### Additional Data
* **Region**: Location and statistical data of the regions in South Korea.
* **Weather**: Data of the weather in the regions of South Korea.
* **Policy**: Data of the government policy for COVID-19 in South Korea.
