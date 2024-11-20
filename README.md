# Handwritten-digits-and-character-recognition-HINDI
Handwritten Devanagari Character Recognition
This project focuses on recognizing handwritten characters and digits from the Devanagari script using Convolutional Neural Networks (CNNs). Devanagari, used in languages like Hindi and Marathi, poses unique challenges due to handwriting variability and script complexity. This project provides an automated solution for transcription and digitization.

Features
Recognition of 36 Devanagari characters and 10 digits.
Uses CNNs for accurate pattern recognition.
Achieves ~98.9% validation accuracy.
Robust to variations in handwriting styles.
Dataset
Total Images: 92,000
Image Dimensions: 32x32 pixels, RGB format.
Split:
Training Set: 78,200 images (85%).
Test Set: 13,800 images (15%).
Technologies Used
Programming Language: Python
Libraries/Frameworks: TensorFlow, Keras, NumPy, OpenCV, Matplotlib
Tools: Jupyter Notebook for development and visualization.
Installation
Clone the repository:
bash
Copy code
git clone <repository-link>
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Usage
Prepare the dataset by placing the images in the specified directory.
Run the training script:
bash
Copy code
python train_model.py
Test the model using:
bash
Copy code
python test_model.py
View results and performance metrics.
Results
Training Accuracy: ~98.9%
Validation Accuracy: ~98.7%
Loss: ~4.5%
Applications
Document digitization for Hindi and related languages.
Automated grading for handwritten scripts.
Real-time handwriting recognition apps.
Language preservation and archiving.
Project Resources
Dataset, Code, PPT, and Project Report:
Click Here
Future Enhancements
Real-time implementation using mobile or web apps.
Expanding support for other Indic scripts.
Adding multilingual OCR capabilities.
License
This project is open-source and available under the MIT License.
