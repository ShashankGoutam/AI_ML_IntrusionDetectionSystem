# AI_ML_IntrusionDetectionSystem


# 🔐 Intrusion Detection System using Random Forest (Binary & Multi-class Classification)

## 📖 Project Overview
This project demonstrates a Machine Learning-based Intrusion Detection System (IDS) using the Random Forest Classifier.  
It classifies network traffic into either malicious or benign (binary classification) and also supports multi-class classification of various attack types using the NSL-KDD dataset.

## 📂 Project Structure
```
├── data/
│   ├── Train_data.csv
│   ├── Test_data.csv
├── notebooks/
│   ├── IDS_Model_Development.ipynb
├── outputs/
│   ├── test_predictions.csv
├── README.md
├── requirements.txt
└── report/
    ├── Project_Report.docx
    ├── Project_Presentation.pptx
```

## 📊 Dataset
We use the NSL-KDD dataset, an improved version of the KDD Cup '99 dataset. It includes labeled samples of network traffic.  
- `Train_data.csv` — Used to train the model  
- `Test_data.csv` — Used to validate the model  

Each row includes features like protocol type, service, flag, and connection-related metrics, along with a label.

## ⚙️ Tools & Libraries Used
- Python 3.x  
- Jupyter Notebook  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib / Seaborn (for visualization)

## 🧪 How it Works
1. **Data Preprocessing**
   - Label encoding of categorical features
   - Feature scaling using StandardScaler
   - Splitting into training, validation, and test sets

2. **Model Training**
   - A Random Forest Classifier is trained with 100 trees
   - Validated using accuracy and a detailed classification report

3. **Evaluation**
   - Displays precision, recall, F1-score
   - Output predictions stored in `test_predictions.csv`
   - Supports multi-class classification for different attack types

## 📈 Results
- ✅ Validation Accuracy: ~99.78%
- 📄 Classification Report: Precision, recall, and F1-score of nearly 1.00 across classes
- 🧠 Capable of detecting not only whether traffic is malicious but also the specific attack type

## 👥 Team Responsibilities
### Tanmay Vemuri
- Data Handling & Preprocessing  
- Dataset Loading, Encoding, Scaling, and Splitting  

### Shashank Goutam
- Model Training & Evaluation  
- Performance Reporting, Test Predictions, and Report Writing  

## 🚀 How to Run
1. Clone the repository
```bash
git clone https://github.com/yourusername/ids-random-forest.git
```

2. Open and run the notebook

```

## 🔐 Why This Project Matters
This IDS model offers a scalable, adaptable solution for real-time detection of cyber threats.  
It outperforms traditional rule-based systems by leveraging data-driven insights.

## 🛠️ Future Work
- Add support for real-time traffic detection  
- Integrate with SIEM tools (Security Information and Event Management)  
- Explore deep learning approaches  
- Visualize feature importance  


## 🚨 Disclaimer
This project is intended for educational purposes and not meant for production-grade deployment.
