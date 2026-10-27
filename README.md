# End-to-End Predictive Maintenance Pipeline

A PySpark notebook that processes NASA C-MAPSS FD001 turbofan sensor data through Bronze, Silver, and Gold layers, then trains and evaluates a remaining useful life (RUL) regression model.

## Contents

- `Assignment1_PredictiveMaintenance.ipynb`: the complete lab workflow and results.
- `data/CMAPSSData/`: raw FD001 training, test, and RUL files.
- `lab5_outputs/`: saved Parquet layers and the selected Spark ML pipeline.

## Run

Open the notebook with the repository root as the working directory. It uses relative paths for `data/CMAPSSData` and `lab5_outputs`. The notebook calls for Java 17+, PySpark 3.4+ (tested with 4.2), NumPy, pandas, PyArrow, and Matplotlib. Run its cells in order; generated output directories may be replaced as it runs.
