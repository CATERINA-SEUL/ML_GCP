#### 1. What operations can be performed on tensors?

A : Both A and B

    They can be reshaped
    They can be sliced

#### 2. Which is an example of a rank 2 tensor?

A : Shape:  [3,4]

#### 3. Which of the following is true when we compute a loss gradient?

A : All of the above

    TensorFlow records all operations executed inside the context of a tf.GradientTape onto a tape.
    It uses tape and the gradients associated with each recorded operation to compute the gradients.
    The computed gradient of a recorded computation will be used in reverse mode differentiation.

#### 4. Which of the following produces tensors that can be modified?

A : tf.Variable

#### 5. What is the significance of tf.Variable()?

A : A tf.Variable represents a tensor whose value can be changed by running ops on it. Specific ops allow you to read and modify the values of this tensor. Higher level libraries like tf.keras use tf.Variable to store model parameters.  