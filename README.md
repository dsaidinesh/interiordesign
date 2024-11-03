# Interior Design Style Transfer with ComfyUI

This repository contains workflows and instructions for performing interior design style transfer using ComfyUI.

## Installation

### Option 1: Standard Installation

1. **Download ComfyUI**
   ```bash
   git clone https://github.com/comfyanonymous/ComfyUI.git
   cd ComfyUI
   ```

2. **Set up Python Virtual Environment**
   ```bash
   python -m venv venv
   
   # For Linux/macOS
   source venv/bin/activate
   
   # For Windows
   venv\Scripts\activate
   ```

3. **Install Requirements**
   ```bash
   pip install -r requirements.txt
   ```

### Option 2: Alternative Installation
If you're not familiar with Git or command-line interfaces, you can follow the detailed setup guide on [Stable Diffusion Art](https://stable-diffusion-art.com/comfyui/), which provides step-by-step instructions and troubleshooting tips.

## Getting the Workflow

### Option 1: Clone Repository
```bash
git clone https://github.com/dsaidinesh/interiordesign.git
```

### Option 2: Direct Download
1. Download the workflow file `final_Dr.json` directly from this repository:
   - Click on `final_Dr.json` in the repository files
   - Click the "Download" button or "Raw" button and save the file
   - Save it in a location you can easily find on your computer

## Workflow Setup

### Loading the Workflow

1. **Start ComfyUI**
   ```bash
   python main.py
   ```

2. **Import the Workflow**
   - Open ComfyUI in your web browser
   - Go to the File menu
   - Select "Import JSON"
   - Upload the `final_Dr.json` file that you either cloned or downloaded

### Running the Workflow

1. **Prepare Your Images**
   - Load your reference (target room) image
   - Load your style image

2. **Execute the Workflow**
   - Configure any necessary parameters
   - Run the workflow to generate the styled output

## Requirements

- Python 3.8 or higher
- CUDA-compatible GPU (recommended)
- Sufficient disk space for models and generated images

## Contributing

If you'd like to contribute to this project, please:
1. Fork the repository
2. Create your feature branch
3. Submit a pull request



## Acknowledgments

- ComfyUI team for their excellent platform
