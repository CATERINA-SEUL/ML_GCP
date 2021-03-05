#### 1. Which model is appropriate for a plain stack of layers ?

A : Sequential

#### 2. How does Adam (optimization algorithm) help in compiling the Keras model?

A : Both A and B

    By updating network weights iteratively based on training data.
    By diagonal rescaling of the gradients.

#### 3. The predict function in the tf.keras API returns what?

A : Numpy array(s) of predictions

#### 4. What are the parameters involved while compiling the Keras model?

A : All of the above

    Optimizer
    Loss function
    Evaluation metrics

#### 5. What is the significance of the Fit method while training a Keras model ?

A : Defines the number of epochs

#### 6. What are the weaknesses of the Keras Functional API?

A : Both A and B

    It doesn't support dynamic architectures.  The Functional API treats models as DAGs of layers.  This is true for most deep learning architectures, but not all: for instance, recursive networks or Tree RNNs do not follow this assumption and cannot be implemented in the Functional API.  
    Sometimes we have to write from scratch and need to build subclasses.  When writing advanced achitectures, you may want to do things that are outside the scope of “defining a DAG of layers”: for instance, you may want to expose multiple custom training and inference methods on your model instance. This requires subclassing.  