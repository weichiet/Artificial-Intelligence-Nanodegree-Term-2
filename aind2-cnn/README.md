# Convolutional Neural Networks

### List of Tutorials
1. [Train an MLP to classify images from the MNIST database.](./mnist-mlp)  
2. [Train a CNN to classify images from the CIFAR-10 database.](./cifar10-classification)
3. [Visualize four activation maps in a CNN layer.](./conv-visualization)
4. [Train a CNN on augmented images from the CIFAR-10 database.](./cifar10-augmentation)
5. [Use transfer learning to train a CNN to classify dog breeds.](./transfer-learning)  

### Instructions

1. Clone the repository and navigate to the downloaded folder.

	```
		git clone https://github.com/udacity/aind2-cnn.git
		cd aind2-cnn
	```

2. Obtain the necessary Python packages, and switch Keras backend to Tensorflow.  	

	For __Mac/OSX__:
	```
		conda env create -f requirements/aind-dog-mac.yml
		source activate aind-dog
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	For __Linux__:
	```
		conda env create -f requirements/aind-dog-linux.yml
		source activate aind-dog
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	For __Windows__:
	```
		conda env create -f requirements/aind-dog-windows.yml
		activate aind-dog
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
	```

3. Enjoy!
