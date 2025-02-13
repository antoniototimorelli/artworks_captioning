# Image Captioning Comparison: BLIP vs BLIP-2

This repository contains a Jupyter Notebook that fine-tunes and compares the performance of two image captioning models: a quantized version of **BLIP** and **BLIP-2**.

Dataset is [Best Artworks of All Time](https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time) with captions (machine generated) from [here](https://github.com/tunib-ai/artwork_captions).

## Features
- **Uses two different models**: [BLIP quantized](https://huggingface.co/gospacedev/blip-image-captioning-base-bf16) and [BLIP-2](https://huggingface.co/Salesforce/blip2-opt-2.7b).
- **Explores LoRA**.
- **Explores quantization**.
- **Compares baseline vs. fine-tuned models**.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Open the Jupyter Notebook through [Google Colab](https://colab.research.google.com/).

3. Execute the cells to compare BLIP and BLIP-2.

## License
This project is open-source and available under the [MIT License](LICENSE).
