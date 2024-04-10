{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

	├── README.md
	├── cookiecutter.json
	├── docs
	│   ├── README.md
	│   ├── docs
	│   │   ├── css
	│   │   │   └── extra.css
	│   │   ├── favicon.ico
	│   │   └── index.md
	│   └── mkdocs.yml
	├── requirements.txt
	└── {{ cookiecutter.repo_name }}
	    ├── LICENSE
	    ├── README.md
	    ├── data
	    │   ├── preprocessed
	    │   ├── processed
	    │   └── raw
	    ├── docs
	    │   ├── Makefile
	    │   ├── commands.rst
	    │   ├── conf.py
	    │   ├── getting-started.rst
	    │   ├── index.rst
	    │   └── make.bat
	    ├── models
	    ├── notebooks
	    ├── references
	    ├── requirements.txt
	    ├── setup.py
	    └── {{ cookiecutter.repo_name }}
		├── __init__.py
		├── data_ops
		│   └── __init__.py
		├── training
		│   ├── __init__.py
		│   ├── models.py
		│   └── train.py
		├── utils
		│   ├── __init__.py
		│   ├── data_utils.py
		│   ├── training_utils.py
		│   └── visualization_utils.py
		├── validation
		│   ├── __init__.py
		│   ├── inference.py
		│   └── validate.py
		└── visualization
		    └── __init__.py

<!--     ├── LICENSE -->
<!--     ├── README.md                               <- The top-level README for developers using this project. -->
<!--     ├── data -->
<!--     │   ├── processed                           <- The final, canonical data sets for modeling. -->
<!--     │   └── raw                                 <- The original, immutable data dump. -->
<!--     │ -->
<!--     ├── docs                                    <- A default Sphinx project; see sphinx-doc.org for details -->
<!--     │ -->
<!--     ├── models                                  <- Trained and serialized models, model predictions, or model summaries -->
<!--     │ -->
<!--     ├── notebooks                               <- Jupyter notebooks. Naming convention is a number (for ordering), -->
<!--     │                                              the creator's initials, and a short `-` delimited description, e.g. -->
<!--     │                                              `1.0-jqp-initial-data-exploration`. -->
<!--     │ -->
<!--     ├── references                              <- Data dictionaries, manuals, and all other explanatory materials. -->
<!--     │ -->
<!--     ├── reports                                 <- Generated analysis as HTML, PDF, LaTeX, etc. -->
<!--     │ -->
<!--     ├── requirements.txt                        <- The requirements file for reproducing the analysis environment, e.g. -->
<!--     │                                              generated with `pip freeze > requirements.txt` -->
<!--     │ -->
<!--     ├── {{cookiecutter.project_name}}           <- Source code for use in this project. -->
<!--     │   │ -->
<!--     │   ├── data                                <- Scripts to download or generate data -->
<!--     │   │ -->
<!--     │   ├── utils                                <- Scripts utilities used during data generation or training -->
<!--     │   │ -->
<!--     │   ├── training                            <- Scripts to train models -->
<!--     │   │ -->
<!--     │   ├── validate                            <- Scripts to validate models -->
<!--     │   │ -->
<!--     │   └── visualization                       <- Scripts to create exploratory and results oriented visualizations -->
