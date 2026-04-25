# RSS-News-Intelligence
# News Classification with BERTopic

[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.9+-red.svg)](https://pytorch.org/)
[![BERTopic](https://img.shields.io/badge/BERTopic-0.13+-green.svg)](https://maartengr.github.io/BERTopic/)

## 📊 Project Overview
A complete news analytics system that:
- **Collects** live news from RSS feeds (BBC, Al Jazeera, TechCrunch, etc.)
- **Classifies** articles into 6 categories using DistilBERT (79% accuracy)
- **Discovers** emerging topics using BERTopic topic modeling

## 🎯 Features
- ✅ Real-time RSS feed collection with retry logic
- ✅ DistilBERT-based classification (79% accuracy)
- ✅ BERTopic emerging topic detection
- ✅ Interactive topic visualizations (HTML)
- ✅ Data augmentation for small datasets
- ✅ Class balancing with weighted sampling

## 📈 Results
| Metric | Score |
|--------|-------|
| Accuracy | 79.03% |
| F1-Score | 79.17% |
| Topics Discovered | 9 |

## 🛠️ Tech Stack
- **Classification**: DistilBERT (fine-tuned)
- **Topic Modeling**: BERTopic + Sentence Transformers
- **Data Collection**: feedparser, requests
- **Visualization**: matplotlib, seaborn, plotly

## 🚀 Quick Start
```bash
git clone https://github.com/YOUR_USERNAME/News-Classification-BERTopic.git
cd News-Classification-BERTopic
pip install -r requirements.txt
python code.py
