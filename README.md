ATTESSA
==============================

Auto Trader with TimE Series and Sentiment Analysis

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

## Checklist
### Setup

- [ ] Install Postgres server on RaspberryPi
- [ ] Setup remote ssh tunnel (via Serveo)
- [ ] Setup permissions

### Data Collection

- [ ] Find API for news
- [ ] Implement web scrapers
- [ ] Scheduling

### BERT
- [ ] Find Pre-trained models of BERT on Sentiment Analysis
- [ ] Data labeling (via Prodigy) [Percentage: 0.0%]
- [ ] Fine tune the model [Accuracy: 0.0%]

### Time Series Prediction
- [ ] Idea 1: use simple forecasting models (SARIMA or Exponential smoothing)
- [ ] Idea 2: signal processing using FFT + Deep Learning

### Price Prediction
- [ ] Feature engineering: add economics and finance related features
- [ ] Prediction target: is the stock price going to increase or decrease after a periods

### Auto-Trading
- [ ] Buy/Sell functionalities using APIs
- [ ] (Alternative) Use web scrapers (un-reliabe)

### Production
- [ ] Question: Can we/do we want to make this real-time?
- [ ] Migrate database into a real server
