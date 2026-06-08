# OCR
这是一个OCR手写字识别模型，主要用于单据、报表等。
This is an OCR handwritten character recognition model, mainly used for documents, reports, etc.

# 📝 企业级手写单据 OCR 与结构化信息提取系统
> **Handwritten Document OCR & Structured Data Extraction System**

[![ModelScope](https://img.shields.io/badge/ModelScope-Models-blueviolet)](https://www.modelscope.cn/search?page=1&search=OCR&type=model)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97-HuggingFace-yellow)](https://huggingface.co/zai-org/GLM-OCR)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Framework](https://img.shields.io/badge/Framework-PyTorch-orange)

本项目旨在解决企业日常业务中面临的手写单据录入效率低、人工成本高的核心痛点。通过自主研发的“手写字体识别与结构化数据录入系统”，深度融合了图像处理 (CV)、深度学习 (Deep Learning) 与自然语言处理 (NLP) 技术，实现对手写单据的自动化高精度识别与结构化提取。

---

## 📢 商业合作与技术交流

💡 **本项目涉及企业核心业务，模型已调试完成并成功交付使用。** 我们支持根据企业需求**定制专属企业级 App / 系统**，欢迎洽谈合作。

* **⚡ 性能指标**：识别成功率高达 **99%**，单张单据平均处理耗时仅 **3s**。
* **📨 联系我们**：[yaxiguba766@gmail.com](mailto:yaxiguba766@gmail.com)
* **🔬 开源核心算法参考**：
    * [ModelScope 算法库](https://www.modelscope.cn/search?page=1&search=OCR&type=model)
    * [HuggingFace GLM-OCR](https://huggingface.co/zai-org/GLM-OCR)

---

## ✨ 核心成果

* **降本增效**：显著提升了数据录入效率，大幅降低人力成本。
* **高鲁棒性**：克服了手写字体连笔、潦草、背景干扰等难题，实现了极高的识别精度。
* **商用落地**：目前该项目已完成企业级部署，并正式投入实际生产应用，获得业务部门的高度认可。

---

## 🚀 核心功能 | Key Features

* **智能图像预处理**：自动进行倾斜校正、去噪、二值化及表格线消除，提升复杂背景下单据的清晰度。
* **高精度手写体 OCR**：基于深度学习视觉模型，精准识别中英文混合、连笔、潦草手写体。
* **智能结构化提取**：结合命名实体识别与版面分析，自动将识别出的长文本解析为结构化字段（如：姓名、金额、日期、物料编号等）。
* **企业级高可用架构**：提供标准化 RESTful API 接口，支持高并发请求与异步处理，无缝对接企业现有 ERP/OA 系统。

---

## 🛠️ 技术栈 | Tech Stack

* **核心语言**：Python 3.8+
* **计算机视觉**：OpenCV, PIL, Scikit-image
* **深度学习框架**：PyTorch

---

## 📊 效果展示 | Demo & Visualization
<img width="959" height="688" alt="6773a357-279c-4e9d-b06b-986dc9506240" src="https://github.com/user-attachments/assets/95f725ad-846f-49bc-b871-cff4b3faec32" />
<img width="1152" height="598" alt="image" src="https://github.com/user-attachments/assets/df1e1c53-d02b-44d0-8773-60a64605ba52" />
<img width="1044" height="580" alt="image" src="https://github.com/user-attachments/assets/85d05fb4-ffe4-472f-afb2-cd6558d8adc1" />
<img width="831" height="380" alt="image" src="https://github.com/user-attachments/assets/880d0eef-64ac-407c-b3e8-d4ea08d1c76f" />



