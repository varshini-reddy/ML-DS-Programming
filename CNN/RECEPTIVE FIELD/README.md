The aim of this lab is to visualize the receptive field of each pixel of a selected activation map. For each pixel of the selected activation map, we first find the image that activates that pixel the most. Then we compute the receptive field of that pixel wrt the corresponding input image and visualize it.



## Instructions:

- Define the model based on the architecture mentioned in the scaffold.

- Load the pre-trained weights from the receptive_field_weights.h5 file.

- Load all the images in the cifar folder provided using the load_image function.

- Select a convolution layer and an activation map within it to visualize the receptive field of each pixel of the activation map.

- Find out by running all the images through the defined CNN model which image activates a pixel in the selected activation map the most.

- Save this pixel-wise image information in the best_img dictionary.

- Use the helper class provided to compute the size and position of the receptive field for a given layer.

- Visualize the receptive field based on the best_img dictionary for each pixel in the activation map.



## Hints:

keras.Sequential() 


Creates a sequential model. A Sequential model is appropriate for a plain stack of layers where each layer has exactly one input tensor and one output tensor.

keras.compile()


Configures the model for training.

tf.keras.layers.Flatten()

Flattens the input. Does not affect the batch size.

tf.keras.layers.Conv2D()


2D convolution layer (e.g. spatial convolution over images).

tf.keras.layers.Dense()


A regular densely-connected NN layer.

model.load_weights(file_name)

Loads the pre-trained weights from the file.



## NOTE 

In this lab, we are using the word activation map and feature map synonymously. 