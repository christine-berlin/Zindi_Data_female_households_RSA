# Machine learning project: <br> Womxn in Big Data South Africa: Female-Headed Households in South Africa

Jana Conradi, Christine Merkel, Alexandra Zimmermann-Rösner <br>

<sup><sup>(This project was originally a Zindi competion. More info:  [Zindi competition](https://zindi.africa/competitions/womxn-in-big-data-south-africa-female-headed-households-in-south-africa/data) )
 <br>



 Duration: 03.11.2021 - 05.11.2021 <br>
 Presentation: 08.11.2021

## About
South Africa is divided into over 4,000 wards.
The project is about predicting the target variable. 
The target variable of interest is the percentage of households per ward that are both female-headed and earn an annual income that is below 19,600 R (approximately $2,300 USD in 2011). For context, the poverty line in South Africa is defined as 1,183 R per month per person and the average individual salary in South Africa is 20,860 R per month.<br><br>
The project has several notebooks: <br>
- The baseline model (see [here](baseline_model.ipynb)) 
- The models we used (see [here](models/)) 
- EDA (see [here](EDA.ipynb)) 

The presentation slides are here : [slides](presentation.pdf)

## Data
- 2822 observations <br>
- 64 variables : <br>
   - housing forms
   - school attendance
   - access to water
   - school attendance
   - language
   - population group
   - household with car
   - household with tv
   - ...



## Requirements:
- pyenv with Python: 3.9.4

## Environment

```BASH
make setup 

#or 

pyenv local 3.9.4
python -m venv .venv
pip install --upgrade pip
pip install -r requirements.txt
source .venv/bin/activate
```



