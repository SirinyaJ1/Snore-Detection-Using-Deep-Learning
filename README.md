# 💤 Snore Detection Using Deep Learning

This project uses deep learning techniques (Simple CNN & MobileNetV2) to detect snoring sounds from 1-second audio clips by converting them into spectrograms. The goal is to develop an effective and lightweight model that could be deployed in real-world healthcare applications such as sleep monitoring and early detection of sleep disorders.

## 📊 Project Highlights
- Dataset: 1,000 audio samples (balanced between snoring and non-snoring)
- Input: Mel Spectrograms (image-like representations of sound)
- Models: 
  - Simple 2D CNN (97% validation accuracy)
  - MobileNetV2 (96% validation accuracy using transfer learning)

## 🛠️ Tools & Libraries
- Python, Librosa, Matplotlib, TensorFlow / Keras, Scikit-learn

## 📁 Structure
- `/notebooks/`: Jupyter Notebooks for EDA and modeling
- `/src/`: Core scripts for preprocessing and training
- `/models/`: Trained model files
- `/images/`: Spectrograms and visualizations

## 📷 Example Spectrograms
<p align="center">
  <img src="images/spectrogram_examples/snoring.png" width="250">
  <img src="images/spectrogram_examples/non_snoring.png" width="250">
</p>

## 📈 Performance Comparison

![Model Comparison](images/performance_chart.png)

## 📌 Future Improvements
- Add more diverse and noisy samples for better generalization
- Use data augmentation techniques (e.g., time warping, frequency masking)
- Explore real-time deployment with model size optimization

## 🔗 References
- Buaruk & Deepaisarn (2023). Enhancing snoring detection...
- Khan, T.H. (2019). A deep learning model for snoring detection...

---

Feel free to fork or contribute!
