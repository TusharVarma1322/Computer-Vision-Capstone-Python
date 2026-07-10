# OpenCV Setup (Conda)

Based on your provided instructions.

## 1) Create and activate environment

Open **Anaconda Prompt** (Run as Administrator on Windows), then:

```bash
conda -V
conda update conda
conda create -n capstone python=3.11 -y
conda activate capstone
```

## 2) Install OpenCV + NumPy

```bash
conda install -c conda-forge opencv numpy -y
```

## 3) Run project

```bash
python capstone_solution.py
```

## Alternative (pip)

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
pip install -r requirements.txt
python capstone_solution.py
```