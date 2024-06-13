
# Image Classification with ResNet

## Introduction
This project explores image classification using different variations of the ResNet model. The objective is to understand how deep neural networks work in vision and to utilize trained neural networks for inference with PyTorch.

## Prerequisites

### Software Requirements
- Python 3.x
- Google Colab
- PyTorch
- Torchvision
- NumPy
- Matplotlib

### Hardware Requirements
- A computer with internet access to run Google Colab

## Project Structure
```
.
├── sample_data/
│   └── images/                   # Folder containing images for classification
├── Image_Classification_ResNet.ipynb   # Jupyter notebook with the project code
├── results/                      # Folder to save result screenshots
└── README.md                     # Project README file
```

## Part A: Image Classification with ResNet50
- **Task:**
  - Select 10 classes from the ImageNet classes list.
  - Capture two images for each class and upload them to the `sample_data/images/` folder.
  - Run inference for each image using ResNet50.
  - Display the image, classification ID, class name, and confidence score.

## Part B: Image Classification with ResNet Variations
- **Task:**
  - Switch from ResNet50 to another ResNet variation (e.g., ResNet18).
  - Repeat the classification process for the same images.
  - Display the image, classification ID, class name, and confidence score for the new model.

## Part C: Image Classification with Other Pre-trained Models (Bonus)
- **Task:**
  - Choose a pre-trained model within torchvision that performs better than ResNet50 on the selected images.
  - Compare the classification accuracy and confidence scores of all models.
  - Display the image, classification ID, class name, and confidence score for the chosen model.

## Usage
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/image-classification-resnet.git
   cd image-classification-resnet
   ```

2. **Open the Google Colab Notebook:**
   - Open [Google Colab](https://colab.research.google.com/).
   - Upload `Image_Classification_ResNet.ipynb` to your Google Colab space.
   - Follow the instructions in the notebook to run the project.

## Results
- The project results include the original image, transformed image, original and transformed image sizes, and predictions from the different models used.
- Results are saved as screenshots in the `results/` folder.

## Conclusion
This project demonstrates the capabilities of various ResNet models for image classification. It also highlights the process of switching between different models and comparing their performance.

## Contributing
Feel free to fork this repository, submit issues, and send pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License.
