# Flask Project

This is a simple starter Flask project created in **VS Code**.

## 📂 Project Setup

### 1. Create Project Folder
```bash
mkdir flask_project
cd flask_project
```

### 2. Open in VS Code
Open the folder `flask_project` in **Visual Studio Code**.

---

## 🐍 Virtual Environment

### Create Virtual Environment
```bash
python -m venv venv
```

### Activate Environment
- **Windows (PowerShell):**
```powershell
.\venv\Scripts\activate
```

- **Linux / macOS:**
```bash
source venv/bin/activate
```

---

## 📦 Install Flask

```bash
pip install flask
```

---

## 📝 Create `app.py`

```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "Hello, Flask!"

if __name__ == "__main__":
    app.run(debug=True)
```

---

## ▶ Run the App

```bash
python app.py
```

Then open in browser:
```
http://127.0.0.1:5000/
```

---

## ⚙ Optional: VS Code Debug Configuration
1. Go to **Run and Debug** in sidebar.
2. Click **Add Configuration...**
3. Select **Python: Flask**.
