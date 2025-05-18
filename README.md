# Automated Pneumonia Detection from Chest X-Ray Images Using Deep Learning

Developed a deep learning model to detect pneumonia from X-rays with 90% accuracy, utilizing TensorFlow and image data augmentation techniques.


![image](https://github.com/user-attachments/assets/fe4aa26b-7d37-4e26-a6c3-a8c059a1b668)


---

## Summary

- Built and trained deep learning models to distinguish pneumonia from normal cases using chest X-ray images.
- Managed datasets using Python with libraries such as TensorFlow, Keras, NumPy, and Pandas.
- Imported data from Google Drive and preprocessed using ImageDataGenerator for real-time data augmentation.
- Created models with varied hyperparameters and architectures to optimize performance:
- Main model: TensorFlow Sequential model with Conv2D, MaxPooling2D, Flatten, and Dense layers.
- Alternative models: Adjusted stochastic gradient descent (SGD) optimizer and network depth.
- Evaluated models using accuracy, loss metrics, and produced a confusion matrix and classification report.
- Compared optimizer performance (Adam vs. SGD) and the effect of network depth on model accuracy.

## Results

- Achieved ~90% accuracy with the main model using the Adam optimizer and four hidden layers.
- Secondary models with SGD and reduced network depth achieved ~82% and ~87% accuracy, respectively.

---

## Tools & Technologies

- TensorFlow 2.8.2 for building deep learning models.
- Google Colab for executing Jupyter Notebooks.
- Data augmentation and image preprocessing to enhance model robustness.

---

## Comments

- Adam optimizer was found to be more effective compared to SGD in this context.
- The depth of neural networks was directly correlated with the accuracy, with deeper networks performing better.

---

Tags: #Deep Learning, #Medical Imaging, #Pneumonia Detection, #TensorFlow, #Image Processing, #Convolutional Neural Networks (CNN), #Data Augmentation, #Classification, #Health Informatics

---
