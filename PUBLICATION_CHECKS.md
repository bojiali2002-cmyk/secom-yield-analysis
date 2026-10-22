# Publication preparation checks

- secom-yield-analysis: Python syntax, Notebook JSON structure, code-cell compilation and saved-error checks passed
- secom-yield-analysis: common token/private-key/local-home-path patterns not found (heuristic scan, not a security guarantee)
- secom-yield-analysis: relative Markdown links resolve
- SECOM: 1567 OOF rows, 104 failures; Random Forest top 314 captures 53; XGBoost AP recomputed as 0.17813060833903357

## Limits

- No full CNN retraining or full SECOM model refit was performed.
- No fresh pip installation or cross-platform environment validation was performed.
- No scientific claim of prospective validation or deployment is made.
- PyTorch forward execution was not run: PyTorch and scikit-learn are absent from this packaging runtime; metric recomputation uses NumPy definitions.

These checks validate packaging and saved artifacts, not new model training. Original desktop project files were not edited.
