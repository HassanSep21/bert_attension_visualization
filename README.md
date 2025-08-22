# 📌 BERT Attention Visualizer

> An interactive NLP tool that predicts masked words using BERT and generates beautiful visual heatmaps of transformer attention patterns across all layers and heads.

---

## ✨ Features

- Predicts top-K missing words using pre-trained BERT-base-uncased
- Generates 144 detailed heatmap diagrams (12 layers × 12 heads)
- Real-time word prediction with confidence scoring
- High-quality PNG attention diagrams with professional formatting
- Visualizes how different attention heads focus on various linguistic patterns

---

## 🛠 Tech Stack

- **Languages:** Python
- **Frameworks/Libraries** TensorFlow, Transformers (Hugging Face), BERT-base-uncased, PIL, NumPy, AutoTokenizer
- **Tools:** Git, VS Code
---

## 🧠 Model Architecture

**BERT Transformer Analysis:**
- **Model:** BERT-base-uncased (110M parameters)
- **Layers:** 12 transformer layers
- **Attention Heads:** 12 heads per layer
- **Total Visualizations:** 144 attention pattern diagrams
- **Tokenization:** WordPiece with 30,522 vocabulary

---

## 🎨 Visualization Features

**Professional Attention Diagrams:**
- **Grid-based Layout** - Each token pair represented as a colored cell
- **Grayscale Intensity** - Darker cells indicate higher attention scores
- **Rotated Labels** - Clean column headers for better readability
- **Custom Typography** - OpenSans font for professional appearance
- **High Resolution** - Scalable output suitable for research publications
