
# QR Code Generator

This is a simple Streamlit web app for generating QR codes based on user input. You can choose between generating a QR code for a URL or plain text with the ability to generate multiple URLs at once.

# Web App
Click [Here](https://huggingface.co/spaces/Kaludi/QR-Code-Generator-Streamlit_App "Here") To View This App Online!

## Features

-   Generate QR codes for URLs or plain text
-   Download the generated QR code as a PNG image
-   Supports multiple QR codes generation (one per line)

## Usage
    
1.  Select the QR content type (URL or Text)
    
2.  Enter the content for the QR code (for multiple QR codes, enter one per line)
    
3.  Click the "Generate QR Code" button
    
4.  Download the generated QR code by clicking the "Download QR code" button

## Installation

1.  Clone the repository

`git clone https://github.com/Kaludii/QR-Code-Generator-Streamlit.git` 

2.  Change the working directory

`cd QR-Code-Generator-Streamlit` 

3.  Install the required dependencies

`pip install -r requirements.txt` 

4.  Run the Streamlit app

`streamlit run app.py` 

5.  Open your browser and go to the specified address (usually `http://localhost:8501`)
    

## Dependencies

-   streamlit
-   qrcode
-   Pillow