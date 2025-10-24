# 🏠 California House Pricing Prediction

> 🚀 A Machine Learning web app that predicts California housing prices based on various input features such as location, income, and population.

---

## 🧠 Overview

This project leverages **Machine Learning** to estimate **house prices in California** using the popular [California Housing Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html).  
It includes a **Flask-based web interface** for real-time predictions and demonstrates a complete end-to-end ML workflow — from data preprocessing to model deployment.

---

## 🧰 Tech Stack

| Category | Tools / Technologies |
|-----------|----------------------|
| **Language** | Python 3.7+ |
| **Libraries** | NumPy, Pandas, Matplotlib, Scikit-learn, Flask |
| **IDE / Code Editor** | [VS Code](https://code.visualstudio.com/) |
| **Version Control** | [Git](https://git-scm.com/) & [GitHub](https://github.com) |
| **Deployment (Optional)** | [Heroku](https://www.heroku.com/) |

---

## ⚙️ Installation & Setup

Follow these steps to set up and run the project locally:

```bash
# 1️⃣ Clone the repository
git clone https://github.com/your-username/california-house-pricing.git
cd california-house-pricing

# 2️⃣ Create a virtual environment
python -m venv venv   # For Windows
python3 -m venv venv  # For macOS/Linux

# 3️⃣ Activate the environment
venv\Scripts\activate      # On Windows
source venv/bin/activate   # On macOS/Linux

# 4️⃣ Install dependencies
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt

# 5️⃣ Run the application
python app.py

