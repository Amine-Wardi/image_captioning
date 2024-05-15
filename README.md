This project is part of the Computer Vision course done at ENSEIRB-MATMECA's AI option.

The goal of this project is to generate captions that describe an image. We tried to solve this problem with two methods :

- The use of a CNN to extract the images features, in our case we used YoloV8. Then, generating text by using an LSTM
- The use of Transformers

We chose to use Flickr8K dataset, you can dowload it from here : https://www.kaggle.com/datasets/adityajn105/flickr8k

The two methods are coded each sepratly in their own jupyter notebooks (`yolo_lstm.ipynb` and `attention.ipynb`).

The report can also be found under the name `report.pdf`, it explains all the steps we took during this project and also shows our results.
