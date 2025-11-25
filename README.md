 
# Campus Placement Predictor 🎓🤖   
 
Campus Placement Predictor is a machine learning-based web application that predicts the placement probability of a student based on academic performance and skill attributes. Built using Flask, this lightweight app integrates a trained model to deliver instant predictions via a user-friendly interface.  
 
## 🚀 Features       
     
- 🎯 Predicts placement chances based on input attributes  
- 📊 Uses a trained scikit-learn classification model 
- 🌐 Built with Flask for rapid API + frontend integration   
- 📂 CSV dataset integrated for demo and retraining  
 
## 🛠 Tech Stack 

- **Python**
- **Flask**
- **scikit-learn**
- **HTML/CSS (Jinja Templates)**
- **Heroku-compatible Procfile**

## 🧪 Setup Instructions

```bash
git clone https://github.com/AnishPasupuleti/Campus_Placement_Predictor.git
cd Campus_Placement_Predictor
pip install -r requirements.txt
python app.py
```

Visit `http://localhost:5000/` in your browser.

## 📁 Files & Structure

```
├── app.py                     # Main Flask app
├── requirements.txt           # Dependencies
├── Placement_Data_Full_Class.csv
├── campusplacementpredictor.pkl  # Serialized model
├── templates/
│   ├── index.html
│   └── show.html
├── Deployment.md              # Deployment guide
├── Procfile                   # For Heroku deployment
```

## 🧠 Model Details

- Trained using Logistic Regression
- Features include:
  - SSC%, HSC%, Degree%, Work Experience, Specialization, etc.
- Pickled with `joblib` for fast Flask integration

## 🔮 Future Enhancements

- Add multiple model options (Random Forest, SVM)
- Integrate resume parsing for auto-input
- Connect with college portal systems

## 📜 License

This project is MIT licensed — feel free to fork and customize!

---

> Built by [Anish Pasupuleti](https://github.com/AnishPasupuleti)
