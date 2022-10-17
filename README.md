[Maria Kelly Venezuela, Ph.D](http://lattes.cnpq.br/6133181706857392). Ciência de Dados. [Insper](https://www.insper.edu.br), 2021.

# Fake JobPosting Prediction

### Motivation:

Due to the conditions we live in today, the use of the internet for job search has increased in recent years. We believe that the safety of these people when applying is of great importance, so we decided to create a forecasting model to recognize fraud in a possible job offer.

For this, we decided to investigate the occurrences of fraud in job interviews collected in a database. Using different classification methods known in the literature. Thus, we will analyze their proficiency in classifying a possible fraud of a proposal in order to help unemployed people.

> The internet has shortened distances and brought about several changes in the forms of consumption, such as entertainment, online shopping, study methodologies and even the search for a job. According to data from the 2019 Survey of Brazilian Professionals carried out by Catho with more than 6,200 respondents, most professionals look for a job on the internet, with 78% looking on job sites.

Jornalismo. "**Internet job search**: About 80% of professionals look for opportunities online". Jornal Contábil, 2019, translated, https://www.jornalcontabil.com.br/busca-de-emprego-na-internet-cerca-de-80-dos-profissionais-procuram-oportunidades-online/. Accessed 08 Jun 2021.


### Objective:

1. Develop exploratory data analysis (univariate and multivariate), using appropriate statistical and computational tools.
2. Select information from databases, handle them and prepare them for processing.
3. Specify the appropriate probability distributions for the discrete and continuous quantitative variables.
4. Conduct appropriate inferential tests that can support decision making.
5. Analyze relationships between variables, using appropriate inferential statistical tools.

### Notebooks:

1. [Exploratory_analysis.ipynb](notebooks/Exploratory_analysis.ipynb) - Exploratory analysis of the dataset.
2. [Predictive_model.ipynb](notebooks/Predictive_model.ipynb) - Building predictive model.

### Project report:

[Access here](Report.md) the project report.

## Dataset

> This dataset contains 18K job descriptions out of which about 800 are fake. The data consists of both textual information and meta-information about the jobs. The dataset can be used to create classification models which can learn the job descriptions which are fraudulent.

The dataset is very valuable as it can be used to answer the following questions:
1. Create a classification model that uses text data features and meta-features and predict which job description are fraudulent or real.
2. Identify key traits/features (words, entities, phrases) of job descriptions which are fraudulent in nature.
3. Run a contextual embedding model to identify the most similar job descriptions.
3. Perform Exploratory Data Analysis on the dataset to identify interesting insights from this dataset.

Bansai, Shivam. "**[Real Or Fake] Fake Jobposting Prediction**: Dataset of real and fake job postings". Kaggle, 2020, https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction. Accessed 21 May 2021.

### Source:

> The Employment Scam Aegean Dataset (EMSCAD) is a publicly available dataset containing 17,880 real-life job ads that aims at providing a clear picture of the Employment Scam problem to the research community and can act as a valuable testbed for scientists working on the field. Our first publication is available online by MDPI Future Internet Journal.

Laboratory of Information & Communication Systems Security. "**Employment Scam Aegean Dataset**". University Of The Aegean, 2014, http://emscad.samos.aegean.gr. Retrieved 29 Feb 2020.

## Authors

|![](https://avatars.githubusercontent.com/u/72350494?v=4)               |![](https://avatars.githubusercontent.com/u/22255332?v=4)|![](https://avatars.githubusercontent.com/u/73079076?v=4)|
|:----------------------------------------------------------------------:|:-------------------------------------------------------:|:-------------------------------------------------------:|
|[Gustavo Eliziario Stevenson de Oliveira](https://github.com/gustavoeso)|[Luciano Felix Dias](https://github.com/FelixLuciano)    |[Pedro Cliquet do Amaral](https://github.com/pcliquet)   |

## License

This project is [MIT licensed](https://github.com/FelixLuciano/Fake-JobPosting-Prediction/blob/main/LICENSE).
