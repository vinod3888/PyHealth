API CheatSheet
==============

Full API Reference: (https://pyhealth.readthedocs.io/en/latest/pyhealth.html). API cheatsheet for most learning models:

* :func:`pyhealth.models.sequence._dlbase.fit` : Fit a learning model.
* :func:`pyhealth.models.sequence._dlbase.inference` : Predict on X using the fitted estimator.
* **evaluator(y, y^hat)**\ : Model evaluation.

Model load and reload:

* :func:`pyhealth.models.sequence._dlbase.load_model` : Load the best model so far.