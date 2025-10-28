🧠 Realtime Sign Language Recognition using YOLOv8 and HDNN

A deep learning–based system for **real-time sign language recognition**, combining **YOLOv8** for gesture detection and a **Hierarchical Deep Neural Network (HDNN)** for gesture classification.  
This project aims to support accessibility and human-computer interaction through AI-driven visual recognition.


🚀 Features
- Real-time detection and classification of sign language gestures  
- Trained using YOLOv8 for fast and accurate bounding-box detection  
- HDNN architecture for robust multi-level gesture recognition  
- Dataset preprocessing and augmentation with Roboflow  
- Flask/Streamlit interface for real-time camera inference  


🧩 Tech Stack
**Languages & Frameworks:** Python, PyTorch, OpenCV, YOLOv8  
**Libraries:** NumPy, Pandas, Matplotlib, TensorFlow/Keras  
**Tools:** Roboflow, Jupyter Notebook, Flask/Streamlit  
**Model:** YOLOv8 (for detection) + HDNN (for classification)


📁 Project Structure
├── app.py # Web app for real-time testing
├── run.py # Script to run YOLOv8 + HDNN model
├── data.yaml # Dataset configuration file
├── train/valid/test # Dataset directories
├── yolov8n.pt # Pretrained weights (linked below)
├── Untitled.ipynb # Notebook for model training
├── README.md # Documentation
└── results/ # Output visualizations

yaml
Copy code


🧠 How It Works
1. **YOLOv8** detects the hand region and key gestures in real time.  
2. The cropped image is passed to **HDNN**, which classifies the specific sign.  
3. Output is displayed as recognized text on the user interface.



⚙️ Setup Instructions

1️⃣ Clone Repository
---bash
git clone [https://github.com/yourusername/sign-language-recognition-yolov8-hdnn.git](https://github.com/Mohiuddin2003/sign-language-recognition-yolov8-hdnn.git)
cd sign-language-recognition-yolov8-hdnn

2️⃣ Install Dependencies
---bash
Copy code
pip install -r requirements.txt

3️⃣ Download Pretrained Model
Download YOLOv8 weights and place them in the project directory:
🔗 Download yolov8n.pt
(If trained custom model is large, link to Google Drive instead.)

4️⃣ Run Application
bash
Copy code
python app.py

🧾 Dataset
The dataset was prepared using Roboflow, containing labeled hand gesture images representing different alphabets and actions.
Dataset link (if available): Google Drive / Roboflow Dataset Link

📊 Results
Achieved high recognition accuracy (>90%) for known gestures.

Real-time processing with low-latency inference.

Works efficiently on standard GPU systems.

🧩 Future Improvements
Expand dataset to support multi-language gestures

Integrate with mobile and web apps for accessibility tools

Add voice synthesis for recognized gestures

📸 Preview

<img width="1240" height="665" alt="Screenshot 2025-10-29 011713" src="https://github.com/user-attachments/assets/45f60f0c-6b56-4fae-8890-71c7caf34155" />
<img width="1241" height="662" alt="Screenshot 2025-10-29 011737" src="https://github.com/user-attachments/assets/c67c6c41-e56c-4048-ba42-37f0158ad4a6" />
<img width="1238" height="666" alt="Screenshot 2025-10-29 011758" src="https://github.com/user-attachments/assets/4e5449c4-7487-440b-97ff-2d54ffb260ac" />
<img width="1240" height="664" alt="Screenshot 2025-10-29 011830" src="https://github.com/user-attachments/assets/a09d6ee2-afb6-4b9a-881c-1a9469f966c6" />
<img width="1238" height="659" alt="Screenshot 2025-10-29 011844" src="https://github.com/user-attachments/assets/ed0d98fe-a46b-4dce-b7ba-2614319d284e" />
<img width="1240" height="663" alt="Screenshot 2025-10-29 011857" src="https://github.com/user-attachments/assets/2dd9073b-6407-4012-a0ad-43ffef348278" />
<img width="1241" height="663" alt="Screenshot 2025-10-29 011913" src="https://github.com/user-attachments/assets/f06a3bdb-8b8e-49c3-a171-99fdfe6194a4" />
<img width="1242" height="662" alt="Screenshot 2025-10-29 011926" src="https://github.com/user-attachments/assets/e68343bb-90cd-4249-89e0-38e2530d13d7" />
<img width="1243" height="663" alt="Screenshot 2025-10-29 012118" src="https://github.com/user-attachments/assets/675e4e15-6903-4ae6-88f6-4de75822bc9c" />
<img width="1237" height="665" alt="Screenshot 2025-10-29 012127" src="https://github.com/user-attachments/assets/b1f6c94b-9734-4098-a3fa-15b81834bda3" />


👨‍💻 Author
Mohammed Mohiuddin Khan
📧 mohimaaz2003@gmail.com
🔗 LinkedIn
www.linkedin.com/in/mohammed-mohiuddin-khan-m2003

