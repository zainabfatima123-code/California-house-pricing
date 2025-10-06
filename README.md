# 🏠 CALIFORNIA HOUSE PRICING

## 🧰 Software and Tools Required
1. GitHub Account: https://github.com
2. VS Code IDE: https://code.visualstudio.com/
3. Heroku Account (optional): https://heroku.com
4. Git CLI: https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line
5. Python 3.7+

---

## ⚙️ Setup and Run the Application

```bash
echo "Creating virtual environment for Windows and macOS/Linux"
python -m venv venv
python3 -m venv venv

echo "Activating virtual environment"
venv\Scripts\activate
source venv/bin/activate

echo "Upgrading pip and installing dependencies"
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt

echo "Running the application"
python app.py

echo "Application is now running! Open your browser and go to http://127.0.0.1:5000/"
