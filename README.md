## ML_ex3 - "3.2.3: Next-word prediction (Language Modelling) using Deep Learning"

### DATA - "Reuters-21578" - http://www.daviddlewis.com/resources/testcollections/reuters21578/
The data was originally collected and labeled by Carnegie Group, Inc. and Reuters, Ltd. in the course of developing the CONSTRUE text categorization system. 


Each of the used different hardware setup, however all model training scenario (12) and prediction (12) were executed on different machines.
We also reconfirmed that tensoflow is - by default - primarily using GPU intensive calculations, so we also leveraged GoogleColab (with available GPU resources) for building the code. For documentation purpose we documented our code in JupyterNotbooks in transparent way.
Key packages: "tensorflow", "keras", "nltk", "numpy", "pickle", "string", "heapq", "bs4", "os", "matplotlib".

 - 1.) Single layer model trained using LSTM32 with 20 epochs (Single_layer_LSTM32_20epochs.ipynb)
 - 2.) Single layer model trained using LSTM64 with 20 epochs (LSTM64.ipynb),
 - 3.) Single layer model trained using LSTM128 with 20 epochs (Single_layer_LSTM128_20epochs.ipynb), 
 - 4.) Single layer model trained using LSTM32 with 32 epochs (Single_layer_LSTM32_32epochs.ipynb), 
 - 5.) Multi layer model trained using LSTM32 with 20 epochs (Multi_Layer_LSTM32_20epochs.ipynb), 
 - 6.) Multi-layer model using LSTM64 with 20 epochs (MultiLayer_LSTM64_20epochs.ipynb), 
