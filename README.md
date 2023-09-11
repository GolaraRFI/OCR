# OCR

![scanned](https://github.com/GolaraRFI/OCR/assets/80590542/38040edd-19fd-4c7e-9f2f-9254d5ab1465)

# Persian Identity Card OCR System

This project is a simple Optical Character Recognition (OCR) system that utilizes OpenCV, ArabicOcr, and pytesseract to extract personal information from Persian Identity Cards. It is designed with beginners in mind, offering a straightforward implementation that covers the core principles of OpenCV, ArabicOcr, and pytesseract.

## Requirements:

Before you get started, ensure you have the following dependencies installed:

```python
pip install opencv-python-headless
pip install ArabicOcr
pip install pytesseract
sudo apt-get install tesseract-ocr-fas
```
Project Steps:
1. Extract Binary Information:
In this step, extraneous data is removed from the image, retaining only the necessary information in a binary image.

2. Extract Each Part Separately:
Here, non-numeric information is saved in separate images.

3. Preprocess Numbers:
This step involves the analysis of numeric information. Numbers are processed one by one, with zeros and ones being recognized through image processing. Slashes are removed, and numbers between them are extracted.

4. Testing:
In this phase, ArabicOcr and pytesseract are employed to extract the remaining information. The extracted information from this step is then combined with the information from the image processing step to produce the final result.

Useful Links:

Document Scanner: https://github.com/murtazahassan/Document-Scanner.git

Tesseract OCR: https://github.com/tesseract-ocr/tesseract.git
