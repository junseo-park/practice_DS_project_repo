# Title of Project 

The project title should capture the project without being too verbose. Often if you are utilizing certain statistical methods you should include the specific or overarching methods in your title, along with subject matter for your respective data set. Since many of our projects are not being created as standalone modules we must be help accountable for naming our repos appropriately. You can also get creative with the title, but be sure its descriptive enough. 

## Contributors

+ Contributor Names 

## Table of Contents

+ More 
+ Will be
+ Added Later

## Abstract
Give us a paragraph detailing your project

## Steps
These steps are often steps not included within the scripts themselves so like reminders for virtual environment set up, database management, api keys set up, etc. 

## Statistical Analysis
Give a brief overview of any statistical analysis you used in your project. This should not be verbose either but should tell people enough of the project for them to know context. Example includes predictive models, specific statistical analysis (i.e. Time Series Analysis), 

## Conclusion 
A brief conclusion relating to your statistical analysis as well as any key takeaways relating to the project as a whole (lessons learned, potential drawbacks, future expansion ideas). 

## To-Do List
This can be created anywhere in the repo, but include a to-do list to help you and your teammates check yourselves in check. 

## Structure

Heavily inspired and elements taken from [Cookiecutter Data Science's Project repo Skeleton](https://drivendata.github.io/cookiecutter-data-science/). We do suggest utilizing their package if you would like but for the purposes of our org. the level of complexity can be made simiplier with this example repo.

	├── LICENSE
	├── README.md          <- The top-level README for developers using this project.
	├── data
	│   ├── external       <- Data from third party sources.
	│   ├── interim        <- Intermediate data that has been transformed.
	│   ├── processed      <- The final, canonical data sets for modeling.
	│   └── raw            <- The original, immutable data dump.
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
	│   └── figures        <- Generated graphics and figures to be used in reporting
	│
	├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
	│                         generated with `pip freeze > requirements.txt`
	│
	└── src                <- Source code for use in this project.
	    ├── __init__.py    <- Makes src a Python module
	    │
	    ├── data           <- Scripts to download or generate data
	    │   └── make_dataset.py
	    │
	    ├── features       <- Scripts to turn raw data into features for modeling
	    │   └── build_features.py
	    │
	    ├── models         <- Scripts to train models and then use trained models to make
	    │   │                 predictions
	    │   ├── predict_model.py
	    │   └── train_model.py
	    │
	    └── visualization  <- Scripts to create exploratory and results oriented visualizations
	        └── visualize.py
