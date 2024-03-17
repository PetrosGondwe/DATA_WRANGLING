CREATING A DATASET FOR EYE DISEASE DETECTION (COMPUTER VISION) 

The eye disease problem is under image classification which identifies if a person has some eye problems which are jaundice, eczema and conjunctivitis classifies the disease in the  photo accordingly. This dataset will contain images to train a model to achieve the task of classifying those images.

Firstly, we downloaded images using a library called Bing_image_downloader which scraps images from the web. 
The images where then processed using another library known as Tensorflow.keras. this library created a prefetch dataset(dataset created by automatically by tensorflow.keras that can be fed into a model) from a directory that assigned integer class labels, standard color mode which is RGB and resized the images to 255 x 255 pixels. 

We applied one-hot encoding which involves changing categorical data into vector representations, so we turned the class labels of the images into their respective vector representations. 

We used tensorflow.one_hot function.
We also applied normalization where we standardized the pixels to a range of 0 to 1. We as well used  tensorflow library.

One of the challenges we faced had to do with saving the preprocessed images which were in prefetched dataset.




