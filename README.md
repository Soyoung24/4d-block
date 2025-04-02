## 딥러닝을 활용한 교육용 포디블록 교구의 쌓기구조 패턴 추출  

### Extracting Stacking Structure Pattern of Educative 4DBlock Material Utilizing Deep Learning


#### 📖 Project Overview
This project implements a deep learning-based approach for extracting stacking structure patterns from educational 4D block materials. By defining 10 types of building structures and applying multi-label classification with EfficientNet-B3, the model is trained to recognize complex stacking patterns. To enhance interpretability, Grad-CAM is used to visualize model predictions.


#### ⚠️ Notice

- **The training dataset cannot be provided**.
- The full training process is documented in `train/train_classification_eff3.ipynb`.
- Dependencies required for training are listed in `train/requirements.txt`.
- This project was developed with **Python 3.8**.
- The `streamlit/` folder provides a simple interface where you can test inference using sample images or your webcam with real 4D blocks.


#### ▶️ How to Run Streamlit App

```bash
cd streamlit
streamlit run app.py
