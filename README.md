# 🦾 Bionic-Arm

> *"Prosthetics always intrigued me — out of empathy for amputees, I interned at NIT Rourkela under Prof. Prasoon Kumar in the BM department to develop a bionic arm."*

---

## 📌 Overview

A prosthetic arm control system powered by **EMG (Electromyography) signals**, combining signal processing, deep learning, and hardware-adaptive design to assist upper-limb amputees.

---

## 🧠 How It Works

1. **EMG Signal Acquisition**  
   Multi-channel EMG data is captured from residual limb muscles, recording electrical activity during intended movements.

2. **Feature Extraction & CNN Processing**  
   Meaningful muscle activity patterns are extracted and passed through a **dynamically designed CNN** to predict servo motor angles for actuation.

3. **MLP for Motor Control**  
   A **Multi-Layer Perceptron (MLP)** maps CNN outputs to precise servo angles, enabling fine-grained control of prosthetic fingers/joints.

4. **Hardware-Adaptive Sampling**  
   The system dynamically calculates **dilation rates and receptive fields** to ensure Action Potential (AP) data remains consistent regardless of the hardware's sampling rate.

---

## 🏗️ Architecture
EMG Sensors (multi-channel)
↓
Signal Preprocessing & Feature Extraction
↓
Dynamically Designed CNN
↓
Multi-Layer Perceptron (MLP)
↓
Servo Motor Angle Prediction
↓
Prosthetic Arm Actuation
---

## 📂 Repository Structure
Bionic-Arm/
├── BIONIC-ARM.ipynb
├── 3d printing notes by Rakshit.pdf
├── EMG + CNN notes by KC_compressed.pdf
├── NIT Rourkela PPT by KC.pdf
├── NIT Rourkela PPT by KC.pptx
└── README.md
---

## 🔬 Key Technical Highlights

| Feature | Detail |
|---|---|
| Input | Multi-channel EMG signals |
| Model | CNN + MLP hybrid |
| Output | Servo motor angles |
| Adaptability | Hardware-agnostic via dynamic dilation rates |
| AP Consistency | Maintained across variable sampling rates |

---

## 🛠️ Tech Stack

- **Python** — Core implementation
- **TensorFlow / Keras** — CNN & MLP modeling
- **NumPy / SciPy** — Signal processing
- **3D Printing** — Physical prosthetic arm fabrication

---

## 📁 Resources

🔗 [Google Drive Resource Folder](https://drive.google.com/drive/folders/1LErvzXufKl4FkV8KDJyog_BKixSNDOlu?usp=drive_link)

---

## 🎓 Internship Context

Developed during a research internship at **NIT Rourkela** under **Prof. Prasoon Kumar** (Biomedical Engineering Department).

---

## 📜 License

Licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

---

