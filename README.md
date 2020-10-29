# Xception Facial Expressoin Recognition

This repository contains an implementation of Xception Facial Expression Recognition.
The model assign a sentiment score to each face based on facial expression, the highest score will determine the emotion associated with the face:

- angry
- disgust
- fear
- happy
- neutral
- surprise
- sad

The neural networks model is trained on the FER-2013 dataset that can be found at: https://www.kaggle.com/deadskull7/fer2013
The CNN is implemented with tensorflow/keras libraries and during the training process checkpoints are created to interrupt and resume the process at a later time.
