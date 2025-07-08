🪪 PAN Card Detection
A computer vision and OCR-based project that detects and extracts information from Indian PAN cards using image processing and text recognition techniques.

📌 Features
📷 Detects and crops PAN card from an image

🔍 Extracts PAN number, name, and date of birth using OCR

✅ Validates extracted PAN numbers using regex

🧠 (Optional) Deep learning model for improved detection

🔐 Handles sensitive data with privacy considerations

🧠 Technologies Used
Component	Tool/Library
Programming Language -->	Python
Image Processing	-->OpenCV
OCR Engine	-->Tesseract OCR
Pattern Matching	-->Regular Expressions (re)
Deep Learning (Optional)	-->YOLO / CRNN / TensorFlow

🔧 Installation
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/pan-card-detection.git
cd pan-card-detection
Create a virtual environment (optional but recommended)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Install Tesseract OCR

Download and install from: https://github.com/tesseract-ocr/tesseract

Make sure to add Tesseract to your system PATH.

🚀 Usage
bash
Copy
Edit
python detect_pan.py --image sample_pan.jpg
You can also use this in a GUI or web application by integrating with Flask or Streamlit.

📝 Output
Extracted PAN Number: ABCDE1234F

Name: Siddharth Sharma

Date of Birth: 01/01/1990

(Optional): Cropped PAN card image saved as cropped_output.jpg

📁 Project Structure
graphql
Copy
Edit
pan-card-detection/
│
├── detect_pan.py             # Main detection script
├── utils/
│   ├── image_utils.py        # Image pre-processing
│   ├── ocr_utils.py          # OCR and text parsing
├── test_images/              # Sample PAN card images
├── requirements.txt
└── README.md
🛡️ Data Privacy Note
This project processes sensitive identity information. Ensure:

PAN card data is used responsibly

Output is not stored unless required

Personal data is masked or anonymized before sharing

📚 Future Enhancements
Add a Streamlit or Flask web interface

Use deep learning for more accurate card detection

Export results to PDF or JSON format

🤝 Contributing
Feel free to fork this repo and create pull requests. Contributions are welcome!

📄 License
This project is licensed under the MIT License.

