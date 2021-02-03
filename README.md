# Weather_forcasting
Now the code is completly functional you can upload the file into you board and make inferences. The model will capture pressure, humidity, temperature using the builtin sensor embedded on the nano 33 BLE sense. The inferences are made using the EloquentTinyML library which is an awesome tool to easly run prediction with a model. It uses tensorflow lite micro header c++ files.

The model is located in /TinyML_weather/include.
The model was built with python, google colab and tensorflow, using kaggle dataset. Then the model has been converted in tensorflow lite model and later in tensorflow lite micro model. (There are 2 methods to convert a model both are shown in the .ipynb).
