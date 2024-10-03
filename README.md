# Chat PDF Streamlit Application 📄🤖

## Overview

The **Chat PDF** application is a Streamlit-based tool that allows users to interactively ask questions about the content of PDF files. By leveraging the power of Google Generative AI and Langchain, the app extracts text from uploaded PDFs, splits it into manageable chunks, and provides accurate responses based on the content. This project aims to simplify information retrieval from documents, enhancing productivity and user experience. 🚀

## Features ✨

- Upload multiple PDF files. 📁
- Ask questions related to the content of the PDFs. ❓
- Get detailed answers generated using advanced AI models. 💡
- User-friendly interface powered by Streamlit. 🌐

## Setup Instructions ⚙️

To set up the Chat PDF application on your local machine, follow these steps:

### 1. Prerequisites ✅

Ensure you have the following installed on your machine:

- **Python 3.8 or later** 🐍
- **pip** (Python package installer) 📦

### 2. Create a Virtual Environment 🌍

It's a good practice to create a virtual environment to manage dependencies. You can create one using the following commands:

- Navigate to your project directory.
- Create a virtual environment: `python -m venv venv`
- Activate the virtual environment:
  - On Windows: `venv\Scripts\activate`
  - On macOS/Linux: `source venv/bin/activate`

### 3. Install Requirements 📜

Install the required packages using pip by running:

`pip install -r requirements.txt`

### 4. Create a `.env` File 🔑

To configure the application, create a `.env` file in the root directory of the project. This file will store sensitive information such as your Google API key.

1. Create a file named `.env`.
2. Add the following line:

   `GOOGLE_API_KEY=your_google_api_key`

   Replace `your_google_api_key` with your actual Google API key. 🔒

### 5. Run the Application 🚀

After setting everything up, run the application with:

`streamlit run app.py`

This will start the Streamlit server and open the application in your web browser. 🌐

## Usage 📝

1. **Upload PDF Files**: Use the file uploader to select and upload your PDF documents. 📥
2. **Ask Questions**: Type your question in the input field and submit it to get answers based on the PDF content. ✍️
3. **Interact**: The application will process your request and provide a detailed response based on the uploaded documents. 🔄

## Conclusion 🎉

The Chat PDF application is a powerful tool that enhances the way users interact with PDF documents. With its intuitive interface and advanced AI capabilities, it provides quick and accurate information retrieval, making it an invaluable resource for students, researchers, and professionals alike.

For any issues or contributions, please feel free to open an issue or submit a pull request in the repository. Enjoy exploring your PDFs with Chat PDF! 🚀
