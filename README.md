# Speech-Emotional-Recognitional-A-Machine-Learning-Based-Approach
Speech Emotional Recognition(SER) system that classifies emotions and predicts intensity from voice,. Using RAVDESS dataset, features(MFCC, Chrome, Mel Spectrogram) are extracted with Librosa and modeled with random forest. Supported real time prediction, reliable accuracy, and application in HCI, mental health, and virtual assistants.
<img width="966" height="643" alt="Screenshot 2025-09-01 120245" src="https://github.com/user-attachments/assets/f070a798-3908-4dc5-84ec-7436dcb7252a" />


#  Speech Emotion Recognition - Implementation with Random Forest  

##  Project Overview  
This project implements a Speech Emotion Recognition (SER) system using the RAVDESS dataset. It classifies emotions (happy, sad, angry, neutral) and predicts their intensity levels from both pre-recorded and real-time audio input. 

![Flow of SER](https://github.com/user-attachments/assets/6581a75f-b5d9-42a4-b453-9c082915e77c)

##  Features  
- Supports **.WAV audio files** and **real-time microphone input**  
- Feature extraction with **MFCC, Mel Spectrogram, Chroma (Librosa)**  
- Preprocessing with **Label Encoding & Train-Test Split**  
- Dual-model approach:  
  - **Random Forest Classifier (RFC)** → Emotion classification  
  - **Random Forest Regressor (RFR)** → Emotion intensity prediction  
- Provides accuracy, confusion matrix, and classification report
   <img width="932" height="572" alt="Screenshot 2025-05-07 190351" src="https://github.com/user-attachments/assets/e2fa7911-2748-4de4-a415-870e75a5060e" />



##  Dataset  
- **RAVDESS dataset** with labeled emotional speech samples  
- Emotions: Happy, Sad, Angry, Neutral  
- Includes **intensity values** for regression  

##  How to Run  
1. Clone this repo  
2. Open the `.ipynb` notebook in **Jupyter/Google Colab**  
3. Install dependencies: `librosa`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`  
4. Run the notebook step by step to train and test the model  

##  Results  
- Achieved reliable accuracy for multi-class emotion classification  
- **Confusion Matrix & Classification Report** for evaluation  
- Regression model successfully predicted **emotion intensity (0–1 scale)**  
- Visualization with matplotlib & seaborn  

##  Real-Time Testing  
- Model tested with **live microphone input**  
- Predicted both **emotion label** and **intensity percentage**  

##  Applications  
- Emotion-aware virtual assistants  
- Human-computer interaction systems  
- Mental health monitoring tools  
- Affective computing research
