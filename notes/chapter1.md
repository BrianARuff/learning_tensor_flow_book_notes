# Introduction to AI and ML

### Machine Learning has 4 elements to its process.

1. supervised
2. unsupervised
3. semisupervised
4. reinforcement

#### Supervised

- the most common form of machine learning
- there is an answer key for the question
- example, if you draw an image and place it over another image and compare the similarity of the two,
  then you can mathematically formulate an estimate on what the image actually is.

#### Unsupervised Learning

- No answer key, only questions.
  ideal, and partical
- what a machine could learn and report form unlabedled data.
- general recognition
- used for categorizing large amounts of data

#### Semisupervised Learning

- some labels for the question
- research on fire with semisupervised breakthroghs
- generative networks
  - trained on what we want the network to create
  - songs, news articles, music, etc..., good for creatives!

#### Reinforcement Learning

- chess moves (is a move good or bad?)
- the answer depends on the results
- often combined with other learning types for optimization

## Information Overload

- Supervisied learning concepts
  - image categorization
  - natural language processing (NLP)
  - image sementation

#### A tour of what a framework provides

- A human writes the code and a computer reads and interpets that code or some variation of it. No algorithm is written, the algorithm comes from the training data.
- A human writes the algorthm's ratiner, assisted by a framework in most cases, a human outlines the paramters of the problem, the desired structure, and the location of the data to learn from. The machine then runes the program-traning program which improves with time until you reach a point of satisfaction! The resulting algorithm is simply a collection of numbers. That collection and its graph is often called a `model`.
- Tensorflow handles the api for specifying the structure or artchtecture of the model, loading data, passing data through our machine learning process, and ultimately tuning the machine to be better at predicting answers to the given input the next time. All we have to worry about is fine tuning the feamework to solve the problem with sufficient data and then saving the resulting model!
- speed aka learning rate
- it's not by chance, it's by math (linear algebra!)

#### Terms

1. Training - process of improving ml alg by having it review data and improve its mathmatical structure to make better predictions with time.
2. Traning Set - sometimes called the training data, this the data you're going to show your algorithm for it to learn from.
3. Test Set - data we keep aside to tset the results of training against, and is never used as training data.
4. Validation Sets - small set of training data that is set aside to make validation tests before letting your model train on an expensive infractursture or for a long time. This tuning and testing for validation is your validation set.
5. Tensors - optimized data structures that allows for GPU and WASM acceleration for immense ai/ml calculation sets.
6. Normalization - process of scaling input values to a simpler domain.
7. Data Augmentation - detecting patterns in different settings.
8. Features and Featurization - limiting paramters of the training data to practical inputs

## Questions

- Machine learning is the process of taking random data and turning it into a meaningful data that can predict the outcome of a question.
- Unsupervised Learning
- Reinforcement Learning
- No, it only produces the most reliable data set that it found
- Featurization, by limiting the paramters given to the training set
