# 📊 Datasets for Deep Learning & ADAS

A curated list of free datasets for practicing deep learning in autonomous driving and ADAS.

---

## 🚗 Autonomous Driving Datasets

### 1. KITTI Vision Benchmark Suite ⭐
- **URL:** https://www.cvlibs.net/datasets/kitti/
- **Size:** ~180 GB
- **Sensors:** Stereo cameras, LiDAR, GPS/IMU
- **Tasks:** 2D/3D detection, tracking, depth, optical flow, semantic segmentation
- **Why use it:** The classic autonomous driving benchmark. Great for starting out.

### 2. nuScenes ⭐
- **URL:** https://www.nuscenes.org/
- **Size:** ~300 GB
- **Sensors:** 6 cameras, 1 LiDAR, 5 radars, GPS/IMU
- **Tasks:** 3D detection, tracking, prediction, segmentation
- **Why use it:** Full 360° sensor coverage. Modern standard for 3D detection research.

### 3. Waymo Open Dataset ⭐
- **URL:** https://waymo.com/open/
- **Size:** ~1.5 TB
- **Sensors:** 5 cameras, 5 LiDARs
- **Tasks:** 2D/3D detection, tracking, domain adaptation, motion prediction
- **Why use it:** Largest, highest quality autonomous driving dataset. From the industry leader.

### 4. Argoverse 2
- **URL:** https://www.argoverse.org/
- **Size:** ~1 TB
- **Sensors:** 7 cameras, 2 LiDARs
- **Tasks:** 3D detection, motion forecasting, scene flow
- **Why use it:** Excellent for motion prediction and HD maps.

### 5. BDD100K
- **URL:** https://www.bdd100k.com/
- **Size:** ~20 GB
- **Sensors:** Dashboard camera
- **Tasks:** Detection, segmentation, lane marking, drivable area
- **Why use it:** Diverse driving conditions (weather, time of day, locations).

---

## 🛣️ Lane Detection Datasets

### 6. TuSimple Lane Detection
- **URL:** https://github.com/TuSimple/tusimple-benchmark
- **Size:** ~10 GB
- **Tasks:** Lane line detection on highways
- **Why use it:** Clean, well-annotated. Standard lane detection benchmark.

### 7. CULane
- **URL:** https://xingangpan.github.io/projects/CULane.html
- **Size:** ~40 GB
- **Tasks:** Lane detection in challenging conditions (night, rain, curves)
- **Why use it:** Diverse and challenging scenarios.

---

## 🖼️ General Computer Vision (Useful for Pretraining)

### 8. ImageNet (ILSVRC)
- **URL:** https://image-net.org/
- **Size:** ~150 GB
- **Tasks:** Image classification (1000 classes, 1.2M images)
- **Why use it:** Standard pretraining dataset for CNN backbones.

### 9. COCO (Common Objects in Context) ⭐
- **URL:** https://cocodataset.org/
- **Size:** ~25 GB
- **Tasks:** Detection, segmentation, captioning, keypoints
- **Why use it:** Rich annotations, standard detection benchmark.

### 10. Cityscapes
- **URL:** https://www.cityscapes-dataset.com/
- **Size:** ~50 GB
- **Tasks:** Semantic segmentation of urban scenes
- **Why use it:** Fine-grained urban scene understanding. Directly relevant to ADAS.

### 11. PASCAL VOC
- **URL:** http://host.robots.ox.ac.uk/pascal/VOC/
- **Size:** ~2 GB
- **Tasks:** Detection, segmentation (20 classes)
- **Why use it:** Small, easy to work with. Good for learning.

---

## 🧪 Simulators (Generate Unlimited Data)

### 12. CARLA Simulator ⭐
- **URL:** https://carla.org/
- **Type:** Open-source driving simulator (Unreal Engine)
- **Why use it:** Generate synthetic driving data with perfect ground truth. Test E2E driving models.

### 13. LGSVL Simulator
- **URL:** https://www.svlsimulator.com/
- **Type:** Autonomous vehicle simulator
- **Why use it:** High-fidelity simulation with sensor models.

### 14. AirSim (Microsoft)
- **URL:** https://github.com/microsoft/AirSim
- **Type:** Drone and car simulator
- **Why use it:** Easy to use, good for reinforcement learning experiments.

---

## 📝 NLP & Multimodal Datasets

### 15. DriveLM
- **URL:** https://github.com/OpenDriveLab/DriveLM
- **Tasks:** Language-annotated driving scenes (QA pairs)
- **Why use it:** Directly relevant for VLM/VLA research in driving.

### 16. nuScenes-QA
- **URL:** https://github.com/qiantianwen/NuScenes-QA
- **Tasks:** Visual question answering on driving scenes
- **Why use it:** Practice VQA for ADAS applications.

---

## 🎯 Getting Started Guide

### For Beginners (Small, Easy)
1. **PASCAL VOC** (~2 GB) — Learn object detection basics
2. **MNIST/CIFAR-10** (built into PyTorch) — Learn CNNs
3. **TuSimple** (~10 GB) — Learn lane detection

### For Intermediate (Standard Benchmarks)
4. **COCO** (~25 GB) — Standard detection/segmentation
5. **KITTI** (~180 GB) — Classic driving benchmark
6. **Cityscapes** (~50 GB) — Urban scene segmentation

### For Advanced (Large-Scale Research)
7. **nuScenes** (~300 GB) — Full 3D perception pipeline
8. **Waymo Open** (~1.5 TB) — State-of-the-art benchmark
9. **CARLA** (simulator) — End-to-end driving experiments

---

## 💡 Tips for Working with Datasets

```python
# Most datasets can be loaded with torchvision or HuggingFace
import torchvision.datasets as datasets

# CIFAR-10 (auto-download)
train = datasets.CIFAR10(root='./data', train=True, download=True)

# COCO (need to download separately)
# train = datasets.CocoDetection(root='./coco/train2017', annFile='./coco/annotations/instances_train2017.json')

# For nuScenes, Waymo, etc., use their official devkits:
# pip install nuscenes-devkit
# pip install waymo-open-dataset-tf
```

---

*Last updated: 2025. All datasets are free for research/educational use.*
