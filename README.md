# Data Scientist Project

Project code for Udacity's Data Scientist Nanodegree program. In this project, you will first develop code for an image classifier built with PyTorch, then you will convert it into a command line application.

In order to complete this project, you will need to use the GPU enabled workspaces within the classroom.  The files are all available here for your convenience, but running on your local CPU will likely not work well.

You should also only enable the GPU when you need it. If you are not using the GPU, please disable it so you do not run out of time!

### Data

The data for this project is quite large - in fact, it is so large you cannot upload it onto Github.  If you would like the data for this project, you will want download it from the workspace in the classroom.  Though actually completing the project is likely not possible on your local unless you have a GPU.  You will be training using 102 different types of flowers, where there ~20 images per flower to train on.  Then you will use your trained classifier to see if you can predict the type for new images of the flowers.

you can download data set by writing these commands
```
!wget -c https://s3.amazonaws.com/content.udacity-data.com/courses/nd188/flower_data.zip
!unzip -qq flower_data.zip;
```


references:
http://howieko.com/projects/classifying_flowers_pytorch/
https://medium.com/@josh_2774/deep-learning-with-pytorch-9574e74d17ad
https://medium.com/udacity/implementing-an-image-classifier-with-pytorch-part-1-cf5444b8e9c9
https://www.freecodecamp.org/news/how-to-build-an-image-classifier-with-greater-than-97-accuracy-3c72010b3d55/
