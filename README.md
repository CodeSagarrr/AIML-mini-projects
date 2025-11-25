# ML Mini Projects

Two lightweight notebooks for practicing end-to-end ML workflows on structured data.

## Mini Project 1 — House Price Predictor
- Focus: regression on housing attributes to estimate selling price.
- Notebook: `mini-project.ipynb`.
- Data: `public/Housing2.csv` (cleaning, encoding, modeling handled inline in the notebook).
- Workflow: open the notebook, follow the exploration → feature engineering → modeling flow, and iterate on models/hyperparameters.

## Mini Project 2 — Titanic Survival Classifier
- Focus: binary classification (0 = did not survive, 1 = survived) on Titanic passenger records.
- Notebook: `mini-project2.ipynb`.
- Data: `public/Titanic-Dataset.csv`. The notebook covers null-imputation (Age, Embarked, Cabin), engineered `HasCabin`, one-hot encoding for `Sex`/`Embarked`, MinMax scaling, and a baseline `DecisionTreeClassifier`.
- Workflow: run cells sequentially to reproduce preprocessing, train/test split, scaling, and evaluation (accuracy + classification report). Swap in other classifiers (e.g., logistic regression) by modifying the modeling cell.

## Next steps
- Promote notebook logic into reusable scripts or an API.
- Add automated checks around data preprocessing steps.
- Experiment with richer models (gradient boosting, ensembles, etc.) once baselines are solid.

