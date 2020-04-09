# TehranAQI_Keras
The goal of this repository is to predict Tehran's **AQI** (**A**ir **Q**uality **I**ndex), using a RNN model implemented in Python-Keras.

By choosing a hard baseline, i.e. predicting the next AQI equal to current AQI, I compared two models: an **MLP** model and a recurrent model based on **GRU**(**G**ated **R**ecurrent **U**nit) layer. The results shows that the recurrent model surpasses the MLP model, and even performs better than such a hard baseline, i.e predicting value at _t+1_ by value of _t_.
