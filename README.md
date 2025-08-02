# YOLOv1-PyTorch

A **deep dive** into every component of the YOLO V1 object detector — from **downloading and preparing the Pascal VOC data, through network architecture and loss formulation**, all the way to **training, evaluation, and real-time inference.** This repository is designed to give you a **clear, end-to-end understanding** of how YOLO V1 works under the hood in PyTorch.

---

## Repository Structure

YOLOv1-PyTorch/
├── YOLO V1/                          # directory containing both notebooks
│   ├── YOLO-V1-Explanation.ipynb     # highly comprehensive deep-dive notebook: full theory, derivations, annotated PyTorch code, visualization of results, and explanatory images for clarity
│   │   • Pascal VOC download & preprocessing  
│   │   • Detailed model architecture breakdown  
│   │   • Loss function derivation & implementation  
│   │   • Training loop with logging & checkpoints  
│   │   • Inference examples with visualization  
│   └── YOLO-V1-Pure-Code.ipynb       # end-to-end pipeline: pure code only (no extra commentary)
│       • Data loading  
│       • Model definition  
│       • Loss & optimization  
│       • Training & evaluation  
│       • Inference with bounding box visualization  
├── sheep.png                         # sample inference result on a sheep image  
├── biker.png                         # sample inference result on a bicycle image  
└── README.md                         # this document  

---

## Notebooks Overview

- **YOLO-V1-Explanation.ipynb**  
  A comprehensive, annotated walkthrough. Explains *why* each component exists, how it’s implemented in PyTorch, and how data flows through the network.

- **YOLO-V1-Pure-Code.ipynb**  
  The identical implementation stripped of all commentary. Ideal for quick experiments, benchmarking, or integration into other projects.

---

## Sample Inference Results

Below are two example outputs produced by the YOLO V1 pipeline:

![Sheep detection result](https://github.com/franciszekparma/YOLOv1-PyTorch/blob/57fb191d9d4beee2dbec3a4bef721fbcf873ea2c/sheep.png)

![Bicycle detection result](https://github.com/franciszekparma/YOLOv1-PyTorch/blob/57fb191d9d4beee2dbec3a4bef721fbcf873ea2c/biker.png)

---

## Prerequisites

- **Python 3.7+**  
- **pip**  
- *(Optional)* CUDA-enabled GPU for accelerated training and inference

Install the required packages:

```bash
pip install torch torchvision opendatasets numpy matplotlib pillow tqdm
```

---

## Getting Started
1.	Clone the repository
```bash
git clone https://github.com/franciszekparma/YOLOv1-PyTorch.git
cd YOLOv1-PyTorch
```

2.	Launch Jupyter Lab or Notebook
```bash
jupyter lab   # or: jupyter notebook
```

3.	Open and run the notebooks
•	YOLO-V1-Explanation.ipynb for the full, annotated deep dive.
•	YOLO-V1-Pure-Code.ipynb for a no-frills, code-only run.


---

## Contributing

Contributions are welcome. Please open an issue or submit a pull request for:
•	Bug fixes
•	Performance optimizations
•	Support for additional datasets
•	Documentation improvements

---

## Acknowledgements
•	“You Only Look Once” (YOLO V1) by Joseph Redmon et al.
•	Aladdin Persson for providing Pascal VOC dataset via the opendatasets library.
•	Inspiration and reference code from Aladdin Persson’s PyTorch tutorials.
•	Tushar Kumar (ExplainingAI) for his theory-focused YOLO V1 tutorial.

---

License

This project is licensed under the MIT License.
© franciszekparma

