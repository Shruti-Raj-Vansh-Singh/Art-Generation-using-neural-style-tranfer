# Art-Generation-using-neural-style-tranfer

Neural style transfer can be used to generate an output image that is based on the stuff showed in, what we call, the content image but has the styling and feel of the style image. 
#### You can now know how would it look if Leonardo Di Vinci had made your painting instead of Mona Lisa!

This technique basically exploits the way in which layers at different depths of a CNN extract features. The initial layers look at simpler features like edges, or maybe colors, etc and as we go deeper into the network, the layers try to look at more complex features like texture, shapes and maybe complete objects too. So we can say that the initial layers give us the style and the later ones give us the content of the image and that is exactly we actually need!!

 
Now how to know if the generated image has the content of the content image(for example your face) and the style of the style image(Mona Lisa Painting)?? For this we will use the loss function. But since we the features extracted from the content image are different from the feature of the style image, we will need two Loss functions : Content Loss Function and Style Loss Function.
