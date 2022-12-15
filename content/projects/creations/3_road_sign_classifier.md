{
    "title":"Python ML: TensorFlow Road Sign Classifier",
    "link":"https://github.com/greent3/Harvards_AI_Programming_W_Python/blob/main/Chapter_5_Neural_Networks/traffic/traffic/traffic.py",
    "image":"img/roadsign.jfif",
    "description":"I used TensorFlow and the German Traffic Sign Recognition Benchmark (GTSRB) dataset to build a neural network that effectively classifies images of road signs.",
    "tags":[
          "Python",
          "TensorFlow",
          "Classification",
          "Computer Vision"
        ],
    "featured": true
}


As research continues in the development of self-driving cars, one of the key challenges is allowing these cars to develop an understanding of their environment from digital images.

In my traffic-sign classification project, I used TensorFlow and the German Traffic Sign Recognition Benchmark dataset to build a neural network that puts images of road signs into different classifications.

My role consisted of loading the data (images) into the program, resizing the images, and designing/implementing the neural network.
For the neural network, I used the following layer structure:

Conv2D layer with 3x3 kernel -> 2x2 Max pooling layer -> Conv2D layer with 3x3 kernel -> Flattening layer -> Relu Activation function -> Dropout -> Softmax
