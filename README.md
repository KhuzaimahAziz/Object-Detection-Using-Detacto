# Using Detacto for Object Detection

## Library and Models Used:

I used Detacto Libray of Python that contains pretrained object detection models.
1. I annotated my images on makesense
2. Then I Used Fast-R-CNN model which is the default model in Detacto library.
3. The reason I used this is because  Detacto provides a high-level API that makes it easy to train and evaluate object detection models, without requiring extensive knowledge of deep learning or computer vision also it is built on top of PyTorch, which is a powerful deep learning library. As a result, Detacto models can achieve state-of-the-art performance on various object detection benchmarks.

## CPU VS GPU:

Firstly I trained this model on my own personal CPU, there were only 15 images but it took around 30-40 mins to train where as when I trained it on colab's GPU it took only 5 minutes to train on 20 images.

## Applying it on videos:
To apply an object detection model that has been trained on images to a video, we need to perform object detection on each frame of the video individually. This can be done using the same techniques used for image detection
