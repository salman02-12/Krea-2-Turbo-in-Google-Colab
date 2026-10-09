# ⚡ Krea-2 Turbo in Google Colab

This repository contains an easy-to-use Google Colab notebook for running the **Krea-2 Turbo Q5_K_M GGUF** model. Powered by a ComfyUI backend, it allows you to generate high-quality AI images rapidly using optimized GGUF files and FP8 text encoders on a free T4 GPU.

**🎥 Watch the Tutorial:** [How to Use](https://www.youtube.com/watch?v=soon)

**🚀 Run in Colab:** [Open Google Colab Notebook](https://colab.research.google.com/drive/1OPUso-UWTHyPprBVgINFncDqb0Bhs32I?usp=sharing)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/salman02-12/Krea-2-Turbo-in-Google-Colab/blob/main/Krea_2_Turbo_CoinNoin.ipynb)
[![Get Pro](https://img.shields.io/badge/Get%20Pro-PayPal-blue?logo=paypal)](https://www.paypal.com/ncp/payment/DEMO)

---
<img src="./thumbnail.png" width="100%" />

## ✨ Features Supported in this Notebook

This notebook automates the entire setup and generation process into 3 simple steps:

1. **⚙️ Initialize Core Environment**: Clones the ComfyUI engine and installs essential dependencies, including `gguf` and custom GGUF processing nodes.
2. **📥 High-Speed Asset Downloader & LoRA Setup**: Uses Aria2c to quickly download the `krea2_turbo-Q5_K_M.gguf` UNet, Qwen3-VL FP8 text encoder, and Qwen image VAE. It also includes a dedicated tool to upload custom `.safetensors` LoRAs directly from your computer or via URL.
3. **🎨 Image Generation**: A fully integrated UI for image creation. Features include:
   * **Prompts & LoRAs**: Enter positive and negative prompts, and easily apply custom LoRAs with adjustable strength.
   * **Turbo Settings**: Default settings are optimized for Turbo models (8 Steps, 1.0 CFG, Euler sampler, Beta scheduler) for incredibly fast generation.
   * **Custom Dimensions**: Sliders to easily adjust width, height, and batch size.
   * **Auto-download**: Save your final image directly to your local device.

## 🛠️ How to Use

1. Click the "Open in Colab" badge above.
2. Go to **Runtime > Change runtime type** in the top menu and ensure a **T4 GPU** is selected.
3. Run **Cell 1** to initialize the ComfyUI core environment.
4. Go to **Cell 2**. Select your `LORA_SOURCE` (None, Download from URL, or Upload from Computer), and hit Play to download all required models. 
5. Go to **Cell 3**. 
   * Enter your prompt (e.g., "A beautiful futuristic city at sunset").
   * Select your LoRA from the dropdown (or leave it as "None").
   * Adjust your resolution (Width/Height) and click Play.
   * The ComfyUI server will start in the background, process the request, and display your generated image right below the cell!

## 🤝 Credits
* **Notebook Creator:** [@CoinNoin](https://www.youtube.com/@CoinNoin)
* **Base Model (GGUF):** [VantageWithAI / Krea-2-Turbo-GGUF](https://huggingface.co/vantagewithai/Krea-2-Turbo-GGUF)
