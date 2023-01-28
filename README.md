# electric_motion_forecast
Challenge for data analytics in application

## instructions for GitHub-Colab integration and versioning
this repository can be dinamically linked and run in Google Colab, how?
1. after the user get access to this repository as editor
2. the user can open a selected notebook version on branch directly from Google Colab in file > open notebook > GitHub OR he can open the notebook in GIT and select "Open in Colab" in the first line
3. *after* he created a branch in GitHub, he can save a new edited Colab notebook in the new branch
4. Main branch is then merged via pull requests via Git UI

when preferred, the user can use any local IDE for development and push the local notebook to a branch of this repository
that can be accessed via Colab as explained in point 2.

## Guide of repository's notebooks

- combinedataframe notebook: used to combine discrete and continuos data for both horizontal an vertical set ups. They are combined associating a value from continuous data with a value from discrete data such that the results are two dataset with A,A,B,B,C,C,.. structure

- data_analysy_model_selection notebook: data are explored via visualization and summary statistics, we trained different models using train, validation and test framework to define the most accurate model as CNN LSTM neural network for series analysis

- horizontal model notebook: ...

- vertical model notebook: ...

- models evaluation notebook: ...

## Challenge description and processes via CRISP framework
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modelling
5. Evaluation
6. Deployment

