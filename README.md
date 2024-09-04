### Description:
This project focuses on classifying VPN traffic using a deep learning-based approach by converting network traffic into packet block images. The classification task involves detecting different types of encrypted VPN traffic, such as VOIP, Video, File Transfer, Chat, and Browsing.

### Key Features:
- **Data Preprocessing**: Raw network traffic data is processed to extract relevant features such as IP addresses, ports, and protocol information. The data is cleaned and filtered to remove any NaN or infinite values.
- **Packet Block Image Generation**: Network traffic is grouped into packet blocks and transformed into images, where each image represents a sequence of packets within a block. This image serves as input to the deep learning model.
- **CNN Model**: A 1D Convolutional Neural Network (CNN) is designed to classify the packet block images into different VPN traffic categories. The model includes two convolutional layers followed by max-pooling and fully connected layers with dropout for regularization.
- **Training and Evaluation**: The model is trained using the Adam optimizer and cross-entropy loss. The dataset is split into training and testing sets to evaluate model performance. The final model achieves around 73% accuracy on the test data.
- **Visualization**: Training accuracy, validation accuracy, and loss curves are plotted to monitor model performance over epochs.

### Technologies Used:
- **Python**
- **Keras** and **TensorFlow** for deep learning
- **Pandas**, **NumPy** for data processing
- **Matplotlib** for visualization

### Project Guide:
This project was completed under the guidance of **Dr. Jai Prakash Gupta (Scientist-E, DRDO)** as part of an internship at DRDO, from **24th June 2024 to 24th August 2024**.

### Acknowledgments:
Special thanks to DRDO and Dr. Jai Prakash Gupta for their mentorship and support throughout this project.
