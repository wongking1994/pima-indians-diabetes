Author: Dilan Fernando <dilan.fd@gmail.com>

In here I am documenting the various steps involved with the typical modeling
of a data problem using Deep Learning. See the attached jupyter-notebook for
details.


## Steps involved:

1. Download the datesets and meta data.
   i. Download dataset.
	   ```bash
	 $  wget http://archive.ics.uci.edu/ml/machine-learning-databases/pima-indians-diabetes/pima-indians-diabetes.data
	   ```
   ii. Download metadata to get an understanding of the structure of the data.
	   ```bash
	 $  wget http://archive.ics.uci.edu/ml/machine-learning-databases/pima-indians-diabetes/pima-indians-diabetes.names
	   ```
2. Inspect data and rename accordingly.

3. Load data set into `jupyternotebook` and proceed as usual.
   ```python
		dataset = np.loadtxt('pima-indians.csv', delimeter=',')
   ```
4. Proceed with the Keras model.
