# Trashnet Classifier using Fastai

`trashnet-classifier.ipynb ` has trained model result.


Trashnet dataset trained on Resnet34/50 architecture using transfer learning.

This model was able to achieve 90.2% accuracy with ResNet34 and 94.5% accuracy with ResNet50.

Data can be found at [Trashnet Repo](https://github.com/garythung/trashnet).

[App demonstration](https://garbage-recognizer.onrender.com)


## Docker setup
`docker build -t trashnet-classifier . && docker run --rm -it -p 5000:5000 trashnet-classifier`

Local server will be running at http://localhost:5000 to test.