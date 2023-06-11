# EMATM0044 Introduction to AI Coursework

## For students NOT on the programme Data Science with Financial Technology

Download the dataset coursework other.csv from Blackboard. This dataset consists data collected from a Combined Cycle Power Plant over 6 years (2006-2011). Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (PE) of the plant. Your task is to predict the net hourly energy of the plant (the column PE).

## All Students:

You should consider the following aspects:

- The kind of algorithm to use (e.g.: classification/regression/clustering)
- The metric to use to measure the performance of the model
- What sort of baseline to compare the model to (`sklearn` has a module `sklearn.dummy` which may be useful in generating a baseline)
- How to choose the hyperparameters of your model
- How to test the performance of your model

Concretely, you should use two algorithms from `scikit-learn` and compare their performance on the dataset. You should also compare the performance of your chosen models against a baseline–i.e. a simple model that more complex models should be able to beat. `sklearn` has a module `sklearn.dummy` which may be useful in generating a baseline. You should use techniques to assess the ability of the models to generalise to unseen data and to ensure that your assessment of the models’ performance is robust.

## Mark scheme

- Overall presentation of the report, including use of appropriate sections, plots, diagrams, or tables to make your point. Do not include code snippets in the report. Instead, describe in words or equations what you are implementing. Format equations correctly.
- Picking a suitable type of algorithm (classification/regression/clustering) and justifying this choice.
- An appropriate choice of performance metric (e.g.: accuracy/precision/mean squared error etc) and justification.
- Discussion of the kind of baseline to compare against. (`sklearn` has a module `sklearn.dummy` which may be useful in generating a baseline)
- Use of an appropriate method to select the hyperparameters of the chosen algorithms. The explanation of which hyperparameters are selected should be backed up with e.g. tables and plots to show which hyperparameter values were chosen and why. Please choose at least one model that uses hyperparameters so that you can show your knowledge in this area. If you choose one model without hyperparameters then please explain in a couple of sentences what the benefits of choosing a model without hyperparameters are.
  -  Show that you understand what hyperparameters are and how they can be selected
  -  Look at the effects of different hyperparameter choices on the performance of your models
  -  Present the effects of the different hyperparameter choices on the performance of your models using tables, plots, or other presentation
  - State what choices you make and why
- Training and testing the performance of the models in a way that shows whether the models are able to generalise to unseen data and that ensures that the performance of the models is robust.
  - Train models and select hyperparameters in a way that gives robust performance
  - Test the performance of your models and compare their performance
  - Make sure your models are tested in a way that shows whether they are able to generalise to unseen data
- Analyse your results. What conclusions can be drawn?