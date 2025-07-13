# 🚗 Self-Driving Car Model using CNN and TensorFlow

Welcome to my self-driving car machine learning project! This project uses the NVIDIA model built with TensorFlow to build and train a model capable of steering based on image inputs — just like a real self-driving car.

---

## 📹 Demo Video

> 🎬 **Coming soon!**  
> Once the demo video is available, it will appear here to showcase the project's results.

---

## 📌 Project Highlights

- NVIDIA model
- Image preprocessing using OpenCV
- Image steering angle prediction
- TensorFlow GPU acceleration
- Use Udacity Simulator for training and testing or clone data from here: 

```
git clone https://github.com/rslim087a/track
```

---

## 🛠️ Environment Setup

### ✅ Step 1: Install Miniconda

Download and install Miniconda from the official site:  
👉 [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)

Miniconda is a lightweight version of Anaconda and is recommended for managing your environments without the bloat.

---

### ✅ Step 2: Create a Python 3.9 Conda Environment

TensorFlow GPU 2.10 supports only **Python 3.9** or **3.10** on **Windows Native**. Python 3.11+ does **not work** for this version of TensorFlow.

```bash
conda create -n self_driving_env python=3.9 -y
conda activate self_driving_env
```
### 3️⃣ Install TensorFlow GPU 2.10
```
pip install tensorflow-gpu==2.10
```
>💡 Ensure that you have the right NVIDIA drivers and CUDA toolkit for GPU support:
>https://www.tensorflow.org/install/gpu#windows-setup

### 📚 Install Project Dependencies
You can install all required Python libraries using ```requirements.txt```.

```
pip install -r requirements.txt
```
or manually if needed

```
pip install numpy matplotlib tensorflow keras scikit-learn opencv-python pandas imgaug
```

### 📓 Run the Jupyter Notebook
### 🔧 Notes on Compatibility
- Python 3.9 or 3.10 is required

- TensorFlow 2.10 is the last version with native GPU support on Windows

- Avoid Python 3.11+ for this build, as it is not compatible with the required TensorFlow version


### 🙋🏽‍♂️ Author
Keshinro Mus'ab Moyosore

Machine Learning Engineer | Mechatronics Student | AI for Good Advocate

[Linkedin](https://www.linkedin.com/in/keshinro-musab/) | [Github](https://github.com/Keshtech2002)

