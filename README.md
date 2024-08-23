# Image Captioning using Transformers

This project implements an image captioning model utilizing CNN and Transformer architectures. The model architecture is as follows:

## Architecture

![ImageCaptioningArchitecture drawio](https://github.com/user-attachments/assets/737588fe-1cb8-43b5-866a-065a5cff3069)


1. CNN as Feature Extractor:

    - We use EfficientNetB0 as the Convolutional Neural Network (CNN) to extract features from the images.

2. Transformer Encoder:

    - The extracted features from the CNN are passed to the encoder, which consists of multiple Transformer layers.
    - These layers process the features and prepare them for decoding.

3. Transformer Decoder:

    - The decoder, which also comprises Transformer layers, generates captions for the images based on the features provided by the encoder.

4. Data
    - Each input image is associated with five captions.
    - Data preprocessing and augmentation techniques are applied to improve the model's robustness and performance.

5. Model Training
    - Once the model is trained, the results, metrics, and the trained model itself are logged using MLFlow and DagsHub for efficient tracking and management of model development.


## Output Examples

<p float="left">
  <img src="https://github.com/user-attachments/assets/884e0fb1-d958-4f81-9c1a-8dfaf7ca85b5" width="45%" height="100%" />
  <img src="https://github.com/user-attachments/assets/7fc76b3b-eefa-4470-b5fa-1a72aaba853c" width="45%" height="250%" />
</p>



## MLFlow Experiment Tracking

<img width="1496" alt="Screenshot 2024-08-22 at 11 33 45 PM" src="https://github.com/user-attachments/assets/447953df-5d2c-4448-ba42-40ec00f7611f">
<img width="1504" alt="Screenshot 2024-08-22 at 11 33 34 PM" src="https://github.com/user-attachments/assets/b41c455c-915c-46e0-96b5-b8bcb5194c65">


