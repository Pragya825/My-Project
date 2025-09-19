# Plant 🌱 Disease 🐛 Detection 🔎

Plant Disease Detection is an innovative machine learning project that harnesses the power of Convolutional Neural Networks (CNN) and deep learning techniques to identify and classify diseases in plants. The primary objective is to offer farmers and agricultural experts a valuable tool for swift plant health diagnosis, facilitating timely intervention and minimizing the risk of crop loss.

[**Live Demo**] https://share.streamlit.io/Pragya825/my-project/main_app.py


## Project Structure 📂

The project comprises essential components:

- `Plant_Disease_Detection.ipynb`: Jupyter Notebook with the code for model training.
- `main_app.py`: Streamlit web application for plant disease prediction.
- `plant_disease_model.h5`: Pre-trained model weights.
- `requirements.txt`: List of necessary Python packages.

## Installation 🚀

To run the project locally, follow these steps:

## How to Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/Pragya825/My-Project.git

```

2. Navigate to the project directory:
cd "My-Project"



3. **Install the required packages:**

pip install -r requirements.txt


4. **Run the Streamlit web application:**

python app.py


## Usage 🌿

Once the application is running, open your web browser and navigate to [http://localhost:8501](http://localhost:8501). Upload an image of a plant leaf, and the system will predict if it is affected by any disease.

## Model Training

## Model Training

- Trained a Convolutional Neural Network (CNN) on a plant leaf dataset with healthy and diseased leaves.  
- Preprocessed images (resizing, normalization, and data augmentation).  
- Used Adam optimizer and Categorical Crossentropy loss for 25–30 epochs with batch size 32.  
- Achieved ~92% accuracy on the validation set, successfully classifying multiple plant diseases.
 


## Requirements 🛠️

- Keras==2.8.0
- numpy==1.21.4
- streamlit==1.18.0
- opencv-python-headless==4.5.3
- tensorflow==2.7.0
