# Design and Build Input Data Pipeline

- [ ] **Question 1** What are distinct ways to create a dataset?

```
I don't understand the question itself and the bizzare candidate answer.
데이터 세트를 만드는 고유한 방법은 무엇입니까?
```

A data source constructs a Dataset from data stored in memory or in one or more files.

**A data transformation constructs a dataset from one or more tf.data.Dataset objects.**


A data source constructs a Dataset from data stored in memory or in one or more files and a data transformation constructs a dataset from one or more tf.data.Dataset objects.

None of the options are correct.

```
This answer is partially correct, please review the module again.
```

**Question 2** Which is true regarding feature columns?

Feature columns describe how the model should use raw output data from your features dictionary.


Feature columns describe how the model should use raw output data from your TPU's.

**Feature columns describe how the model should use `raw input data` from your features dictionary.**


Feature columns describe how the model should use a graph to plot a line.

- [ ] **Question 3** Which of the following is true about embedding?

An embedding is a weighted sum of the feature crossed values. 

Embedding is a handy adapter that allows a network to incorporate spores or categorical data.

- spores n. 홀씨

**The number of embeddings is the hyperparameter to your machine learning model.**

All options are correct.

```
This answer is partially correct, please review the module again.
```

**Question 4** What is the use of tf.keras.layers.TextVectorization?

It performs feature-wise normalization of input features.


It turns continuous numerical features into bucket data with discrete ranges.

**It turns raw strings into an encoded representation that can be read by an Embedding layer or Dense layer.**


It turns string categorical values into encoded representations that can be read by an Embedding layer or Dense layer.

- [ ] **Question 5** Which of the following is not a part of Categorical features preprocessing?

tf.keras.layers.CategoryEncoding

**tf.keras.layers.Hashing**


tf.keras.layers.IntegerLookup

tf.keras.layers.Discretization

```
This answer is incorrect, please review the module again.
```

- [ ] **Question 6** Which of the following layers is non-trainable?

Discretization

**Hashing**


Normalization

StringLookup

- [ ] **Question 7** When should you avoid using the Keras function adapt()?

**When working with lookup layers with very large vocabularies**


When using TextVectorization while training on a TPU pod


When using StringLookup while training on multiple machines via ParameterServerStrategy

When working with lookup layers with very small vocabularies

```
Why?
```

- [ ] **Question 8** Which of the following is a part of Keras preprocessing layers?

Image data augmentation


Image preprocessing 


Numerical features preprocessing 

**All of the options are correct.**