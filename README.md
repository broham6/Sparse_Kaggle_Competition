# Sparse_Kaggle_Competition
We saved our model with pickle. To load it, do the following.
```python
import pickle

# Load the pickled model
model_filename = 'xgb_model.pkl'
with open(model_filename, 'rb') as file:
  loaded_model = pickle.load(file)

# Use the loaded model for predictions
predictions = loaded_model.predict(X_test)
```
