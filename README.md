# 🏠 Bengaluru House Price Prediction

An end-to-end Machine Learning project that predicts house prices based on location, size, and amenities.

## 🚀 Features
- Trained ML model using scikit-learn
- Flask backend API for predictions
- Simple frontend UI (HTML/CSS/JS)
- Real-world dataset (Bengaluru housing)

## 🧠 Tech Stack
- Python
- Flask
- scikit-learn
- Pandas, NumPy
- HTML, CSS, JavaScript

## 📂 Project Structure
```
BHP/
├── Client/        # Frontend
├── Server/        # Flask backend
├── Model/         # Training notebook/code
├── Server/artifacts/ # Model + columns
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation

```bash
git clone <your-repo-url>
cd BHP
pip install -r requirements.txt
```

## ▶️ Run the Project

```bash
cd Server
python server.py
```

## 🔌 API Example

POST /predict

```json
{
  "location": "Indira Nagar",
  "sqft": 1200,
  "bath": 2,
  "bhk": 3
}
```

## 📸 Screenshots
<img width="1200" height="700" alt="project_screenshot" src="https://github.com/user-attachments/assets/529beeeb-0663-4e8f-8573-d9a9d2014355" />


## 📌 Future Improvements
- Deploy backend (Render / Railway)
- Deploy frontend (Netlify)
- Add authentication
- Improve model accuracy

## 👨‍💻 Author
Ankit
