
# Interpretable ConvLSTM: Understanding Spatiotemporal Predictions

This repository provides Jupyter notebooks implementing various interpretability methods for an encoder-decoder model with ConvLSTM layers. The goal is to analyze how spatiotemporal dependencies influence wind speed forecasting predictions.

## 📂 Contents

The repository contains six Jupyter notebooks, each dedicated to a specific interpretability technique:

1. **Permutation Importance** - Evaluates feature importance by shuffling input features and measuring the impact on predictions.
2. **Feature Ablation / Noise Injection** - Tests model robustness by replacing or perturbing specific input features.
3. **Saliency Maps** - Highlights regions in the input that most influence predictions using gradient-based methods.
4. **Smooth Saliency Maps** - Enhances standard saliency maps by applying smoothing techniques.
5. **Occlusion** - Masks parts of the input to analyze their effect on predictions.

## 🚀 Getting Started

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/ConvLSTM-xAI.git
   cd ConvLSTM-xAI
   ```
2. Install dependencies (if required):
   ```
   pip install -r requirements.txt
   ```
3. Open the notebooks and run the experiments:
   ```
   jupyter notebook
   ```

## 📌 Notes

* The interpretability methods help identify which temporal frames or spatial regions are most relevant for accurate wind speed forecasting.
* The model analyzed is an **encoder-decoder ConvLSTM** trained on spatiotemporal wind speed data.

## 📜 License

This project is open-source and available under the [MIT License]().

## ✉️ Contact

For questions or collaborations, feel free to open an issue or reach out!
