# OCR

![scanned](https://github.com/GolaraRFI/OCR/assets/80590542/38040edd-19fd-4c7e-9f2f-9254d5ab1465)

# Persian Identity Card OCR System

This project is a simple Optical Character Recognition (OCR) system that utilizes OpenCV, ArabicOcr, and pytesseract to extract personal information from Persian Identity Cards. It is designed with beginners in mind, offering a straightforward implementation that covers the core principles of OpenCV, ArabicOcr, and pytesseract.

## Requirements:

Before you get started, ensure you have the following dependencies installed:

```bash
pip install opencv-python-headless
pip install ArabicOcr
pip install pytesseract
sudo apt-get install tesseract-ocr-fas

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
Document Scanner Repository
Tesseract OCR Repository

-------------------------------------------------------
This project is a simple OCR system using opencv, ArabicOcr, and pytesseract. You can extract personal information from **Persian** **Identity** **Card**. This is a perfect project for beginners as it is simple and covers the core principals of opencv, ArabicOcr, and pytesseract.

Requirements:

  - pip install opencv-python-headless
  - pip install ArabicOcr
  - pip install pytesseract
  - sudo apt-get install tesseract-ocr-fas

***
**Project steps:**

1 - Extract binary information:

  - In this part extra data is deleted from the image and only the needed information is kept in a binary image.

2 - Extract each part separately:

  - In this part the information which are not numbers are saved in seperate images.
 
3 - Preprocessing numbers:

  - In this part the information (numbers) are analized.
  - Numbers are analized one by one (zeros and ones are recognized by image processing).
  - Slashs are deleted and numbers between them extracted.

4 - TEST:
  - In this part **arabicocr** and **pytesseract** are used for extracting rest of the information. At the end extracted information from this part and the information from image processing part are stuck together and reported as final result.

***

Links:


Document Scanner: https://github.com/murtazahassan/Document-Scanner.git

Tesseract OCR: https://github.com/tesseract-ocr/tesseract.git
