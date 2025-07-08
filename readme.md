🪪 PAN Card Detection:
A Python-based project that detects a PAN card in an image, extracts key details like PAN number, name, and date of birth using OCR and validates the information.

📌 Objective
To automatically detect and extract information from an image of an Indian PAN Card using Computer Vision and Optical Character Recognition (OCR) techniques.

📷 What the Project Does (in Steps)
Step 1: Input Image
Accepts an image containing a PAN card (JPEG, PNG, etc.)

It can be a full photo, scanned image, or camera snapshot

Step 2: Image Pre-processing
Converts the image to grayscale

Applies noise removal and thresholding

Optionally detects the document area and crops it using contour detection

Step 3: Text Extraction (OCR)
Uses Tesseract OCR to extract all visible text from the PAN card area

Extracts raw text including name, PAN number, and DOB

Step 4: Text Parsing and Validation
Applies regex to:

Detect and validate the PAN Number (Format: ABCDE1234F)

Extract the Name and Date of Birth

Validates the extracted text to match expected formats

Step 5: Display or Save Output
Prints or saves:

PAN Number

Name

Date of Birth

Optionally saves cropped PAN image and extracted text to a file

🧠 Technologies and Libraries Used
Component	Technology
Programming Language	-->Python 3.12
Image Processing	-->OpenCV
OCR Engine	-->Tesseract OCR
Text Parsing	-->Python re (regex)
(Optional) DL Models	-->YOLO / CRNN

🔐 Privacy Note
Please ensure:

PAN data is processed locally and securely

Avoid storing or sharing personal data unless necessary

Mask sensitive data in any logs or exported files

💡 Future Improvements
Add GUI using Streamlit or Flask

Use deep learning for better card detection (YOLO/EAST)

Export output in formats like PDF or Excel

Support for batch image processing

🤝 Contribution Guidelines
Contributions, bug reports, and feature requests are welcome!
Please fork the repository and submit a pull request.

📄 License
This project is licensed under the MIT License.
