Predict housing prices in SG
==============================
Problem statement:

Target audience: Soon-to-be / engaged / married couples or singles wanting their own space. 
- Often, couples who wish to bid for their ideal BTO location are unsuccessful, or the BTO are not launched or launching in their ideal locations, or the long waiting time do not suit their needs. For singles, BTOs are not an option for them. 
- Hence, these people look to resale flats. 

- However, with a wide variety of choices, they're stuck in a paradox of choice. This problem is further exacerbated by the multitude of factors that could affect housing prices, e.g. number of bedrooms, bathrooms, housing type, location etc. How will these people know whether the asking price are reasonable? How will they know if their desired property is priced at the 'truth' value? 
- A house represents the biggest investment for most households. Your mortgage payments will likely consume a significant portion of your income.
- Therefore, being able to accurately predict current housing prices will provide valuable guidance for soon-to-be home owners to facilitate their decision making process and make an informed choice about whether their desired property will become their home. 

[This project was done as part of an immersive data science program called Metis. Linear regression and web scraping were project requirements]


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
