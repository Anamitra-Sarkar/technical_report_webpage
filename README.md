# Technical Research Portal

A dynamic, serverless web portal for hosting and visualizing advanced technical research papers on Machine Learning, Neural Architectures, and GPU Optimization.

**Live Demo:** View on GitHub Pages (Note: Link will be active once Pages is enabled)

🚀 Overview

This repository hosts a custom-built web application that renders technical research reports directly from Markdown/HTML into a modern, interactive reading environment. It is designed to be lightweight, responsive, and aesthetically optimized for reading dense technical content (math, code, and benchmarks).

## Key Features

- Serverless Architecture: Runs entirely on the client-side using Vanilla JS; no backend required.
- Dynamic Content Loading: Fetches research papers asynchronously and renders them in an immersive modal view.
- Dark/Light Mode: Includes a robust theme switcher with local storage persistence.
- PDF Export: Built-in functionality to download any research paper as a formatted PDF.
- Math Support: Integrated MathJax for rendering complex LaTeX equations in real-time.

## 📚 Research Papers

The portal currently hosts the following in-depth technical reports:

- **Memory-Efficient Transformer Architectures**  
  Topic: Optimizing VRAM usage for LLM training using FlashAttention, GQA, and mixed precision.  
  Focus: Strategies for constrained hardware (L4/T4 GPUs).

- **Advanced GPU Optimization Techniques**  
  Topic: A practical guide to CUDA memory management, kernel fusion, and distributed training (FSDP/DDP).  
  Focus: Maximizing throughput and GPU utilization on A100/H100 clusters.

- **Sequence Models: From RNNs to Transformers**  
  Topic: A comprehensive historical and mathematical analysis of RNNs, LSTMs, GRUs, and the Transformer revolution.  
  Focus: Architecture comparison and use-case selection in 2025.

- **Why Quantization Matters in 2025**  
  Topic: Deep dive into INT8, FP16, BF16, NF4, GPTQ, and AWQ quantization methods.  
  Focus: Deploying 70B+ parameter models on consumer hardware.

- **Self-Rewriting Neural Architectures**  
  Topic: A foundational theoretical framework for networks that dynamically alter their topology during training.  
  Focus: Gradient field geometry, information load, and structural morphogenesis.

## 🛠️ Technology Stack

- Frontend: HTML5, CSS3 (Custom Properties for theming), Vanilla JavaScript (ES6+)

Libraries:
- html2pdf.js: For client-side PDF generation.
- MathJax: For LaTeX equation rendering.

Hosting: GitHub Pages (Static hosting).

## 📖 How to Run Locally

Clone the repository:

```bash
git clone https://github.com/Anamitra-Sarkar/technical_report_webpage.git
```

Navigate to the folder:

```bash
cd technical_report_webpage
```

Launch:
Simply open `index.html` in your web browser.  
Note: For the best experience (and to avoid CORS issues with local file fetching), it is recommended to run a simple local server:

```bash
# Python 3
python -m http.server 8000
```

Then visit http://localhost:8000.

## 📬 Contact

Author: Anamitra Sarkar  
GitHub: Anamitra-Sarkar  
Email: anamitrasarslsn10ab@gmail
