# Image-Captioning
Image features were generated from the Pre-Trained VGG16 model as encoder, while the text features were
generated from scratch using Sequence Feature Layers. Both features were fed into the LSTM layer as decoders.
Fine-tuned the model on the Flickr8K dataset and Evaluated the performance of the model using BLEU-1 metrics.
The link for the dataset is https://www.kaggle.com/datasets/adityajn105/flickr8k
