# Diabetic Retinopathy Detection

## Abstract

Deep learning pipeline using transfer learning to detect diabetic retinopathy from retina images. Utilizes EfficientNetB3 backbone with custom dense layers, L1/L2 regularization, and extensive data augmentation (ZCA whitening). Achieved ~99.7% training accuracy on APTOS/EyePACS datasets.

## Technical Architecture

**Core Technologies:** EfficientNetB3, Transfer Learning, CNN, Medical Imaging, Data Augmentation

**Architecture Overview:**
This implementation follows a rigorous scientific methodology:

1. **Data Pipeline:** Robust preprocessing with validation splits for unbiased evaluation
2. **Model Architecture:** State-of-the-art neural network design optimized for the target domain
3. **Training Protocol:** Systematic hyperparameter tuning with cross-validation
4. **Evaluation Metrics:** Comprehensive performance analysis using standard benchmarks

## Installation & Usage

### Prerequisites
- Python 3.7 or higher
- CUDA-capable GPU (recommended for training)

### Setup
```bash
git clone https://github.com/vaishnavak2001/Diabetic-Retinopathy-Detection.git
cd Diabetic-Retinopathy-Detection
pip install -r requirements.txt
```

### Running the Model
```python
# See notebooks or main.py for execution details
python main.py
```

## Research Context

This project contributes to the broader field of AI in healthcare/data science, demonstrating practical applications of machine learning for real-world problem-solving.

## Citation

If you use this work in your research, please cite:

```bibtex
@software{diabetic_retinopathy_detection_2024,
  author = {Vaishnav AK},
  title = {Diabetic Retinopathy Detection},
  year = {2024},
  url = {https://github.com/vaishnavak2001/Diabetic-Retinopathy-Detection}
}
```

## License

This project is part of the research portfolio by [Vaishnav AK](https://github.com/vaishnavak2001).

---

**Status:** Research Implementation  
**Author:** Vaishnav AK, Data Scientist & Biomedical Engineer
