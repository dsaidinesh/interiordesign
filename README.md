Installation
Download ComfyUI
Follow the instructions on the ComfyUI GitHub page to download and set up ComfyUI on your system.

bash
Copy code
git clone https://github.com/comfyanonymous/ComfyUI.git
cd ComfyUI
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate  # For Windows
pip install -r requirements.txt
Clone This Repository

You can clone this repository or download the ZIP file.

bash
Copy code
git clone https://github.com/yourusername/interior-design-style-transfer.git
cd interior-design-style-transfer
Workflow Setup
Once you have ComfyUI set up, follow these steps to load and run the workflow.

Load the Workflow JSON
Open ComfyUI: Start ComfyUI by running:

bash
Copy code
python main.py
Import Workflow JSON: In ComfyUI, go to the File menu, select Import JSON, and upload the final_Dr.json file located in this repository.

Run the Workflow: Once imported, you should see the workflow nodes loaded into the ComfyUI workspace. To start the style transfer process:

Load your reference (target room) image and style image as specified in the workflow.
Execute the workflow to generate the styled output.
