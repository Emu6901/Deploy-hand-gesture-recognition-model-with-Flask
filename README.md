# Deploy hand gesture recognition model with Flask
This is an API when client send an base64 image to the server. The server will respond an data = {'Class Name': prediction, 'Percent': percent*100} where percent is accuracy of the prediction.
## Model
You can find the dataset and model at this notebook: https://www.kaggle.com/minhhngchong/hand-classification-9-classes-more-data-18

## How to start
```sh
$ pip install requirements.txt
$ py server.py
```
## Test model
If you just want to test the model, you can use Test model.ipynb