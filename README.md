# Intrusion-Detaction-System

🔧 Technologies Used
🔹 Backend / Core Logic
Flask	Lightweight web framework to build the web app
TensorFlow / Keras	Deep learning framework; used for CNN model
Pandas	Data manipulation and loading CSV files
NumPy	Numerical operations on arrays
Scikit-learn	Used for OneHotEncoding of categorical variables
Joblib	Loading saved encoders (.pkl files)


🔹 Frontend
Technology	Purpose
HTML (index.html)	Web form for file upload & results display
Bootstrap (optional)	Styling and responsiveness (if used in index.html)
Jinja2 (Flask built-in)	Render dynamic content (e.g., errors, predictions)


📊 Dataset
NSL-KDD Dataset
Improved version of the original KDD Cup 1999 dataset.
Used for network intrusion detection.
Two subsets used:
KDDTrain+.txt
KDDTest+.txt
You also included:
10% KDD dataset (kddcup.data_10_percent.gz) for historical data comparison.
Each row has 41 features + 1 label. You extract 42 columns (desired_columns) for training/testing.


🧠 Model
🧬 Convolutional Neural Network (CNN)
Saved as cnn_model.h5
Input is reshaped to 3D [samples, features, 1]
Output is multi-class, softmax applied; classification by argmax.





