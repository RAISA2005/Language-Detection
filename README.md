# 🌍 Language Detection using Simple RNN

## 📌 Project Description

This project is an AI-powered Language Detection application developed using Python, TensorFlow, and Streamlit. It uses a Simple Recurrent Neural Network (RNN) model to identify the language of user-entered text.

The model is trained on multilingual text data and deployed through a Streamlit web application, enabling users to detect the language of any sentence in real time along with the model's prediction confidence.

---

## 🎯 Project Objectives

* Detect the language of user-entered text using a Simple RNN model.
* Classify multilingual text accurately.
* Provide real-time language predictions through a web application.
* Demonstrate the practical implementation of deep learning for Natural Language Processing (NLP).

---

## 📂 Project Structure

The project consists of three major components:

### 1. Model Training

### 2. Language Prediction

### 3. Model Deployment using Streamlit

---

# 🧠 Model Training

The multilingual text dataset is preprocessed before training.

### Data Preprocessing

* Text cleaning
* Tokenization
* Sequence generation
* Padding sequences
* Label encoding
* Train-test splitting

### Simple RNN Architecture

* Embedding Layer
* Simple Recurrent Neural Network (RNN)
* Dense Output Layer

### Training Process

* The model is trained on multilingual text samples.
* It learns sequential patterns within text.
* The trained model and tokenizer are saved for future predictions.

---

# 🔮 Language Prediction

After training:

* The saved RNN model is loaded.
* User text is converted into numerical sequences.
* Sequences are padded before prediction.
* The model predicts the most probable language.
* Prediction confidence is displayed along with the detected language.

---

# 🌐 Model Deployment using Streamlit

Streamlit is used to build an interactive web application.

### Features

* Simple text input interface
* Real-time language detection
* Prediction confidence score
* User-friendly design
* Fast and responsive performance

### Workflow

1. User enters text.
2. Text is converted into sequences.
3. Sequences are padded.
4. RNN model predicts the language.
5. The predicted language and confidence score are displayed.

---

# 🛠️ Tech Stack

## Programming Language

* Python

## Libraries & Frameworks

* TensorFlow
* Keras
* Streamlit
* NumPy
* Pickle

## NLP Techniques

* Tokenization
* Sequence Encoding
* Padding
* Language Classification

## Development Tools

* Visual Studio Code (VS Code)
* Jupyter Notebook
* Git & GitHub

---

# 📊 Dataset

### Multilingual Language Dataset

The dataset contains text samples from multiple languages used for training and evaluating the language detection model.

---

# ⚙️ Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/RAISA2005/Language_Detection.git
```

### Navigate to the Project Directory

```bash
cd Language_Detection
```

### Install Required Dependencies

```bash
pip install streamlit tensorflow numpy python-dotenv
```

### Run the Application

```bash
streamlit run app.py
```

---

# 📈 Applications

* Language Identification
* NLP Applications
* Multilingual Chatbots
* Text Processing Systems
* Document Classification
* AI-powered Translation Systems

---

# 🔮 Future Enhancements

* Support for more languages
* Bidirectional LSTM/GRU models
* Transformer-based language detection
* Voice language detection
* Cloud deployment
* REST API integration

---

# 👩‍💻 Author

**Raisa Sharfeen**

**Role:** B.Tech Student (CSE - AI & ML)

### Skills & Interests

* Artificial Intelligence
* Machine Learning
* Deep Learning
* Natural Language Processing
* Python Programming
* Data Structures & Algorithms
* Problem Solving

### Connect With Me

📧 Email: [rsharfeen@gmail.com](mailto:rsharfeen@gmail.com)

🔗 LinkedIn: https://www.linkedin.com/in/raisa-sharfeen-62958437a

🔗 GitHub: https://github.com/RAISA2005

---

# 🙏 Acknowledgement

This project was developed for academic and learning purposes to gain practical experience in:

* Deep Learning using Simple RNN
* Natural Language Processing
* Language Detection
* TensorFlow Model Deployment
* Streamlit Web Application Development

Special thanks to the open-source community and the developers of TensorFlow, Streamlit, and Python for providing powerful tools that made this project possible.

---

# 📜 License

This project is intended for educational and learning purposes only.

Feel free to use, modify, and explore the project for academic and research purposes.

---

⭐ If you found this project useful, consider giving it a star on GitHub and sharing it with others learning Deep Learning and Natural Language Processing.

Thank you for visiting this repository!

