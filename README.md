# 🏅 Sports Video Classification using VGG

This project applies **deep learning and computer vision** to classify sports videos by analyzing frames. It uses a **VGG-based CNN** model for feature extraction and classification.

---

## 🚀 Features
- Frame-level extraction from videos
- Preprocessing and normalization of video frames
- Transfer learning using pretrained VGG16
- Classification of sports categories (e.g., Football, Cricket, Tennis, Basketball)
- Visualization of results and predictions

---

## 📂 Project Structure
sports-video-classifier-vgg/
│── Sports Video Classification @ Frame Based.ipynb
│── src/
│── data/
│── results/
│── requirements.txt
│── Sample.mp4
│── vgg.keras

yaml
Copy code

---

## ⚙️ Installation
```bash
git clone https://github.com/venkatesh-data/sports-video-classifier-vgg.git
cd sports-video-classifier-vgg
pip install -r requirements.txt

---

🧠 Model
The model uses VGG16 pretrained on ImageNet and fine-tuned on sports video frames. Each video is processed frame-by-frame, and predictions are averaged for final classification.

---

▶️ Usage
bash
Copy code
python src/frame_extraction.py --video data/test_videos/sample.mp4
python src/predict.py --model vgg.keras --frames data/frames/

Or simply open and run the notebook:

mathematica
Copy code
Sports Video Classification @ Frame Based.ipynb

---

📊 Example Output
Video	Predicted Sport	Confidence
sample.mp4	Football	0.92


🧩 Requirements
Python 3.9+

TensorFlow / Keras

OpenCV

NumPy

Matplotlib

Install all dependencies:

bash
Copy code
pip install -r requirements.txt

---

📈 Future Improvements
Real-time video stream classification

Use 3D CNNs (ConvLSTM) for spatiotemporal learning

Integrate Grad-CAM visualizations for interpretability

---

🧑‍💻 Author
Venkatesh
Data Scientist | Deep Learning & AI Enthusiast
📧 [LinkedIn or GitHub link here]

---

📜 License
This project is licensed under the MIT License.
