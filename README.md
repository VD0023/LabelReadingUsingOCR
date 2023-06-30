## Label Reading using OCR - Python Project Documentation

### Introduction:
Optical Character Recognition (OCR) is a technology that enables the extraction of text from images or scanned documents. This project demonstrates how to use OCR to read labels from an image and save the extracted text to a text file. The Tesseract OCR engine is utilized for text extraction.

### Prerequisites:
- Python 3.x
- Tesseract OCR (tesseract.exe) - Make sure the Tesseract OCR engine is installed and its executable path is set correctly in the code.

### Project Structure:
The project consists of a single Python script that utilizes the Tesseract OCR engine to perform label reading on an image.

### Main Code:
The **Main Code** includes the following steps:
1. Importing required libraries: The `pytesseract` library is used to access the Tesseract OCR engine, and `PIL` (Python Imaging Library) is used to handle image processing.
2. Setting the Tesseract OCR path: The path to the Tesseract OCR executable is specified using `pytesseract.pytesseract.tesseract_cmd`.
3. Defining the OCR function: The `recText()` function takes the filename of an image as input, opens the image using PIL, and then extracts the text using Tesseract OCR. The extracted text is returned by the function.
4. Performing OCR on the image: The `recText()` function is called with the filename 'TEST2.png', and the extracted text is stored in the variable `info`.
5. Writing the result to a text file: The extracted text is written to a text file named 'result.txt' using the `open()` and `write()` functions.
6. Displaying successful completion: A success message is printed to the console after writing the text to the file.

### Usage:
To use the Label Reading using OCR system:
1. Make sure all the prerequisites are installed, including the Tesseract OCR engine and its executable path is set correctly in the code.
2. Place the image file (e.g., 'TEST2.png') containing the label to be read in the same directory as the Python script.
3. Run the Python script.
4. The script will perform OCR on the image, extract the text, and save it in a text file named 'result.txt'.
5. Check the 'result.txt' file to view the extracted label text.

### Conclusion:
The Label Reading using OCR project provides a simple and effective way to extract text from images. It can be extended for various applications, such as extracting information from scanned documents, automating data entry tasks, and enhancing text recognition in image processing applications.
