# Image-Classification-CNN
Image classification based on pre-packaged MNIST and CIFAR dataset using CNN  

1. The MNIST data set contains handwritten single digits from 0 to 9 (grayscale image)  

    For the labels we’ll use One-Hot Encoding.  
    This means that instead of having labels such as “One”, “Two”, etc… we’ll have a single array for each image.  

    The label is represented  based off the index position in the label array.   
    The corresponding label will be a 1 at the index location and zero everywhere else.  
    For example, 4 would have this label array:  
    [0,0,0,0,1,0,0,0,0,0]   

2. CIFAR-10 dataset are 32by32 images of 10 different objects:  
Airplane,Car,Bird,Cat,Deer,Dog,Frog, Horse,Ship,Truck  
These are color images!  



