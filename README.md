# LSTM-for-Human-Activity-Recognition-using-Smartphone-Accelerometer-data

Human Activity Recognition using Smartphone Accelerometer Data with LSTM
This project aims to implement a Human Activity Recognition (HAR) system using raw accelerometer signal data from smartphones. The dataset used in this project is sourced from the WISDM (Wireless Sensor Data Mining) Lab at Fordham University, NY. The dataset consists of tri-axial accelerometer readings from smartphones, capturing acceleration in all three spatial dimensions.

Dataset Description
The dataset used in this project is the WISDM_ar_v1.1_raw.txt file, which contains raw accelerometer signal data. Each data point in the dataset includes the following features:

User: Identifies the user performing the activity.
Activity: Indicates the type of activity performed, such as walking, jogging, sitting, standing, etc.
Timestamp: Records the timestamp when the accelerometer reading was captured.
X, Y, Z Acceleration: Tri-axial accelerometer readings capturing acceleration in three spatial dimensions.
Methodology
The project utilizes Long Short-Term Memory (LSTM) networks, a type of recurrent neural network (RNN), for human activity recognition. LSTM networks are well-suited for sequence prediction tasks and can effectively capture temporal dependencies in sequential data like time series or sensor readings.

The implementation involves the following steps:

Data Preprocessing: The raw accelerometer signal data is preprocessed to extract relevant features and prepare the data for training the LSTM model. This includes segmenting the data into fixed-length windows and normalizing the accelerometer readings.

Model Architecture: An LSTM-based neural network architecture is designed for human activity recognition. The LSTM model takes the preprocessed accelerometer data as input and learns to predict the activity labels.

Training and Evaluation: The LSTM model is trained on the preprocessed data and evaluated using techniques such as train-test split or k-fold cross-validation. The performance of the model is assessed based on metrics like accuracy, precision, recall, and F1-score.

Model Deployment (Optional): Once trained and evaluated, the LSTM model can be deployed for real-time human activity recognition on new data from smartphones.

Conclusion
Human Activity Recognition using smartphone accelerometer data has various applications in fields like healthcare, fitness tracking, and behavior analysis. By implementing LSTM-based models, we can accurately classify human activities based on sensor data, paving the way for intelligent and context-aware mobile applications.

References
Original Dataset: WISDM Lab, Fordham University
Blog Post: Implementing LSTM for Human Activity Recognition using Smartphone Accelerometer Data
