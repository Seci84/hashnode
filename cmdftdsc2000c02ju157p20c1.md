---
title: "About Me"
datePublished: Wed Jul 23 2025 10:22:05 GMT+0000 (Coordinated Universal Time)
cuid: cmdftdsc2000c02ju157p20c1
slug: about-me
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1753326433910/bcdd1aab-35d8-451b-ba7b-241e3fd9ee90.png
tags: ml-engineer, ai-engineer, model-optimization, infrastructurengineer

---

I’m an AI engineer with extensive experience in model development, optimization, and deployment. My passion lies in building intuitive and efficient ecosystems and platforms for developers. I believe that the future of AI lies in the seamless integration of high-performance AI hardware—such as Tenstorrent—and developer-friendly software stacks.

I aim to unlock the full potential of AI semiconductors by optimizing models and designing accessible APIs, making it easier for developers to leverage hardware acceleration without deep hardware expertise. Through personal experiments and projects, I’ve been exploring developer-centric AI workflows on platforms like Tenstorrent’s TT-Metalium.

---

## Key Projects

### 1\. Automated Digital Catalog System

**Overview:**  
Developed an end-to-end pipeline that extracts structured product information from unstructured Excel line sheets and classifies products into categories.

**Contributions:**

* Designed a term dictionary to standardize varied formats (e.g., *Gender: W, femme, donna*) using GPT-3.5 and LlamaParse
    
* Automatically extracted column names and normalized tables using LlamaIndex and MarkdownElementNodeParser
    
* Built semantic vector indices and recursive query structures using `recursive_query_engine` for context-aware retrieval
    
* Implemented a RESTful API to auto-upload extracted JSON data into the catalog system
    

**Tech Stack:**  
LlamaParse, GPT-3.5, LlamaIndex, `recursive_query_engine`, REST API

This project strengthened my ability to build developer-friendly data pipelines using tools like LlamaIndex and REST APIs. It also demonstrated how efficient LLM inference can be scaled on platforms like Tenstorrent for optimized AI workflows.

---

### 2\. Multimodal Category Classification Model & ONNX Optimization

**Overview:**  
Built a multimodal classification model combining LSTM, 1D-CNN, and MobileNetV3 for text and image data, and optimized its inference performance.

**Contributions:**

* Merged Word2Vec-based text embeddings and MobileNetV3 image features into a Dense classification model
    
* Converted the Keras model to ONNX and accelerated inference with ONNX Runtime, reducing latency from 38.28ms to 4.96ms (87% improvement) and model size from 17.4MB to 5.63MB (68% reduction)
    
* Applied float16 quantization with &lt;0.5% accuracy loss
    

**Results:**  
Achieved 82.49% validation accuracy with significantly improved inference performance

**Tech Stack:**  
TensorFlow, Keras, Word2Vec, MobileNetV3, tf2onnx, ONNX Runtime, MLflow

This experience with ONNX optimization directly supports efficient inference on AI chips and contributes to designing tools and APIs that abstract hardware complexity for developers.

---

### 3\. Personal Research: NLP Pipeline on Tenstorrent TT-Metalium

**Overview:**  
Exploring a lightweight NLP pipeline optimized for Tenstorrent hardware using its open-source software stack, TT-Metalium.

**Research Focus:**

* Converting LlamaIndex-based vector indices to ONNX format and implementing optimized inference on Tenstorrent hardware (e.g., Grayskull)
    
* Experimenting with text embedding generation efficiency using Tenstorrent's high-throughput architecture
    

This research deepens my understanding of integrating AI semiconductor performance with accessible development environments. It also reflects my interest in contributing to platforms that bridge cutting-edge hardware and flexible software for developers.

---

## Vision

I believe that the power of AI hardware lies not only in performance, but in its accessibility through well-designed ecosystems. I’m particularly interested in designing APIs, tools, and workflows that help developers harness the efficiency of AI chips like Tenstorrent—without being burdened by low-level hardware details.

Through hands-on experimentation and practical deployments, I aim to contribute to building integrated platforms that connect innovative AI hardware and developer-friendly software, and to collaborate with AI semiconductor designers to shape the next generation of AI systems.