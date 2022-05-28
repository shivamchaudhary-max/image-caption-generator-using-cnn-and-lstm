# image-caption-generator-using-cnn-and-lstm
in this project we build an image generator to load an random image and give some captions describing the image.
we have use cnn for image feature extraction and lstm for geneation of caption.
BLEU score is used as metric and BLEU score of our project is .53 which is consider good.
we use VGG-16 for feature extraction instead of cnn.
loss=sparse categorical crossen tropy
optimizer=adam
dataset=flickr 8k which contains 8091 images and flicker 8k text which contain text files with captions.
i train model for 20 epocs and batch size is 32 with 227 steps.

