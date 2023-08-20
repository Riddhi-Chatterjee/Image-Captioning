# Image-Captioning

Our goal is to develop a robust CNN-LSTM model for image captioning using the Flickr8
dataset. We start by implementing a baseline model with a chosen CNN-LSTM
architecture and evaluating its performance. 

To improve upon the baseline model, we enhance both the vision embeddings and language embeddings without making any architectural modifications to the LSTM. Several techniques such as Beam Search, Single-Head and Multi-Head Attention, etc are used.

This modified baseline is then compared against the original baseline using various
evaluation metrics, such as BLEU and METEOR scores, to determine the effectiveness of the enhancements. 

The improvements make our image captioning system highly accurate and efficient -- capable of generating descriptive and natural-sounding captions for a wide range of images.
