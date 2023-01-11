# <span style="color:green">__Machine Learning Project__


## <span style="color:navy">__>> Kickstarter Project Success <<__

.

**Context:** 
Analyse and model success factors of kickstarter campaigns. Give new projects an idea what is needed for a successful funding and potentially even predict campaign success upfront.
In recent years, the range of funding options for projects created by individuals and small companies has expanded considerably. In addition to savings, bank loans, friends & family funding and other traditional options, crowdfunding has become a popular and readily available alternative.

Kickstarter, founded in 2009, is one particularly well-known and popular crowdfunding platform. It has an all-or-nothing funding model, whereby a project is only funded if it meets its goal amount; otherwise no money is given by backers to a project.
A huge variety of factors contribute to the success or failure of a project — in general, and also on Kickstarter. Some of these are able to be quantified or categorized, which allows for the construction of a model to attempt to predict whether a project will succeed or not. The aim of this project is to construct such a model and also to analyse Kickstarter project data more generally, in order to help potential project creators assess whether or not Kickstarter is a good funding option for them, and what their chances of success are.

**Source of the data:** Kickstarter Project Success Data, containing information about their campaigns.

**Final Deliverables:**
1. Slide deck PDF pushed to GitHub designed for non-technical stakeholders that outline findings, recommendations, and future work (10 min presentation).
2. Jupyter notebook following PEP8 designed for data science/technical audience.
3. (Recommended) Python script for generating (takes .csv as argument and saves the model locally) and running your model from the terminal (takes test.csv and model as arguments and outputs accuracy and predictions as .csv)

**Team:** Jens Bimberg, Karine Real, Niels Lory

**Files of the Project:**
1. [EDA and Cleaning Notebook](EDA-and-Cleaning.ipynb)
2. [Machine Learning Notebook](ML_Kickstarter.ipynb)
3. [Presentation Slides](Presentation_Kickstarter_ML_Jan23.pdf)

---
## **Requirements and Environment**


**Requirements:**
- pyenv with Python: 3.9.8

**Environment:**

For installing the virtual environment you can either use the Makefile and run `make setup` or install it manually with the following commands: 

```Bash
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```