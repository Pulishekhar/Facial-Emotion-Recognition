Facial Emotion Recognition using CNN
This project builds a deep learning model using Convolutional Neural Networks (CNNs) to recognize human facial expressions from grayscale images. It classifies emotions like happy, sad, angry, surprised, disgust, fear, and neutral.

🧠 Tech Stack & Tools
Languages/Libraries: Python, TensorFlow, Keras, OpenCV, NumPy, Pandas

Model Architecture: CNN with Conv2D, MaxPooling2D, Dropout, and Dense layers

Utilities: Matplotlib, Seaborn, tqdm for visualization and progress tracking

📥 Dataset
Source: Pre-sorted facial expression image dataset (Kaggle-style directory structure)

Train Path: /train/train/

Test Path: /test/test/

Format: Grayscale images, 48×48 pixels, stored in class-named folders (e.g., happy, sad, etc.)

⚙️ Model Workflow
Load images and labels from train/test directories

Convert data to Pandas DataFrame

Preprocess images (resizing, normalization)

Encode labels using one-hot encoding

Train CNN model with CategoricalCrossentropy loss and Adam optimizer

Evaluate model on test set

📈 Results
Validation Accuracy: ~79%

Validation Loss: ~0.6

Achieved robust performance across all 7 emotion categories

📊 Output
The model predicts one of the following emotions for each test image:

😄 happy

😢 sad

😠 angry

😮 surprise

😐 neutral

😨 fear

🤢 disgust
