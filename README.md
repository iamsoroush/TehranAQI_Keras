# Predicting Tehran's AQI
The goal of this repository is to predict Tehran's **AQI** (**A**ir **Q**uality **I**ndex), using a RNN model implemented in Python-Keras.

By choosing a hard baseline, i.e. predicting the next AQI equal to current AQI, I compared two models:
1.an **MLP** model and
2.a recurrent model based on **GRU**(**G**ated **R**ecurrent **U**nit) layer.


# Results
The results shows that the recurrent model surpasses the MLP model, and even performs better than such a hard baseline, i.e predicting value at _t+1_ by value of _t_.

Model | MAE training loss | MAE validation loss
--- | --- | ---
Baseline | - | 0.721
MLP | **0.316** | 0.872
RNN (GRU) | 0.599 | **0.617**


You can re-generate the results by guidelines presented in the [provided notebook](https://github.com/iamsoroush/TehranAQI_Keras/blob/master/tehranaqi.ipynb).
