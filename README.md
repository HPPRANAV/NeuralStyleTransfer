Project Overview

In this project, we aim to apply neural style transfer techniques to clothing images, allowing users to experiment with different styles and apply them to various types of clothing. 
By leveraging neural networks and style transfer algorithms, we can transform mundane clothing images into unique and eye-catching pieces of art. 

Data: 
The original images are present in the folder "original"
The masks of the clothing for each image are present in the folder "all masks"
The masks of the chosen images after performing style transfer are present in the folder "result_masks"
The final blended images showcasing the clothing style transfer are present in the folder "blended images"   

Created Dataset : 
The dataset that is created is the resultant images generated by the style transfer model. The dataset consists of 223 images, present in the "blended_images" folder. 

Code: 

The clothes_mask.ipynb file is the code related to creating the isolated mask images, as well as final concatenation of the style transferred mask images onto the original images . 
The model.py contains the code for the actual neural style transfer process. 
In the main function, the weights can be tweaked and experimented with for different resultant images. 
The directories to the style and content images can be changed within the main function to test the style transfer for different images. 
