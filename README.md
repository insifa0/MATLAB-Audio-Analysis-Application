# **MATLAB Audio Analysis Application**

### **Overview**
This MATLAB application allows users to analyze audio files, predict the genre of the audio, and visualize key characteristics such as the spectrogram, STFT energy distribution, and signal waveform. 

The application supports different pre-trained models for classification and enables the extraction of audio features.

---

### **Features**
- **Audio File Selection**: Load `.wav` files for analysis.
- **Genre Classification**: Predict the genre of a song using machine learning models.
- **Visualization**:
  - Signal Graph
  - Spectrogram
  - STFT Energy Distribution
  - Percentage Predictions for Genres
- **Model Selection**: Choose from a variety of machine learning models:
  - Fine Tree
  - Medium Tree
  - Coarse Tree
  - Linear SVM
  - Fine KNN
  - Medium KNN
  - Coarse KNN
  - Boosted Trees
  - Narrow Neural Network
  - Medium Neural Network
  - Quadratic SVM

---

### **Prerequisites**
1. **MATLAB** (App Designer supported version)
2. Pre-trained models (`.mat` files):
   - `QuadraticSVM.mat`
   - `FineTree.mat`, `MediumTree.mat`, `CoarseTree.mat`
   - `LinearSVM.mat`
   - `FineKNN.mat`, `MediumKNN.mat`, `CoarseKNN.mat`
   - `BoostedTrees.mat`
   - `NarrowNeuralNetwork.mat`, `MediumNeuralNetwork.mat`
3. Audio files in **WAV** format.

---

### **Screenshots**
Here are some screenshots to illustrate the application's interface and features:

1. **Main Interface**  
   ![Main Interface](screenshots/main_interface.png)

2. **Signal Graph Visualization**  
   ![Signal Graph](screenshots/signal_graph.png)

3. **STFT Energy Distribution**  
   ![STFT Energy](screenshots/stft_energy.png)

4. **Genre Prediction Results**  
   ![Genre Prediction](screenshots/genre_prediction.png)

5. **Spektogram Graph**  
   ![Spektogram Graph](screenshots/Spektogram.png)
   

---

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/audio-analysis-matlab.git
