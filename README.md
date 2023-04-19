# NN_lecture
There are two assignments:
1) Predict the classes for the fashion data set
2) Predict the position of the planets as a function of time for the dataset that can be downloaded at the following link:
https://www.dropbox.com/s/uahmj0rr37629jd/planets_trajectories.npz?dl=0
you can load the data set with the following line:
 data = np.load('planets_trajectories.npz')

The data set has the orbits of 4 planets each time step is 1e-4 years and the position coordinate is given in A.U.

In doing these projects you may want to consider topics such as:
- Using a validation set in addition to the test set (see https://www.tensorflow.org/guide/keras/train_and_evaluate)
- Hyperparameters: regularization, learning rate, etc. 
- Neural Net architecture (convolution layers, etc.), preprocessing, descriptors

link to fashion dataset:
https://www.dropbox.com/sh/wannefe9ajteihd/AABb6AXca5pGVFidHUUvahQda?dl=0
to read the dataset:
import idx2numpy #pip install idx2numpy
X_train = idx2numpy.convert_from_file('fashion MNIST/train-images-idx3-ubyte')
y_train = idx2numpy.convert_from_file('fashion MNIST/train-labels-idx1-ubyte')
X_test = idx2numpy.convert_from_file('fashion MNIST/t10k-images-idx3-ubyte')
y_test = idx2numpy.convert_from_file('fashion MNIST/t10k-labels-idx1-ubyte')
