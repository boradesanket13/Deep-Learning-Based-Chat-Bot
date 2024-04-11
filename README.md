# Deep-Learning-Based-Chat-Bot

### Dependancies
- numpy
- tensorflow
- scikit-learn
  
 ` pip install numpy tensorflow scikit-learn  `

### Step 1: Training Data

### Step 2: Data Preprocessing
- Label Encoding
- Tokenisation
- Padding

### Step 3: Building and Training the Chatbot Model
#### Layers:

1. Embedding Layer: Maps the input sequence of integers to a dense vector representation.

2. Flaten Layer: Convert the multi-dimensional output of the Embedding layer into a one-dimensional vector

3. Dense layer with ReLU activation: Introduces non-linearity to the model, allowing it to learn complex patterns in the data.

4. Output Layer with Softmax Activation Function: Produces probability scores for each class label

#### Compile the model using

1. Adam optimizer
2. Sparse categorical crossentropy loss function

#### Training model using fit method with following parameters

1. input sequences
2. encoded labels
3. epochs

### Step 4: Generating Responses
predicted label is then converted back into its original text form using the  `inverse_transform ` method of the LabelEncoder


