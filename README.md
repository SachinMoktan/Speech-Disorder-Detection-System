# 🧠 AI-Based Speech Disorder Detection System

##  Overview
Early detection of speech disorders in children is crucial for timely intervention and effective treatment. Traditional diagnostic methods often require expert evaluation and can be time-consuming.

This project develops an **AI-based speech analysis system** that processes audio recordings of children's speech to detect early signs of potential speech disorders using machine learning techniques.



##  Objectives
- Detect speech disorders using audio data  
- Extract meaningful features from voice recordings  
- Train machine learning models for classification  
- Compare model performance  
- Support early diagnosis using AI  



##  Tools & Technologies
- Python  
- Librosa (Audio Processing)  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Google Colab  



##  Dataset
- Audio recordings of children’s speech  
- Includes:
  - Normal speech samples  
  - Disordered speech samples  



##  Methodology

### 1. Audio Preprocessing
- Trimmed long audio clips  
- Removed noise and silence  
- Standardized audio format  



### 2. Feature Extraction
Extracted key audio features using **Librosa**:

- MFCC (Mel-Frequency Cepstral Coefficients)  
- Spectral features  
- Frequency-based characteristics  



### 3. Model Development

Models used:
- Random Forest Classifier  
- Neural Network  



### 4. Model Evaluation
Models were evaluated based on:
- Accuracy  
- Precision  
- Recall  



## 📈 Results

- Random Forest provided stable and interpretable results  
- Neural Network improved classification capability with complex patterns  
- MFCC features were highly effective in distinguishing speech patterns  



## 🔍 Key Insights

- Audio features like MFCC play a crucial role in speech classification  
- Machine learning can assist in early detection of speech disorders  
- Proper preprocessing significantly improves model performance  
- AI can support healthcare professionals in diagnosis  



## 💡 Real-World Impact

This system can help:

- Early identification of speech disorders in children  
- Assist speech therapists and healthcare professionals  
- Improve accessibility to diagnostic tools  
- Enable faster intervention and treatment  



## 🚀 Future Improvements

- Deploy as a mobile application  
- Integrate real-time voice input  
- Expand dataset for better accuracy  
- Use deep learning (CNN, RNN) for improved performance  

