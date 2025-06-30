# 👤 Gender and Age Prediction using OpenCV

A Python-based deep learning project that predicts gender and age from an image or webcam feed using OpenCV and pre-trained models.

---

## 🚀 Features
- Predicts **gender** (Male/Female)
- Estimates **age range**
- Works with both **image input** and **live webcam**

---

## 🛠️ Requirements

- Python 3.x  
- OpenCV (`opencv-python`)  
- NumPy  
- Pre-trained models (ensure they're in the correct path)

Install dependencies using:
```bash
pip install -r requirements.txt

You can download all required `.prototxt` and `.caffemodel` files from:
👉 https://github.com/spmallick/learnopencv/tree/master/AgeGender

Make sure to place the following files in your project directory:
- `age_deploy.prototxt`
- `age_net.caffemodel`
- `gender_deploy.prototxt`
- `gender_net.caffemodel`
