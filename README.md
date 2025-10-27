# Python-based-text-to-image-generator
This project lets you generate high-quality images from text prompts.

==================================================
No API keys. GPU acceleration supported.
--------------------------------------------------------
Features:
--------------------------------------------------------
- Text-to-Image generation
- Image-to-Image generation 
- Based on Stable Diffusion Pipeline
- Tkinter GUI and Flask Web UI 
- Transparent PNG output
- Output folder + preview + download

--------------------------------------------------------
System Requirements:
--------------------------------------------------------
- OS: Windows / Linux / macOS
- Python: 3.10.x (strictly recommended)
- RAM: 8GB minimum (16GB+ recommended)
- CUDA GPU (optional but strongly recommended)

--------------------------------------------------------
Installation:
--------------------------------------------------------

1. Create Virtual Environment (optional but recommended)
--------------------------------------------------------
    python -m venv venv

    # Activate it:
    - On Windows:
        venv\Scripts\activate
    - On macOS/Linux:
        source venv/bin/activate

2. Install Requirements
--------------------------------------------------------
Create a file named requirements.txt and paste:

    torch
    torchvision
    diffusers
    transformers
    safetensors
    pillow
    flask

Then install with:
    pip install -r requirements.txt

3. Download the Model File
--------------------------------------------------------
Model: realisticVisionV60B1_v51HyperVAE.safetensors  
Source: https://civitai.com/models/4201/realistic-vision-v60

Place this file in the same directory as `app.py` or `gui.py`

4. Run the Application
--------------------------------------------------------

- To run the web app (Flask):
    python app.py
    → open http://127.0.0.1:5000/ in browser

- To run the desktop GUI (Tkinter):
    python gui.py
--------------------------------------------------------


