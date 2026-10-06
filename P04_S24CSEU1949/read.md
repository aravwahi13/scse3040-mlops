# Module responsibilities

- __init__.py — turns the folder into an importable package and exposes its public functions.
- data.py — loads the delivery dataset from CSV and splits it into training and test sets.
- features.py — computes and checks properties of a single delivery order (e.g. average speed).
- model.py — trains, scores, saves, and loads the prediction model.
- validate.py — checks whether an order's field values (distance, prep time, traffic, rain) are valid.
- train.py — command-line script that trains the model on the dataset and reports its error.
- predict.py — command-line script that loads the saved model and prints a prediction for one order.

## AI assistance disclosure
Used Claude (Anthropic) to help debug environment/file-path issues while
zipping the package, and to review task correctness. All module code was
written and understood by me.