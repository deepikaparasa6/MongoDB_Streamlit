# MongoDB_Streamlit
Projects using Streamlit

# 🌈 Streamlit Playground – MongoDB Project Add-On

Welcome to my Streamlit World! 🚀  
This repo is a joyful mashup of 3 super fun Streamlit applications I created while exploring UI interactivity, ML models, data visualizations, and good ol’ Python magic ✨🐍

> 📍 Part of my MongoDB & Full Stack Dev learning series  
> 🧑‍💻 Author: [@deepikaparasa6](https://github.com/deepikaparasa6)

---

## 🧩 What's Inside?

### 🔹 1. **Basic UI Playground**
A simple app showcasing how Streamlit handles:

- Text inputs
- Sliders
- Buttons
- Dynamic output rendering

> 📁 File: `mongodb.py`  
> 🔧 Great for: Beginners trying out Streamlit widgets

---

### 🔹 2. **Hello Streamlit-er! App**
A super basic, goofy welcome app where:

- You greet the user
- Hit a button for surprise balloons 🎈

> 📁 File: `rainbow.py`  
> 🎉 Mood: Fun & friendly dev playground

---

### 🔹 3. **AGC All-in-One ML Dashboard**
This is where the real action happens! 👇

💼 Features:
- Generate random data using NumPy & Pandas  
- Visualize it using both Streamlit line chart & Matplotlib scatter plot  
- Train a simple Linear Regression model with scikit-learn  
- Predict on user input  
- Upload a CSV and preview data  
- Use Streamlit’s session state to count stuff  
- Form inputs + success messages  
- Download random data as CSV 🎯

> 📁 File: `streamlitapp.py`  
> 💡 Tech Stack: Streamlit + scikit-learn + Matplotlib + Pandas + NumPy

---

## 🛠️ Installation & Setup

```bash
# 1. Clone the repo
git clone https://github.com/deepikaparasa6/MongoDb_Project.git
cd MongoDb_Project

# 2. Create virtual environment
python -m venv venv

# 3. Activate the environment
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run any app!
streamlit run mongodb.py
# or
streamlit run rainbow.py
# or
streamlit run streamlitapp.py
