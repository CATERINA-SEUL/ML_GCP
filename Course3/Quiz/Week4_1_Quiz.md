#### 1. Select the correct statement regarding the Keras Functional API.

A : Unlike the Keras Sequential API, we have to provide the shape of the input to the model.  

#### 2. The Keras Functional API can be characterized by having: 

A : Multiple inputs and outputs and models with shared layers. 

#### 3. Select the correct statement regarding the Keras Sequential and Functional API's.

A : The core data structure of Keras is a model, which let us organize and design layers. Sequential and Functional are two ways to build Keras models.  The Sequential model is the simplest type of model (a linear stock of layers). If we need to build arbitrary graphs of layers, the Keras Functional API can do that for us.  

#### 4. Which of the following is correct regarding the Keras Functional API?

A : The input layer needs to have shape (p,) where p is the number of columns in your training matrix.  For example:

    inputs = Input(shape=(3,))  