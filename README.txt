# Flask Image Classification

This repo comprises of ShuffleNet & MobileNet python file from scratch on cifar10 and then using Flask for Model serving.


## Model Serving on Flask.

- Run the Model

- Go to the command prompt and type the path of for the python file (python shufflenet.py/python mobilenet.py)

- It will redirect you to the path http://127.0.0.1:5000/.

- Add the get_prediction command to it in the url.(e-g-http://127.0.0.1:5000/get_prediction?url=https://www.hp-lexicon.org/wp-content/uploads/2015/05/amphibian-animal-frog-200x0-c-default.png)

- It will return the result in the form of json.

- Choose high quality images for better Accuracy.

Pretrained Model for Deployment:

Consists of app.py,label_image,static

-Go to the command prompt and type the path of for the python file.

-Upload the file from local system(Image selection from Local computer).

-Predict the output.

 
