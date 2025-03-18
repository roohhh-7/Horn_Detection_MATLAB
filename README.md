# 🚗 Horn Detection using MATLAB  

## 📌 Overview  
This project detects horn sounds from audio recordings using **Digital Signal Processing (DSP)** techniques in MATLAB.  


## 🛠️ Features  
✔️ Reads and processes audio files.  
✔️ Converts stereo to mono.  
✔️ Applies **Butterworth bandpass filtering** to isolate horn sounds.  
✔️ Visualizes waveforms and spectrograms for analysis.  

## 🚀 How to Run  
1. **Clone the repository:**  
   ```sh
   git clone https://github.com/yourusername/Horn-Detection.git
   cd Horn-Detection

Open MATLAB and navigate to the code/ folder.
Run the detection script:
matlab

horn_detection
📜 Methodology
Preprocessing: Converts stereo to mono and normalizes the audio.
Filtering: Uses a Butterworth bandpass filter (300Hz – 3000Hz) to remove noise.
Analysis: Plots waveforms and spectrograms to verify horn detection
