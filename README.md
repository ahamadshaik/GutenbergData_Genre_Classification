# Gutenberg Data_Genre_Classification
- Genre Identification on subset of a Gutenberg corpus.
- Assigning a book to its genre, using various supervised models and compare the performance.
- Achieved an Accuracy of 96%.

## Dataset:
- The corpus consist of 996 HTML files. Each file is a fiction book.
- The master996.csv file consists meta data about the books.
  - Book Name
  - Book ID
  - Book Genre
  - Author Name
- Our target attribute is Book Genre.
- **Challenge in Dataset**: Class Imbalance.

## Models:

Deep Learning:

- Multi-Layer Perceptron
- Convolutional Neural Networks.

Machine Learning:

- Support Vector Machines
- Naïve Bayes

### Libraries and Tools:

- TensorFlow 2.0
- Keras
- Scikit-Learn
- NLTK
- Numpy
- Pandas
