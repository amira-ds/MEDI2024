# Comparative Analysis of Multivariate Time Series Forecasting Methods for Modeling Plastic Extruder Behavior

## Description:
We will provide experimental datasets due to the lack of public data in the plastics field. 
As part of the \recyplast project, we developed a data acquisition protocol to study how extruder settings evolve over time when processing virgin and recycled polypropylene (PP). 
The tests involved PP30, PP40, and PP89, both individually and in mixtures, selected for their chemical resistance and heat tolerance. 
We then applied four forecasting models—Vector Autoregression (VAR), Multiple Linear Regression (MLR), Facebook Prophet, and Long Short-Term Memory (LSTM)—to these datasets and evaluated their forecasting capabilities. After applying these models, we compared their performance in modeling the behavior of the extruder.
![extruder icam](https://github.com/user-attachments/assets/2525dd45-a460-4b9f-9837-085a9366c7b4)
## Requirements ( !pip install library_name OR import library_name)
- Python 3.x
- Pandas Library
- Numpy Library
- Matplotlib and Seaborn Libraries
- Scikit-learn Library
- Prophet Library
- Tensorflow Library
- statsmodels Library

## Files Provided
- **Datasets**: Available in the `CSV FILES/` zip folder, containing the `.cvf` files.
- **Notebooks**: Colab notebooks for each forecasting model are available in the `notebooks/` folder.
  - `VAR_model.ipynb` (Vector Autoregression)
  - `MLR_model.ipynb` (Multiple Linear Regression)
  - `Prophet_model.ipynb` (Facebook Prophet)
  - `LSTM_model.ipynb` (Long Short-Term Memory)
## Usage:
- For example, to run the LSTM model:
  -  `LSTM_model.ipynb` in `Google Colab`.
  -  Upload the required `.cvf` file using the upload cell in `Colab`.
  -  Run the remaining cells to preprocess the data and apply the LSTM model.
