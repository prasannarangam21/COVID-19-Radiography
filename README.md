  <h2 align="center">Covid-19 Radiography</h>

  <h4 align="center">
  <p align="center">
    Detecting Covid-19 and Pneumonia cases using CT-scans & Deep Learning
    </h4>
  </p>
</p>

<br></br>
## Demo
Link: [Deploy on colab in 2 mins](https://colab.research.google.com)

Directory Structure of the project
----------------------------------

    ├── data
    │   ├── sample_images                 <- Sample images for inference
    │   ├── 0_raw                         <- The original, immutable data dump.
    │   ├── 1_external                    <- Data from third party sources.
    │   ├── 2_interim                     <- Intermediate data that has been transformed.
    │   └── 3_processed                   <- The final, canonical data sets for modeling.
    │
    ├── notebooks                         <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                                        the creator's initials, and a short `-` delimited description, e.g.
    │                         `              1.0-jqp-initial-data-exploration`.
    │
    ├── output
    │   ├── models                        <- Trained and serialized models, model predictions, or model summaries
    │   │   ├── snapshots                 <- Saving training snapshots.
    │   │   ├── inference                 <- Converted trained model to an inference model.
    │   │   └── TrainingOutput            <- Output logs
    │   └── figures                       <- Generated graphics and figures to be used in reporting
    │
    ├── src                               <- Source code for use in this project.
    │   ├── __init__.py                   <- Makes src a Python module
    │   │
    │   ├── data                          <- Scripts to download or generate data
    │   │   ├── make_dataset.py
    │   │   └── preprocess.py    
    │   │
    │   ├── models                        <- Scripts to train models and then use trained models to make
    │   │   │                                predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization                 <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    ├── utils                             <- Utility scripts for Streamlit etc.
    ├── serve                             <- HTTP API for serving predictions using Streamlit
    │   ├── Dockerfile                    <- Dockerfile for HTTP API
    │   ├── Pipfile                       <- The Pipfile for reproducing the serving environment
    │   └── app.py                        <- The entry point of the HTTP API using Streamlit app
    │
    ├── .dockerignore                     <- Docker ignore
    ├── .gitignore                        <- GitHub's excellent Python .gitignore customized for this project
    ├── app.yaml                          <- contains configuration that is applied to each container started
    │                                        for that service
    ├── config.py                         <- Global configuration variables
    ├── LICENSE                           <- Your project's license.
    ├── Makefile                          <- Makefile with commands like `make data` or `make train`
    ├── README.md                         <- The top-level README for developers using this project.
    ├── tox.ini                           <- tox file with settings for running tox; see tox.readthedocs.io
    ├── requirements.txt                  <- The requirements file for reproducing the analysis environment, e.g.
    │                                        generated with `pip freeze > requirements.txt`
    └── setup.py                          <- makes project pip installable (pip install -e .) so src can be imported

## Technologies Used

1) Keras
2) Python
3) Streamlit
4) Docker
5) AWS

## 