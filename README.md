# Neural-Style-Transfer-using-Pytorch

![Alt text](images/styled_img.jpg?raw=true "Title")

Neural Style transfer is an optimization technique used to take a content and a style image and blend them together so the output image looks like the content image but painted in the style of the style image. 
In this project, an artistic style image is created using content and given style image. 
The content and style loss function are also calculated in this regard. These loss functions are minimized using optimization techniques to get an artistic style image that retains content features and style features.

The key tasks in this project are:

- Load pretrained VGG-19 model.
- Extract content and style features.
- Create style and content loss function.
- Minimize the total loss to generate artistic style image.
