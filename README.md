# adjusted_r2_score  

A lightweight and simple Python package to calculate the **adjusted R-squared score**, a key metric for evaluating the goodness-of-fit of regression models.  

The adjusted R² penalizes the R² score for adding independent variables that do not significantly improve the model's explanatory power, making it a more reliable metric for model selection.  

---

## 🔑 Key Features  
- **Simple API**: A single, intuitive function for easy integration.  
- **Lightweight**: Built on NumPy for high performance with minimal overhead.  
- **Fully Tested**: 100% test coverage with pytest ensures reliability and correctness.  
- **Open Source**: Freely available under the MIT License.  

---

## 📦 Installation  

Install the package from the Python Package Index (PyPI) using pip:  

```bash
pip install adjusted_r2_score
```

## How to Use

The library is straightforward to use. Import the function, provide your data, and get the score.
```bash
from adjusted_r2_score import adjusted_r2_score

# 1. Define your data
y_true = [3, -0.5, 2, 7]      # The actual, ground-truth values
y_pred = [2.5, 0.0, 2, 8]      # The values predicted by your model
n_features = 2                 # The number of features (predictors) in your model

# 2. Calculate the score
score = adjusted_r2_score(y_true, y_pred, n_features)

# 3. Print the result
print(f"Adjusted R-squared Score: {score}")
# Expected output: Adjusted R-squared Score: 0.9166666666666666
```
## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/dhyeymakwana/adjusted_r2_score/issues) to see if you can help out.



