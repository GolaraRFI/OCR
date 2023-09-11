# OCR

![scanned](https://github.com/GolaraRFI/OCR/assets/80590542/38040edd-19fd-4c7e-9f2f-9254d5ab1465)

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
