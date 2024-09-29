OCR Web Application

Overview:

This project is a web-based Optical Character Recognition (OCR) application that extracts text from image containing English text. It utilizes the GOT 2.0 model for efficient text recognition and provides features for keyword search and text highlighting.

Features:

* Image Upload: Users can upload images containing text in English.

* Text Extraction: Utilizes the GOT 2.0 model to extract text from the uploaded images.

* Keyword Search: Users can search for specific keywords in the extracted text.

* Highlight Matching Sections: Matching sections of the text are highlighted for better visibility.

Prerequisites:

* Before running the application, ensure you have access to Google Colab and a suitable environment set up.

Setup Instructions:

1.Open Google Colab

2.Create a New Notebook

3.Install Required Libraries:
tiktoken
verovio
torch
transformers
Gradio

Run the application:

1.Execute the cells in the notebook sequentially to ensure all libraries are loaded and the application is initialized correctly.

2.When prompted, upload an image containing English text for extraction.

Usage Instructions:

Once the application is running, follow these steps:

1.Upload your image file containing English text using the upload feature in the interface.

2.After the image is processed, you will see the extracted text displayed on the screen.

3.Use the search functionality to enter specific keywords. The application will highlight all matching sections in the extracted text for easier visibility.



Screenshots:


![OCR Web Application Screenshot](https://github.com/user-attachments/assets/5af440fd-b8c5-443a-8caf-0ecfa2211854)
*OCR Web Application Screenshot*

![OCR Web Application Screenshot with search](https://github.com/user-attachments/assets/3ab84721-141e-4971-a7b1-860171fe5f5d)
*OCR Web Application Screenshot with search*

![OCR Web Application Screenshot with highlighted text](https://github.com/user-attachments/assets/b93e077e-9d89-4958-a0d2-9e8c439a5367)
*OCR Web Application Screenshot with highlighted text*

