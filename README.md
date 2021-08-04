# Real estate price prediction (ML)

<p>
    <a href="https://scikit-learn.org/stable/" alt="Scikit-learn">
        <img src="https://img.shields.io/badge/Scikit--learn-3499CD?style=flat&logo=scikit-learn&logoColor=white&labelColor=F89939" />
    </a>
    <a href="https://pandas.pydata.org/docs/index.html" alt="Pandas">
        <img src="https://img.shields.io/badge/Pandas-130654?style=flat&logo=pandas&logoColor=white" />
    </a>
    <a href="https://www.python.org/" alt="Anaconda">
        <img src="https://img.shields.io/badge/Anaconda-20232A?style=flat&logo=anaconda&logoColor=44A833" />
    </a>
    <a href="https://jupyter.org/hub" alt="Jupyter">
        <img src="https://img.shields.io/badge/Jupyter-orange?style=flat&logo=Jupyter&labelColor=505050" />
    </a>
</p>

The purpose of this project is to predict property prices of Melbourne's housing market. Two regression models were used for obtaining the predictions: linear regression and random forest regression. This project was built for the Aalto University course Machine Learning.

## Project structure

- `ML-project.ipynb` contains the Jupyter Notebook file for predicting property prices.
- [`ML-project.pdf`](./ML-project.pdf) is my machine learning report submitted for the Aalto University course Machine Learning.
- `data` directory contains the csv file of properties that have been for sale in Melbourne between 2016-2018 ([data source](https://www.kaggle.com/anthonypino/melbourne-housing-market)).
- `img` directory contains the plotted graphs.

## Quickstart for running the notebook
1. Install [Anaconda](https://docs.anaconda.com/anaconda/install/index.html).
2. Create a conda environment with all the dependencies:
    ```
    conda env create -f environment.yml
    ```
3. Activate the environment:
    ```
    conda activate ML_project
    ```
4. Run Jupyter Notebook locally:
    ```
    jupyter notebook
    ```
5. Choose the notebook called `ML-project.ipynb`
