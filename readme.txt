readme_content = """
<h1 align="center">🍔🍟🍗 Meal analysis with Theseus 🍞🍖🍕</h1>

<p align="center">
  <a><img src="./static/assets/demo/pipeline.png" alt="Pipeline Diagram: Image to Detection, Classification, Segmentation, and Nutritional Analysis"></a>
  <br>
</p>

<p align="center">
  <a href="./LICENSE"><img src="https://img.shields.io/github/license/Naereen/StrapDown.js.svg" alt="MIT License" /></a>
  <a href="https://www.codefactor.io/repository/github/lannguyen0910/food-recognition/overview/master"><img src="https://www.codefactor.io/repository/github/lannguyen0910/food-recognition/badge/master?s=9716a4eb0076053fa36e0d967bba5161b85b8fb5" alt="CodeFactor Grade" /></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg" alt="Made with Python" /></a>
  </p>

---

## ✨ Project Overview

**Meal Analysis with Theseus** is a versatile **Computer Vision** project designed for comprehensive analysis of food images. Built upon the powerful **YOLO** (You Only Look Once) architecture and the **Theseus** template, this system performs **Object Detection**, **Classification**, and **Semantic Segmentation** to accurately identify food and provide instant nutritional insights.

### 🎯 Key Features

* **Multi-Task Analysis:** Seamlessly integrates Detection (YOLOv5/v8), Classification (EfficientNet), and Segmentation (UNet++) for robust results.
* **Nutritional Integration:** Queries the **Edamam API** to provide estimated caloric and macronutrient data for detected food items.
* **Ensemble Modeling:** Uses **Weighted Box Fusion** to combine predictions from multiple models, increasing overall accuracy.
* **Efficient Caching:** Utilizes **Perceptual Hash** encryption to cache processed images, speeding up repeated analysis and parameter tuning.
* **Interactive Web App:** Includes a **Flask**-based server and frontend using **Chart.js** for interactive data visualization.

---

## 🌳 **Folder Structure**

A clear folder structure helps contributors navigate the codebase quickly.

<details>
  <summary><strong>Details</strong></summary>