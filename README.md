# Network RTT Prediction with Random Forest

This project collects ping data (Round-Trip Time and packet loss) from a set of specified hosts and trains a Random Forest Regressor model to predict RTT.

## Project Structure

*   **`collecting_data.ipynb`:**  Jupyter Notebook containing the code to collect ping data from multiple hosts and save it to a CSV file.
*   **`train.ipynb`:** Jupyter Notebook containing the code to load the ping data, perform data analysis, train a Random Forest model, and evaluate its performance.
*   **`raw_ping_data.csv`:** (Example) CSV file containing the collected ping data. *Note: This file will be generated when you run `collecting_data.ipynb`.*  You may choose to *not* include this in your Git repository if it gets very large.
* **`plot1.png`:** A plot generated from the `train.ipynb` notebook, containing visualization on data.
* **`plot2.png`:** A plot generated from the `train.ipynb` notebook, showing the performance of the model.
*   **`rtt_model.joblib`:** (Optional) The saved Random Forest model. You might choose *not* to include this in your Git repository, depending on its size and whether you want to share the trained model.

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
