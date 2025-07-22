

# 🧠 TalkLens – Lip Reading Model for Real-Time Video Calling

**TalkLens** is an intelligent video calling application designed to facilitate one-to-one communication by interpreting lip movements into readable text. This project focuses on implementing and comparing state-of-the-art **Lip Reading (Visual Speech Recognition)** models to assist individuals with speech impairments.

---

## 📌 What is Lip Reading?

**Lip Reading**, or **Visual Speech Recognition (VSR)**, is the process of understanding speech by analyzing the speaker's lip movements. It enables silent communication by interpreting visual cues instead of relying on audio.

---

## 🎯 Project Objective

The primary objective of this project is to:
- Perform a **comparative analysis** of various lip-reading techniques.
- Explore multiple **deep learning architectures** for lip movement interpretation.
- Identify the most **accurate and real-time deployable models** for the TalkLens video calling app.

---

## 🛠️ Approach & Methodology

### 📚 Literature Review
We surveyed a wide range of research papers and implementations to select both traditional and modern lip-reading models.

### ✅ Model Selection
The following models were selected for implementation and evaluation:
- **LipNet**
- **Watch, Listen, Attend and Spell (WLAS)**
- **TM-seq2seq**
- **AV-HuBERT**

Pre-trained weights were obtained when available to ensure a fair comparison.

### 📊 Evaluation Metrics
- **Word Error Rate (WER)**
- **Character Error Rate (CER)**
- **Real-Time Inference Speed**
- **Model Size and Latency**

---

## 🚀 Dataset Used

Models were evaluated on standard benchmark datasets such as:
- [GRID Corpus](http://spandh.dcs.shef.ac.uk/gridcorpus/)
- [LRS2](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs2.html)

---

## 🧪 Results & Findings

- Each model was evaluated on a consistent test dataset.
- **LipNet** and **AV-HuBERT** offered strong accuracy, while **WLAS** was better suited for real-time performance.
- A trade-off analysis was conducted to recommend the best model for **real-time deployment** in the TalkLens app.

---

## ✅ Final Outcome

- Identified top-performing models based on both **accuracy** and **latency**.
- Recommended lightweight, high-performance models suitable for integration into the TalkLens real-time lip-reading pipeline.

---


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
>>>>>>> a3ea84bf4d69fa07d95038509bee5a51ca9539fd

