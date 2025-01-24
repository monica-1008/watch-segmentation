# AI Powered Watch Detection System using UNET Architecture

This project is an AI-powered watch detection and segmentation system built using the UNET architecture. It can detect and segment watches from images uploaded by users. The system is designed to be user-friendly, using Streamlit for the web interface, making it accessible to anyone.

## System Overview

The Watch Detection System uses the UNET model to identify and segment watches in images. The model is trained on a custom dataset of watch images, and the system allows users to upload images for watch detection and segmentation.

### Key Features:
- **Watch Detection and Segmentation**: Uses the UNET architecture for high-quality segmentation of watches in images.
- **User-Friendly Interface**: The web interface is built using Streamlit, making it easy for users to interact with the system.
- **Real-Time Results**: Upon uploading an image, the system quickly processes it and provides segmented outputs.

## Demo Link

You can try the system live on the following link:

[Watch Segmentation App](https://watch-segmentation-s2123599.streamlit.app/)

## Dataset

The dataset used for training the model is available on Google Drive. It contains images of watches with labeled annotations for training the segmentation model.

You can access the dataset here:

[Watch Segmentation Dataset](https://drive.google.com/drive/folders/17T7n7lal59dSMcWHifzkB_f_HWE1jNor?usp=sharing)

### Dataset Details:
- **Number of Classes**: 2 (Background and Watch)
- **Image Annotations**: Segmentation masks annotated for training.
- **Image Types**: High-resolution images of various types of watches.

## Model Weights

The trained UNET model weights are available for download. You can use these weights to replicate the results or further fine-tune the model for your use case.

[Download Model Weights](https://drive.google.com/file/d/11MstxV8kt1fEHiLtnAe38kjgU7ru9xik/view?usp=sharing)

## Usage

Once the app is up and running, simply upload an image of a watch, and the system will return the segmented output.
