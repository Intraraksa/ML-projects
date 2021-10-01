# Background

As Production engineer in manufacturing. I have routine job to evaluate how defect of production is going?
There are versatile defects in production process. And there are many methods to validate parts quality such as measure tool or machine detection also know as POKAYOKE.
The computer vision become more popular in the past decade but they are not quite relevance to deep learning because manufacturer's behavior.

Naturally, Manufacturers produce goods by putting raw material on matufacturing tools also known as [Jig&Fixtures.](https://en.wikipedia.org/wiki/Fixture_(tool)).
Fixtures will hold the raw material consistently. So, the computer vision in manufacturing is just memorization images pixel.

In this project come from [Kaggle](https://www.kaggle.com/satishpaladi11/mechanic-component-images-normal-defected) 
It provide 3 type of images
1. Defect type 1
2. Defect type 2
3. OK parts

# Method

These images are mechanical parts. They contain in subfolder

![folder1.jpg](https://i.postimg.cc/PqVRbc54/folder1.jpg)

Deep learning architecture was created with Resnet19 for extract feature and train the model by feeding the images to model layers subsequently


