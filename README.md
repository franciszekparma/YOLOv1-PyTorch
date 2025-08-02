# YOLO V1 from Scratch

**A deep dive into every component of the YOLO V1 object detector**—from data download and preprocessing, through network architecture and loss derivation, all the way to training loops, evaluation, and inference. Whether you’re completely new to YOLO or you’re looking to understand the nitty-gritty details under the hood, this repo has you covered.

---

## 📚 What’s Inside

- **YOLO-V1-Explanation.ipynb**  
  A _fully annotated_ Jupyter notebook that walks you through:
  1. **Resources & References**  
     - Link to the original [YOLO V1 paper](https://arxiv.org/abs/1506.02640)  
     - Recommended video tutorials  
  2. **Getting the Data**  
     - Downloading Pascal VOC via `opendatasets`  
     - Directory structure and file formats  
  3. **Libraries & Imports**  
     - PyTorch, torchvision, NumPy, Matplotlib, etc.  
  4. **Utility Functions**  
     - Intersection over Union (IoU)  
     - Bounding box conversions  
     - Non-Max Suppression  
  5. **Model Architecture**  
     - Grid split, convolutional backbone, prediction heads  
     - Tensor shapes at every stage  
  6. **Loss Function**  
     - Mathematical derivation of the YOLO loss  
     - PyTorch implementation with detailed comments  
  7. **Data Configuration & Augmentation**  
     - Hyperparameters (S, B, class count)  
     - Random flips, color jitters, scaling  
  8. **Dataset & DataLoader**  
     - Custom `Dataset` class  
     - Collate functions for variable-length targets  
  9. **Training Loop**  
     - Epoch/iteration structure  
     - Logging losses and metrics  
     - Checkpoint saving  
  10. **Evaluation & Metrics**  
      - Computing mAP  
      - Precision/Recall curves  
  11. **Inference Demo**  
      - Running on new images  
      - Visualizing bounding boxes  

- **YOLO-V1-Pure-Code.ipynb**  
  The same code cells—**no markdown**, no commentary—so you can:
  - Quickly run an end-to-end training demo  
  - Benchmark on your own images  
  - Integrate into larger projects without extra text  

---

## 🔍 Repository Structure
