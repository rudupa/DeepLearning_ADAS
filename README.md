# 🚗 Deep Learning for ADAS — A Beginner's Learning Repository

> **Advanced Driver Assistance Systems (ADAS)** rely heavily on deep learning for perception, prediction, and planning. This repository is a structured, hands-on guide to learn the key deep learning architectures used in modern ADAS — from foundational CNNs to cutting-edge Vision-Language-Action (VLA) models.

---

## 📚 Who Is This For?

- Engineers/students with **basic Python knowledge**
- Anyone curious about **how self-driving cars perceive the world**
- Beginners who want a **structured path** from neural network basics to state-of-the-art models

---

## 🗺️ Learning Roadmap

```
┌─────────────────────────────────────────────────────────────────┐
│                    LEARNING PATH                                │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  01. Foundations ──► NumPy, PyTorch, Autograd, Neural Nets      │
│         │                                                       │
│         ▼                                                       │
│  02. CNNs ────────► Conv Layers, ResNet, Object Detection       │
│         │                                                       │
│         ▼                                                       │
│  03. RNNs ────────► LSTM, GRU, Sequence Modeling                │
│         │                                                       │
│         ▼                                                       │
│  04. Transformers ► Attention, ViT, DETR                        │
│         │                                                       │
│         ▼                                                       │
│  05. LLMs ────────► GPT, Tokenizers, Fine-Tuning                │
│         │                                                       │
│         ▼                                                       │
│  06. VLMs ────────► CLIP, Multimodal Understanding              │
│         │                                                       │
│         ▼                                                       │
│  07. VLAs ────────► Vision-Language-Action, End-to-End Driving  │
│         │                                                       │
│         ▼                                                       │
│  08. ADAS Apps ───► Lane Detection, Sensor Fusion, Planning     │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📂 Repository Structure

```
DeepLearning_ADAS/
│
├── 01_Foundations/
│   ├── 01_python_numpy_basics.ipynb
│   ├── 02_pytorch_tensors_autograd.ipynb
│   └── 03_first_neural_network.ipynb
│
├── 02_CNNs/
│   ├── 01_convolution_fundamentals.ipynb
│   ├── 02_cnn_architectures.ipynb
│   └── 03_object_detection_adas.ipynb
│
├── 03_RNNs/
│   ├── 01_rnn_fundamentals.ipynb
│   └── 02_lstm_gru_sequence_modeling.ipynb
│
├── 04_Transformers/
│   ├── 01_attention_mechanism.ipynb
│   ├── 02_vision_transformer_vit.ipynb
│   └── 03_detr_object_detection.ipynb
│
├── 05_LLMs/
│   ├── 01_tokenization_embeddings.ipynb
│   ├── 02_gpt_architecture.ipynb
│   └── 03_finetuning_prompt_engineering.ipynb
│
├── 06_VLMs/
│   ├── 01_clip_multimodal_basics.ipynb
│   └── 02_vlm_for_adas.ipynb
│
├── 07_VLAs/
│   ├── 01_vla_concepts.ipynb
│   └── 02_end_to_end_driving.ipynb
│
├── 08_ADAS_Applications/
│   ├── 01_lane_detection.ipynb
│   └── 02_sensor_fusion_planning.ipynb
│
├── resources/
│   ├── FREE_BOOKS.md
│   ├── PAPERS.md
│   ├── COURSES_AND_VIDEOS.md
│   └── DATASETS.md
│
├── images/                 # Diagrams and figures
├── requirements.txt
└── README.md
```

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/DeepLearning_ADAS.git
cd DeepLearning_ADAS
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter
```bash
jupyter notebook
```

---

## 🔗 Quick Links to Resources

| Resource | Description |
|----------|-------------|
| [Free Books](resources/FREE_BOOKS.md) | Curated list of free deep learning & ADAS books |
| [Research Papers](resources/PAPERS.md) | Key papers for each architecture |
| [Courses & Videos](resources/COURSES_AND_VIDEOS.md) | Free online courses and YouTube playlists |
| [Datasets](resources/DATASETS.md) | Datasets for practicing ADAS tasks |

---

## 🧠 Key Concepts Covered

| Module | Key Topics | ADAS Relevance |
|--------|-----------|----------------|
| **Foundations** | Tensors, Autograd, MLPs | Building blocks for all models |
| **CNNs** | Convolution, Pooling, ResNet | Image classification, object detection |
| **RNNs** | LSTM, GRU, Sequences | Temporal sensor data, trajectory prediction |
| **Transformers** | Self-Attention, ViT, DETR | State-of-the-art detection & segmentation |
| **LLMs** | GPT, Tokenization, Fine-tuning | In-cabin assistants, scene description |
| **VLMs** | CLIP, Image-Text Matching | Scene understanding, anomaly detection |
| **VLAs** | Action Prediction, E2E Driving | End-to-end autonomous driving |
| **ADAS Apps** | Lane Detection, Sensor Fusion | Real-world ADAS pipelines |

---

## 📄 License

This repository is for **educational purposes**. All referenced materials belong to their respective authors.

---

*Happy Learning! 🚀*
