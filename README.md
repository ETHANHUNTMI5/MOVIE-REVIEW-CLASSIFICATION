# Movie-Review-Classification

Sentiment Analysis problem using Neural Network.
-IMDB dataset which has 50000 reviews.
- output positive or negative.
- hence a Binary Classification problem.

1. Data Preparation
- splitting the data into train and test
- restricting the vocab to 10000 words

2. Vectorize the data
- Vocab size is fixed to 10000
- Each input review converted into vector of length 100000

3. Defining the Model Architecture
- RELU ACTIVATION
- 2 HIDDEN LAYERS WITH 16 UNITS EACH
- 1 OUTPUT LAYER WITH 1 UNIT(SIGMOID ACTIVATION)

4. Training and Validation
- Avoiding overfitting
- Splitting train into train and validation set
- using early stopping
