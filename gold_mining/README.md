# Optimization of gold mining company production

[Jupyter Notebook viewer](https://nbviewer.jupyter.org/github/abatomunkuev/Yandex_Practicum_DS_EN/blob/main/gold_mining/gold_mining.ipynb)

This project shows: 
- ability of writing solid,structured Python code 
- ability of using existing utilities(libraries) for processing and analyzing data.
- ability of utilizing Machine Learning models 
- statistical analysis application
- exploratory analysis application
- analytical and data pre-processing skills

Project is combined project that involves:
1. Data pre-processing
2. Exploratory Analysis
3. Statistical Analysis
4. Machine Learning

## Technological process

When the mined ore undergoes primary processing, a crushed mixture is obtained. It is sent for flotation (enrichment) and two-stage purification:
1. Flotation - A mixture of gold-bearing ore is fed into the flotation plant. After beneficiation, a rough concentrate and "tailings", i.e. product leftovers with a low concentration of valuable metals, are obtained. The stability of this process is affected by the inconsistent and non-optimal physical and chemical state of the flotation slurry (mixture of solid particles and liquid).
2. purification - The crude concentrate undergoes two purifications. The output is the final concentrate and new tailings.

## Data description

### Technological process
- *Rougher feed*
- *Rougher additions* (or reagent additions): 
    - Xanthate
    - Sulphate
    - Depressant
- *Rougher process* - floatation
- *Rougher tails* 
- *Float banks* 
- *Cleaner process* 
- *Rougher Au* — gold rough concentrate
- *Final Au* — gold final concentrate

### Stage parameters
- *air amount* 
- *fluid levels* 
- *feed size* — raw material granule size
- *feed rate*

### Feature names

**[stage].[parameter_type].[parameter_name]**. Пример: **rougher.input.feed_ag**

Possible values for block **[stage]**:
- *rougher —* floatation
- *primary_cleaner* 
- *secondary_cleaner* 
- *final* — final characteristics

Possible values for block **[parameter_type]**:

- *input* — raw material characteristics
- *output* — product characteristics
- *state* — parameters that characterize the current state of the stage
- *calculation*

|Column            |Description            |
 |:---------------|:------------------------|
|children        |number of childern in family                 |
|days_employed        |record of employment in days                |
|dob_years        |customer age in years               |
|education        |customer education level                 |
|education_id        |customer education level id                 |
|family_status        |family status                 |
|family_status_id        |family status id                 |
|gender        |gender                 |
|income_type        |type of employment                 |
|debt        |whether a customer was in debt                |
|total_income        |monthly total income  in Rubles             |
|purpose        |purpose to get a loan                 |

## Task

The company ["Zyfra"](http://zyfra.com/) develops solutions for the efficient operation of industrial plants. The company needs a machine-learning model to help optimize production to avoid launching enterprises with unprofitable characteristics. The company needs a machine learning model to predict the recovery rate of gold from gold ore.  


## Libraries used
*pandas*
*numpy*
*matplotlib*
*seaborn*
*scipy*
*sklearn*
