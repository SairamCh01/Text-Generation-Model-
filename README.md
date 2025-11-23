# Text-Generation-Model-
# GPT-2 Text Generator (Gradio + HuggingFace Transformers)

A simple and interactive **GPT-2 text generation web app** built using **Gradio** and the **HuggingFace Transformers (dev version)**.  
Users can input any sentence and generate coherent continuations using OpenAI's GPT-2 language model.


## Features

- Interactive web UI using **Gradio**
- GPT-2 (PyTorch) text generation
- Improved results using **Beam Search**
- Clean dark UI theme
- Fully compatible with **Google Colab**
- Lightweight and easy to run


## Installation

Install all required packages:

```bash
pip install gradio
pip uninstall -y sentence-transformers
pip install git+https://github.com/huggingface/transformers.git
```


# How it Works
1. User enters text in input field.
2. Text is tokenized using GPT-2 tokenizer.
3. The model generates text using Beam Search for higher-quality output.
4. Output is cleaned and displayed in the UI.


# Model Details 

+ Model: GPT-2 (Small)
+ Framework: PyTorch
+ Library: HuggingFace Transformers (dev version)
+ Generation: Beam Search (num_beams=5)
+ Max tokens generated: 120

**License**
This project is available under the Apache License 2.0
