# ObjectCOUNTER
Counting objects in an image is a task of computer vision. There are many computer vision libraries that you can use for this task, such as OpenCV, 
TensorFlow, PyTorch, Scikit-image, and cvlib. You must have not heard much about the cvlib library in Python. Well, this is a very simple, high level, 
and easy to use computer vision library in Python.

By using the features of this library we can count the number of objects in an image using Python. To use this library, make sure you have OpenCV
and TensorFlow installed in your systems. You can easily install it by using the pip command; pip install cvlib.


Now let’s see how to use the cvlib library to count the number of objects in an image using the Python programming language. 
I will first read an image by using the OpenCV library, then I will detect all the objects using cvlib and count the number of particular objects.
The image that I am going to use for this task is shown below.

![cars](https://user-images.githubusercontent.com/104202659/204874670-711a0f8b-c306-4630-8afa-25ab35104ba6.jpeg)


As you can see the image that I am using here for the task of counting objects in an image using Python contains vehicles in it. 
So I will first detect all the vehicles and then count the number of cars out of them.
