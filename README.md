🖼️ Image-to-Text Generator using OCR

A Python-based tool to extract text from images using Optical Character Recognition (OCR). This project leverages Tesseract OCR and OpenCV to convert scanned documents, screenshots, and handwritten content into machine-readable text.

📌 Features

Upload and process image files (.png, .jpg, .jpeg)

Extract text using pytesseract

Image preprocessing (grayscale, thresholding, noise removal)

Jupyter Notebook implementation for easy modification and experimentation

Display and save extracted text

🔬 Use Cases
Document digitization

Extracting data from scanned papers

Text mining from images for NLP

Academic research and automation

Assistive tools for the visually impaired

🧠 Tech Stack

Python 3.x

OpenCV

Pytesseract (Tesseract OCR)

NumPy

Matplotlib

⚙️ Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Ayush0135/image-to-text-generator.git
cd image-to-text-generator
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Install Tesseract OCR engine:

Ubuntu:

bash
Copy
Edit
sudo apt install tesseract-ocr
macOS (with Homebrew):

bash
Copy
Edit
brew install tesseract
Windows:
Download and install from: https://github.com/tesseract-ocr/tesseract

Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook image_to_text_generator.ipynb
📁 File Structure
arduino
Copy
Edit

📦 image-to-text-generator/

 ┣ 📄 image_to_text_generator.ipynb
 ┣ 📄 requirements.txt
 ┗ 📁 sample_images/

✅ Sample Output

Extracted text from a sample image using the pipeline.

🚀 Future Work

GUI/Web interface (e.g., Streamlit/Gradio)

Multilingual OCR support

Integration with NLP pipelines (summarization, translation)

Batch image processing

Text post-processing using AI

🙌 Acknowledgements

Tesseract OCR
OpenCV
