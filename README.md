# EN3160 – Assignment 02: Fitting and Alignment

This repo contains solutions for:
- **Q1**: Blob detection (LoG)
- **Q2**: Line & Circle estimation with RANSAC
- **Q3**: Image superimposing via homography
- **Q4**: Image stitching with SIFT + RANSAC

---

## Environment

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

pip install --upgrade pip
pip install numpy matplotlib opencv-python scikit-image scipy
