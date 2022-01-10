# U.S. Medical Insurance Costs

## About

This project analyzes the costs of US insurance based on the data from a typical healthcare institution.

## Data Sources
The dataset is downloaded from [Kaggle](https://www.kaggle.com/mirichoi0218/insurance). It has the following columns:
* **age**: age of primary beneficiary
* **sex**: insurance contractor gender, female, male
* **bmi**: body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
* **children**: number of children covered by health insurance / number of dependents
* **smoker**: whether the patient is a smoker or not
* **region**: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
* **charges**: Individual medical costs billed by health insurance

## Key Insights
Click on the [us-medical-insurance-costs.ipynb](https://github.com/vytran17/us-medical-insurance-costs/blob/main/us-medical-insurance-costs.ipynb) file to view the complete code of the analysis. Select insights are summarized below.

### The insurance cost of smokers is significantly higher

| Smoker status | Avg. insurance cost |
| ------------- |:-------------------:|
| Smoker        | $32,050.23          |
| Non-smoker    | $8,434.27           |

### Older patients tend to have a higher body mass index

| Age group     | Average BMI         |
| ------------- |:-------------------:|
| 10-19         | 29.97               |
| 20-29         | 29.79               |
| 30-39         | 30.44               |
| 40-49         | 30.71               |
| 50-59         | 31.51               |
| 60-69         | 32.02               |

### The geographic region of the patients is evenly distributed, with southwest being slightly overrepresented.

| Region     | Number of patients  | Percent of total    |
| -----------|:-------------------:|:-------------------:|
| Southeast  | 364                 | 27.2%               |
| Southwest  | 325                 | 24.3%               |
| Northwest  | 325                 | 24.3%               |
| Norhteast  | 324                 | 24.2%               |

### Average patient is 31 years old

### Average age of patients with at least 1 child is 40 years old
