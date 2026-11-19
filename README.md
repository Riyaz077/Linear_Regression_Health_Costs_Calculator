# Linear Regression Health Costs Calculator

A TensorFlow/Keras regression notebook for the freeCodeCamp Machine Learning challenge.

## Files
- `fcc_predict_health_costs_with_regression.ipynb` — complete notebook.
- `README.md` — setup and execution instructions.

## Run in Google Colab
1. Upload/open the notebook in Google Colab.
2. Select **Runtime → Run all**.
3. Allow the notebook to download `insurance.csv`.
4. Check the reported **Test Mean Absolute Error**. The freeCodeCamp requirement is below `$3,500`.
5. Run the official test cell from the original freeCodeCamp challenge notebook before submitting.

## Run locally in VS Code (Windows)
Open a terminal in this folder and run:

```powershell
py -3.11 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install tensorflow pandas numpy scikit-learn matplotlib ipykernel
```

Then open the `.ipynb` file in VS Code, select the `.venv` Python kernel, and choose **Run All**.

If PowerShell blocks virtual-environment activation, use Command Prompt instead:

```cmd
.venv\Scripts\activate.bat
```

## Important
This notebook is a ready-to-run implementation, but it has not been executed against the official freeCodeCamp test in this environment. Training results can vary with library versions and the dataset split. Do not submit until you have run the original challenge's final test cell and confirmed it passes.
