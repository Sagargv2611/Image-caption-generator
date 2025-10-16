<<<<<<< HEAD
# Image Caption Generator

A deep learning project that generates textual captions for images using the **Xception CNN** for feature extraction and **LSTM** for sequence generation.

## Features
- Uses Xception (pretrained on ImageNet) for image feature extraction.
- LSTM model for caption generation.
- Tokenization and sequence padding with Keras.
- End-to-end training and testing pipeline.

## Files
- `main.py` → Training the caption generation model.
- `test.py` → Testing and generating captions for new images.

## Model Architecture
- CNN encoder (Xception)
- LSTM decoder
- Combined multimodal model using Keras functional API

## Requirements
```bash
tensorflow
keras
numpy
pillow
matplotlib
tqdm
```

## Example Usage
```bash
python test.py --image path/to/your/image.jpg
```

## Dataset
The model is trained using the [Flickr8k dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k).
