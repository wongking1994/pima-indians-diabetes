Author: Dilan Fernando <dilan.fd@gmail.com>
Source: Machine Learning Mastery.

In here I am documenting the various steps involved in the typical modeling
of a data problem using Deep Learning. See the attached jupyter-notebook for
details.


## Steps involved:

1. Download the datesets and meta data.

   i. Download dataset.
	   ```
	 $  wget http://archive.ics.uci.edu/ml/machine-learning-databases/pima-indians-diabetes/pima-indians-diabetes.data
	   ```
   ii. Download metadata to get an understanding of the structure of the data.
	   ```
	 $  wget http://archive.ics.uci.edu/ml/machine-learning-databases/pima-indians-diabetes/pima-indians-diabetes.names
	   ```
2. Inspect data and rename accordingly.

3. Load data set into `jupyternotebook` and proceed as usual.
   ```python
		dataset = np.loadtxt('pima-indians.csv', delimeter=',')
   ```
4. Proceed with the Keras model.
