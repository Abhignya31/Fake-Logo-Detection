# 🏷️ Fake Logo Detection

A **web application** that classifies brand logos as **Real** or **Fake** using deep learning.  
Built with **MobileNetV2** for fast, lightweight, and accurate predictions, and served through a **Flask** web interface.  

---

## 💡 Features  
- 📤 Upload a logo image and instantly check its authenticity  
- 🔍 Detects Real vs Fake logos with a trained deep learning model  
- ⚡ MobileNetV2-based CNN for optimized performance  
- 🖥 User-friendly web interface powered by Flask & Bootstrap  


---

## 🛠 Tech Stack  

- **Python** 🐍  
- **TensorFlow & Keras** (Deep Learning Framework)  
- **Flask** (Web Framework)  
- **OpenCV** (Image Processing)  
- **Bootstrap** (Frontend Styling)  
 

---

## 🚀 How to Run Locally  

```bash
git clone https://github.com/your-username/fake-logo-detector.git
cd fake-logo-detector

# Create Virtual Environment
python -m venv venv
venv\Scripts\activate  # On Windows
# source venv/bin/activate  # On macOS/Linux

# Install Requirements
pip install -r requirements.txt

# Run Application
python app.py
```

---

## 📂 Project Structure  
```text
fake-logo-detector/
│
├── app.py                      # Flask web application
├── model/
│    └── saved_model.h5         # Pre-trained CNN model
├── static/
│    └── style.css              # Custom CSS styling
├── templates/
│    └── index.html             # Frontend HTML template
├── train_model.py              # Script to train the model
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
└── .gitignore
```
---

## 🎯 Applications  


- ✅ Brand authenticity verification  
- 📚 Educational demonstration of transfer learning  
- 🖼 Proof-of-concept for image classification tasks  


---

## 🔮 Future Improvements  


- 📊 Expand dataset with more brand logos  
- 🎯 Improve accuracy with balanced data  
- ☁ Deploy to cloud platforms (Render, Heroku, Hugging Face Spaces, etc.)  
