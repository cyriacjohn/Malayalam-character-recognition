# Malayalam Character Recognition

As a proud Malayali, I've always been captivated by the beauty and complexity of the Malayalam script. This project, **Malayalam Character Recognition**, is inspired by my love for my native language and its unique script. The goal is to build a tool that recognizes handwritten Malayalam characters using deep learning, contributing to the digital accessibility of this culturally rich language.

## 🌟 Project Overview

This project uses a Convolutional Neural Network (CNN) to recognize and classify handwritten Malayalam characters. By identifying individual characters from images, it has potential applications in OCR (Optical Character Recognition) systems, educational tools, and digital libraries. The project aims to help digitize handwritten Malayalam text, promoting accessibility for Malayalam speakers and learners alike.

## 🚀 Features

- **Accurate Character Recognition**: Uses deep learning to accurately recognize and classify core Malayalam characters.
- **Preprocessing Pipeline**: Built-in preprocessing for image-based character data to improve model accuracy.
- **User-Friendly Interface**: Functions for loading images and obtaining character predictions.
- **Scalable Architecture**: Easily adaptable for scaling with additional data or new languages.
- **Flexible Input**: Works with scanned or photographed images of handwritten text, making it versatile for a variety of use cases.

## 🛠️ Technologies Used

- **Python**: Core programming language
- **TensorFlow/Keras**: For deep learning model implementation
- **OpenCV**: Image processing library
- **Numpy**: Data manipulation and preprocessing
- **Jupyter Notebooks**: For experimenting and evaluating model performance

### Prerequisites

1. **Python 3.7+**: Ensure Python is installed on your system.
2. **Virtual Environment (recommended)**: To isolate project dependencies.
3. **Clone the Repository**:
   ```bash
   git clone https://github.com/cyriacjohn/malayalam-character-recognition.git
   cd malayalam-character-recognition
   ```
### Installation
Create a virtual environment (optional but recommended):

```bash
python3 -m venv venv
.\venv\Scripts\activate
```  
Install required packages:

```bash
pip install -r requirements.txt
```

### Dataset Preparation:

- Download the Dataset from [here](https://drive.google.com/file/d/1WjZnnmmfjv7-N-WakhJdLoDhiHEi5dOb/view)
- Organize the dataset in data/raw folder as per your requirements.
- Training the Model
- To train the model, run:

```bash
python src/main.py --mode train --epochs 20
```
- Evaluating the Model
- To evaluate the trained model on test data, use:
```bash
python src/main.py --mode evaluate
```
- Running Prediction
To predict on a single image:
```bash
python src/main.py --mode predict --image_path path/to/your/image.png
```

## ⚙️ Model Architecture
The CNN architecture consists of:

- Convolutional Layers: To detect character patterns.
- Pooling Layers: To reduce dimensionality.
- Fully Connected Layers: For classification.
- Hyperparameters
- Learning Rate: 0.001
- Batch Size: 32
- Epochs: Configurable, recommended 20-30

## 📊 Results and Performance
- Training Accuracy: 92%
Validation Accuracy: 89%
These metrics are based on the dataset used and may vary with different data.

## 🤝 Contributing
Contributions are welcome to help improve this project! Feel free to:

1. Fork the repository.
   Clone your fork and create a new branch:
```bash
git checkout -b feature-branch
```
2. Make your changes and commit them.
3. Push your branch and create a Pull Request.

My goal is to contribute to the accessibility of Malayalam and promote its use in the digital world.

### You can reach out to me/check out my blogs:
[Linkedin](https://www.linkedin.com/in/cyriac-john-5b7844216/)</t>
[Email](yohncyriac2002@gmail.com)</t>
[Medium](https://www.medium.com/@cyriacjohn)

