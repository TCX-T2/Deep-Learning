# Deep-Learning


# Tumor Detection and Prediction Notebook

## Overview
This notebook utilizes a pre-trained deep learning model to detect and predict the type of tumors in medical images. It leverages the MobileNetV2 architecture and is trained to classify tumors into different categories. The predicted results, along with additional information provided by the user, are saved in a PDF report.

## How to Use
1. **Upload Image**: Use the provided Colab widget for file uploading to upload a medical image containing a tumor.
2. **Input Patient Information**: Enter the patient's name, surname, and date of birth as prompted.
3. **Run the Notebook**: Execute the notebook cells to perform image classification and generate the prediction report.
4. **View Results**: The predicted tumor type, recommended treatments (if applicable), and the resized image are displayed within the notebook.
5. **Save PDF Report**: A PDF report is generated, containing patient information, predicted results, and the embedded image. Each report has a unique filename based on the timestamp.

## Dependencies
- TensorFlow
- Pillow (PIL)
- ReportLab
- Google Colab (for file uploading)

## File Structure that you must dowload or create
- `ModelData/`: Directory containing the pre-trained MobileNetV2 model.
- `Rapports_Scan/`: Directory where prediction reports are saved.

## Use this picture to test the model

![testImage](https://github.com/TCX-T2/Deep-Learning/assets/94483687/1d3c138f-dc72-4164-9588-9fdba0f3c695)

## Note
Make sure to upload the model in you drive data path (`'/content/drive/MyDrive/ModelData'`) and create a file save path (create the /MyDrive/Rapports_Scan) (`'/content/drive/MyDrive/Rapports_Scan/'`) according to your file structure.

## Author
TCX Team 2


