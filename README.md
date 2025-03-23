# Network RTT Prediction with Random Forest

This project collects ping data (Round-Trip Time and packet loss) from a set of specified hosts and trains a Random Forest Regressor model to predict RTT.

## Project Structure

*   **`collecting_data.ipynb`:**  Jupyter Notebook containing the code to collect ping data from multiple hosts and save it to a CSV file.
*   **`train.ipynb`:** Jupyter Notebook containing the code to load the ping data, perform data analysis, train a Random Forest model, and evaluate its performance.

## Requirements

*   Python 3.7+
*   `ping3`
*   `pandas`
*   `scikit-learn`
*   `matplotlib`
*   `seaborn`
*   `joblib`
*   `jupyter` (if you want to run the notebooks)
*   `nbstripout` (highly recommended for managing notebook output in Git)

You can install the required packages using `pip`:

```bash
pip install ping3 pandas scikit-learn matplotlib seaborn joblib jupyter nbstripout
