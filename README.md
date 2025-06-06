# 🖐️ SignSpeaks: Real-Time Indian Sign Language (ISL) Translation using Generative AI & LLMs  

![SignSpeaks Banner]([https://your-image-link-here.com](https://www.livelaw.in/h-upload/2019/07/09/750x450_362025-isl.jpg))  

## 📌 Project Overview  
SignSpeaks is an AI-powered **real-time Indian Sign Language (ISL) translation system** that converts ISL gestures into **text and speech**. It leverages **LLaMA-2 (LLM) for text processing** and **GANs for ISL image generation**, improving accessibility for the deaf and hard-of-hearing community.  

### ✨ Key Features  
✅ **ISL to Text/Speech** – Uses **CNN + LLaMA-2** for accurate ISL recognition and **gTTS** for speech synthesis.  
✅ **Text to ISL Gesture Generation** – Implements **cGANs & Stable Diffusion** to generate ISL images from text.  
✅ **Real-Time Gesture Recognition** – Detects **hand landmarks** using **MediaPipe Hands**.  
✅ **End-to-End AI Pipeline** – Uses **Deep Learning, Generative AI, and NLP techniques**.  

---

## 🛠️ Technologies Used  
🔹 **Deep Learning:** Convolutional Neural Networks (CNNs), Generative Adversarial Networks (GANs)  
🔹 **Large Language Models (LLMs):** LLaMA-2 for text processing  
🔹 **Computer Vision:** OpenCV, MediaPipe Hands for gesture detection  
🔹 **NLP & Speech:** Hugging Face Transformers, gTTS for speech synthesis  
🔹 **Frameworks:** TensorFlow, PyTorch  


## 🚀 Installation & Setup  
### **1️⃣ Clone the Repository**  
```bash  
git clone https://github.com/Krishna6475/SignSpeaks-Real-Time-ISL-Translation.git  
cd SignSpeaks-Real-Time-ISL-Translation  
```

### **2️⃣ Install Dependencies**  
```bash  
pip install -r requirements.txt  
```

---

## 📊 Dataset  
The model is trained on a curated **Indian Sign Language (ISL) dataset**, which consists of:  
- **ISL Gesture Images** (A-Z, 0-9)  
- **Hand Landmarks Extracted using MediaPipe**  
- **Annotated Text for Gesture Classification**  

---

## 📈 Model Architecture  
📌 **Phase 1: ISL to Text/Speech Translation**  
1️⃣ **CNN + LLaMA-2** for ISL gesture classification  
2️⃣ **BERT-based text refinement** for structured sentence formation  
3️⃣ **gTTS for speech output**  

📌 **Phase 2: Text to ISL Gesture Generation**  
1️⃣ **Conditional GANs (cWGAN-GP)** for ISL image generation  
2️⃣ **Stable Diffusion for high-quality gesture synthesis**  

---

## 🤝 Contribution Guidelines  
Contributions are welcome! Follow these steps to contribute:  
1. **Fork the repository**  
2. **Create a new branch** (`git checkout -b feature-branch`)  
3. **Commit your changes** (`git commit -m "Add new feature"`)  
4. **Push to GitHub** (`git push origin feature-branch`)  
5. **Create a Pull Request**  

---

## 📜 License  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  

---

## 📩 Contact & Acknowledgments  
👤 **Chinthagunta Vamshi Krishna**  
✉️ Email: [my_mail](mailto:vamshikrishna6475@gmail.com)  
🔗 LinkedIn: [my LinkedIn Profile](https://www.linkedin.com/in/vamshi-krishna-chinthagunta-73321625b/)  

💡 **Acknowledgments:**  
- Inspired by **research in AI-driven ISL translation**.  
- Special thanks to **academic mentor** for guidance.  

---

🚀 *SignSpeaks is an ongoing research project and is currently in the process of being published. Due to publication constraints, not all models and implementation details have been included in this repository. Feel free to reach out for further discussions.*  
