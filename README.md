# Consuming a Python Model from a Python Client
 

Invoking a Python model from a Python client may seem simple: just call predict (or, for a classifier, predict_proba) on the model. However, you wouldn’t want to retrain the model every time you use it. The goal is to train the model once and allow a client application to recreate it in its trained state. To do this, Python developers commonly use the pickle module.
