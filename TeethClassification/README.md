Teeth Segmentation using U-Net 🦷🔬

This project focuses on the segmentation of dental X-ray images to identify and isolate teeth using the U-Net architecture.
📂 Project Structure

    Teeth_Segmentation.ipynb: The main Jupyter Notebook containing data preprocessing, model building, training, and evaluation.

    UNetSummary.pdf: A detailed summary and theoretical overview of the U-Net architecture, explaining the Encoder-Decoder paths and skip connections.

🧠 Model Architecture: U-Net

The project implements the U-Net architecture, which is specifically designed for biomedical image segmentation. It consists of:

    Contracting Path (Encoder): Captures context through downsampling.

    Expanding Path (Decoder): Enables precise localization through upsampling.

    Skip Connections: Directly connect encoder layers to decoder layers to preserve fine-grained spatial details.

🛠️ Tech Stack

    Python

    TensorFlow / Keras (for model implementation)

    KaggleHub (for dataset management)

    OpenCV & Matplotlib (for image processing and visualization)

📊 Dataset

The model was trained using the "Teeth Segmentation on Dental X-ray Images" dataset from Kaggle, which includes high-quality X-ray images and their corresponding masks.
🚀 How to use

    Upload the Teeth_Segmentation.ipynb to Google Colab or run it locally.

    Ensure you have the kagglehub library installed to fetch the dataset automatically.

    Follow the steps in the notebook to preprocess the images and train the model.
