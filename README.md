# Mask-R-CNN-is-an-object-detection-model-based-on-CNN-on
Wildlife Animals Identification

## Overview of the Mask_RCNN Project

* The Mask_RCNN project is open-source and available on GitHub under the MIT license, which allows anyone to use, modify, or distribute the code for free.

* The contribution of this project is the support of the Mask R-CNN object detection model in TensorFlow ≥ 1.0 by building all the layers in the Mask R-CNN model, and offering a simple API to train and test it.

* The Mask R-CNN model predicts the class label, bounding box, and mask for the objects in an image. Here is an example of what the model could detect.

![image](https://user-images.githubusercontent.com/53464755/178788050-823433c1-eeb1-4fb5-afc4-d30d72a28c49.png)

* The first release of the project (Mask_RCNN 1.0) was published on November 3rd, 2017. The latest release (Mask_RCNN 2.1) was published on March 20th, 2019. Since this date, no new releases were published.

# Environment setup:

1.Install Anaconda:

 https://www.anaconda.com/download/
 
2.Creating an environment with commands

   * To create an environment:
   
           conda create --name myenv
     
     !Note:
     Replace myenv with the environment name.
   
   * When conda asks you to proceed, type y:
   
           proceed ([y]/n)?
           
     This creates the myenv environment in /envs/. No packages will be installed in this environment.

   
       
3.Activating an environment
 
  * To activate an environment:
       
           conda activate myenv
       
       !Note:
Replace myenv with the environment name or or directory path.

4.Install Python packages

    * Tensorflow==1.13.1
    * Keras==2.2.5
    * h5py==2.10.0
    * mrcnn
    * EEL
   
 Install the required packages by executing the following command.

       pip install (package name)
   
       example:
 
           $ pip install numpy
           
   Make sure pip is linked to Python
   
   Using Python virtual environment is highly recommended.

## Help

If you are facing any difficulty, feel free to create a new issue or reach out on [Linkedin](https://www.linkedin.com/in/karthik-v-926656211/)
