# 🤖 Real-Time Digit Recognition System

A deep learning-based **real-time digit recognition** app using **Python**, **OpenCV**, **TensorFlow**, and **Streamlit**. It captures digit images via **webcam**, processes them, and predicts the digit using a **CNN trained on the MNIST dataset**.

---

## 🚀 Features

✅ **Live Webcam Feed** for digit drawing  
✅ **CNN Model** trained on MNIST dataset  
✅ **Real-Time Predictions** on captured digits  
✅ **Streamlit UI** for a smooth interactive experience  
✅ **Preprocessing Pipeline** for image cleaning & resizing  

---

## 🛠️ Tech Stack

* **Frontend**: Streamlit, OpenCV
* **Backend**: Python
* **Deep Learning**: TensorFlow, Keras
* **Data**: MNIST Handwritten Digit Dataset

---

## 🧠 How It Works

### 📦 Model Training (`model_training.py`)
- Loads MNIST data
- Normalizes and reshapes images
- Builds and trains a CNN
- Saves the trained model (`mnist_cnn.h5`)

### 🎥 Streamlit App (`app.py`)
- Opens webcam using OpenCV
- Captures user-drawn digits on screen
- Preprocesses the frame to match MNIST format
- Loads trained CNN model
- Predicts and displays the digit live

---

## 📁 File Structure

.
├── app.py # Streamlit frontend with webcam
├── model_training.py # Model training script
├── mnist_cnn.h5 # Trained model file
├── requirements.txt # Python dependencies
└── README.md # Project documentation

yaml
Copy
Edit

---

## 📦 Installation

### 1️⃣ Clone the Repository

bash
git clone https://github.com/YOUR_USERNAME/real-time-digit-recognition.git
cd real-time-digit-recognition
###2️⃣ Create a Virtual Environment (optional)
bash
Copy
Edit
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
###3️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
🧪 Usage
▶️ To Train the Model:
bash
Copy
Edit
python model_training.py
▶️ To Run the Streamlit App:
bash
Copy
Edit
streamlit run app.py
A browser window will open where your webcam will activate and start digit prediction in real time.

✨ Future Enhancements
Improve drawing interface (canvas-based instead of webcam)

Add model confidence score

Add support for multi-digit recognition

Deploy on Hugging Face Spaces or Heroku

🧑‍💻 Author
Developed by Anand Yadav
GitHub: @anandy07

📜 License
This project is licensed under the MIT License.

⭐ Contribute & Support
If you liked this project, consider giving it a star ⭐ on GitHub!
Pull requests and suggestions are welcome!

go
Copy
Edit

Let me know if you also want the full `app.py` and `model_training.py` code added directly for upload.








