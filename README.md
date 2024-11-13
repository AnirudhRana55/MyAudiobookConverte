# PDF to Audiobook Converter
A straightforward web application that converts PDF files into audiobooks, developed using Python and Streamlit.

![Streamlit PDF to Audiobook Converter](https://github.com/user-attachments/assets/e55f2fa1-79c6-406f-b3fb-2b2c00229979)


This app enables users to:

* Upload PDF files using a drag-and-drop interface.
* Convert the uploaded PDF into an MP3 audiobook.
* Download the generated MP3 file after the conversion is finished.

**The Tools and Modules used include**
-------------------------

To develop this app, we utilize:

* **Streamlit** for creating the web interface.
* **pdfplumber** to extract text from PDF documents.
* **pyttsx3** for offline text-to-speech conversion.
* **Pathlib** to manage file paths and ensure proper file saving.
  
**Steps to Run**
-------------------------

*   Clone the app:
`git clone https://github.com/AnirudhRana55/MyAudiobookConverter.git`
*   Install required libraries:
`pip install streamlit pyttsx3 pdfplumber`
*   Run the app:
`streamlit run app.py`


