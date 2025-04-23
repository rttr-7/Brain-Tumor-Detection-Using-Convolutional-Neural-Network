🧠 Brain Tumor Detection using CNN 

This project presents a deep learning-based approach for the early detection and classification of brain tumors from MRI scans. The solution utilizes Convolutional Neural Networks (CNNs) in their custom form and through transfer learning using the pre-trained VGG16 model. The primary goal is to build an intelligent system that can automatically distinguish between various types of brain tumors and non-tumorous brain images, aiding radiologists in timely diagnosis.

📂 Dataset

The project uses the Brain Tumor Classification Dataset provided by Sartaj Bhuvaji, which is publicly available on GitHub.

🔗 Dataset Link - https://github.com/SartajBhuvaji/Brain-Tumor-Classification-DataSet

The dataset contains MRI scans categorized into four classes:
Glioma Tumor
Meningioma Tumor
Pituitary Tumor
No Tumor

It comprises thousands of high-resolution brain MRI images, already divided into training and testing sets, making it suitable for deep learning applications.

🧪 Methodology

The detection pipeline follows a structured sequence of steps to ensure high model accuracy and generalization:
Preprocessing Techniques:
All MRI images are resized for uniformity and normalized to ensure efficient training.
Augmentation techniques such as rotation, flipping, zooming, and shifting are applied to increase data diversity and reduce overfitting.

Model Architectures:

A custom CNN model was developed using multiple convolutional, max-pooling, dropout, and dense layers, tailored to extract complex spatial features.
Additionally, a pre-trained VGG16 model was used with fine-tuning for transfer learning, allowing the network to leverage features learned from a large-scale image dataset.

Training and Evaluation:

Both models were trained using categorical cross-entropy loss and evaluated using standard metrics like accuracy and loss.
The best model achieved a loss of 0.1314 and an accuracy of 94.20%, indicating strong performance in detecting and classifying brain tumors.

📊 Results & Performance

High accuracy across test images shows the models’ reliability in real-world applications.
The models performed well in terms of precision, recall, and F1-score, particularly in differentiating between tumor types.
Dropout layers helped reduce overfitting and improved generalization on unseen data.


🚀 Demo

An interactive demo of the CNN-based brain tumor detection system is deployed and accessible on Hugging Face Spaces:

🔗 Run the Demo - https://huggingface.co/spaces/rttr1/brain_tumor_cnn

![Image Alt](https://github.com/rttr-7/Brain-Tumor-Detection-Using-Convolutional-Neural-Network/blob/ffe052adf695316f8aaf584fcd03ba7246a4ff4e/Screenshot%202025-04-23%20143857.png)


![Image Alt](https://github.com/rttr-7/Brain-Tumor-Detection-Using-Convolutional-Neural-Network/blob/ffe052adf695316f8aaf584fcd03ba7246a4ff4e/Screenshot%202025-04-23%20143841.png)


🛠️ Technologies Used

Python for core development
TensorFlow/Keras for deep learning models
NumPy, Pandas for data manipulation
OpenCV for image processing
Matplotlib for data visualization
Hugging Face Spaces for web deployment

Model - 

📥 You can download the trained model directly from our Hugging Face community space here. 
https://huggingface.co/spaces/rttr1/brain_tumor_cnn/resolve/main/BRAIINTUMORMODEL.h5

📄 Publication

This project has been published in the Scopus-indexed Springer LNNS conference proceedings.

🔗 Published Paper - https://link.springer.com/chapter/10.1007/978-981-97-0180-3_35

It highlights the effectiveness of CNNs in detecting brain tumors and emphasizes the role of AI in healthcare innovation.


🔖 Citation

If you use this project or refer to its methodology in your research, kindly cite the following paper:

Mane, Vijay, Amay Chivate, Prajyot Ambekar, Ananya Chavan, and Ameya Pangavhane.
Brain Tumor Detection Using Convolutional Neural Network.
In International Joint Conference on Advances in Computational Intelligence, pp. 449-461. Springer, 2022.
