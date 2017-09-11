# Deep Neural Networks

### Student Admissions in Keras
File: ` Student_Admissions.ipynb`   
Data: `student_data.csv`

Predicting  student admissions to graduate school at UCLA based on three pieces of data:  
* GRE Scores (Test)
* GPA Scores (Grades)
* Class rank (1-4)

### Using Keras to Analyze IMDB Movie Data
File: `IMDB_in_Keras.ipynb`  
Data:  More info available at [Keras](https://keras.io/datasets) website

Analyzing a dataset from IMDB and use it to predict the sentiment analysis of a review.

### Instructions

1. Clone the repository and navigate to the downloaded folder.

	```
		git clone https://github.com/udacity/aind2-dl.git
		cd aind2-dl
	```

2. Obtain the necessary Python packages, and switch Keras backend to Tensorflow.  

	For __Mac/OSX__ or __Linux__:
	```
		conda env create -f requirements/aind-dl-mac-linux.yml
		source activate aind-dl
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	For __Windows__:
	```
		conda env create -f requirements/aind-dl-windows.yml
		activate aind-dl
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
	```

3. Enjoy!
