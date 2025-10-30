# student-projects
creation of fun projects
# AI Vision Practice

This project is a personal learning experiment in **image classification** using a custom dataset and a **Convolutional Neural Network (CNN)**.  
Built entirely on **Google Colab**, it reflects my growing passion for Artificial Intelligence, deep learning, and computer vision.

---

## Project Overview

The goal of this project is simple but meaningful:
> **Classify different types of images into categories using a CNN model.**

I collected my own image samples, prepared them into a dataset, and trained a neural network model that can recognize visual patterns from the data.  
This hands-on practice helped me understand dataset organization, preprocessing, model design, and evaluation.

---

## ⚙️ Technologies Used

- **Python 3**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Google Colab** (for development and training)
- **GitHub** (for version control and learning collaboration)

---

## 🧩 How the Model Works

1. **Dataset Management**
   - Images were organized into labeled folders (`train/`, `test/`, and `validation/`).
   - Used TensorFlow’s `ImageDataGenerator` to preprocess and normalize images.

2. **Model Architecture**
   - Implemented a simple **Convolutional Neural Network (CNN)** with:
     - Convolutional + MaxPooling layers
     - Flatten + Dense layers
     - Softmax output for classification
   - Trained for several epochs until accuracy improved significantly.

3. **Results**
   - The model successfully learned to identify categories from my collected images.
   - I saved the final model as:
     ```python
     model.save('image_classifier.keras')
     ```

---

##  Example Training Output 
Even though it’s a student project, the accuracy results were encouraging and showed that the model learned real visual differences from my dataset.

---

##  Future Improvements

- Expand the dataset for better generalization  
- Experiment with **Transfer Learning** (e.g., MobileNetV2, ResNet50)  
- Build a simple web or mobile interface for predictions  
- Deploy the model using **Flask** or **Gradio**

---

## About the Author

**Josphat Mwangi**  
GitHub: [@lunuel](https://github.com/lunuel)  
Email: [123muthamajosphat@gmail.com](mailto:123muthamajosphat@gmail.com)  
Phone: [+254757346301](tel:+254757346301)

---

##  Acknowledgements

Special thanks to open-source AI communities, YouTube tutorials, and online mentors who continue to make AI education accessible to everyone.

> *“Every small project builds a bigger understanding.” — Personal motto during this journey.*