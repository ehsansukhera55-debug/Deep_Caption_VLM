# DeepCaption

An AI-powered image captioning tool using BLIP (Vision Language Model) that runs completely locally — no API key required.

## Features
- Generate captions for any image
- Custom prompt support
- Works offline after first model download
- No API key or internet required

## Installation

git clone https://github.com/yourusername/Deep_Caption_VLM.git
cd VisionScribe
pip install -r requirements.txt


## Usage
```python
from captioner import caption_from_file

# Default caption
caption = caption_from_file("image.jpg")

# Custom prompt
caption = caption_from_file("image.jpg", "list all objects in this image")

print(caption)
```

## Model
Uses [Salesforce BLIP](https://huggingface.co/Salesforce/blip-image-captioning-base) — downloaded automatically on first run (~1GB).
```

---

### Your final project structure should look like:
```
DeepCaption/
│
├── deep_caption_VLM.ipynb        # main script
├── requirements.txt    # dependencies
└── README.md           # project description
