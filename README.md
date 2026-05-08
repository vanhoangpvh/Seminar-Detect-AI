# AI-Generated Vietnamese Text Detector

A robust system designed to detect and classify AI-generated Vietnamese text. This project features the creation of a specialized dataset and the fine-tuning of advanced Transformer models to accurately distinguish between human-written and AI-generated content.

## Key Features

* **VSM-D Dataset**: Curated a custom dataset containing over 50,000 samples sourced from Noron.vn and Wikipedia. Data generation utilized advanced **Prompt Engineering** techniques (Zero-shot and Role-playing) to capture both formal and conversational nuances.
* **Robust Data Pipeline**: Implemented a comprehensive pipeline for text normalization and heuristic de-biasing to strip structural AI markers, forcing the model to learn stylistic nuances rather than trivial keywords.
* **State-of-the-Art Performance**: Fine-tuned multiple Transformer architectures. Our **CafeBERT** model achieved an outstanding F1-score of **98.54%**, outperforming multilingual baselines (like mDeBERTa) by approximately 8%.

## Pre-trained Models & Resources

You can download the fully trained models, datasets, and setup files directly from our Google Drive repository:

👉 **[Download Models and Setup Files Here](https://drive.google.com/drive/folders/15NOz8KQ_RgUk67oiLyoIzwgCAySgLgr9?fbclid=IwY2xjawPjzVNleHRuA2FlbQIxMABicmlkETFWQ1JqVHFaejZDVjh6RTFXc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHkJZ5rvcm7i3_5ZkStXHQNzrz70k1RqesnA2_TG4h7okCxmYfzPaGX_c2iX__aem_AnRxDWCdlHfd6M3Sf9jM9Q)**

## Contribution & Support

Contributions are welcome! If you encounter any bugs, setup failures, or have suggestions for improvements, please feel free to open an **Issue** in this repository or contact me directly for assistance.
