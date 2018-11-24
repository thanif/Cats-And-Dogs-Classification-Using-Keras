# Cats-And-Dogs-Classification-Using-Keras
The dataset used is a modified version of the original cats and dogs dataset obtained from 

https://drive.google.com/file/d/1fk-rBgurmtJGkgpmdk0QbVB2iZe8fWl9/view?usp=sharing

# Goal
The goal was to achieve maximum accuracy while using only a maximum of 5 convolution layers.

# Results
Model 15 with test accuracy of 0.897 is the best among the models employed using rescaling, shear, zoom and horizontal flip for data generation with a batch size of 256 using 15000 training examples while 5000 each for validation and test purposes and the results are achieved after training for 100 epochs using binary crossentropy as loss and accuracy as the metric with 5 convolution layers with 64, 64, 128, 128, 256 filters of 3x3 each, three dense layers with 256, 256 and 1 neuron respectively, dropout of 0.5 and rmsprop as the optimizer.
