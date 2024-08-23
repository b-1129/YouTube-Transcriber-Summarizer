# YouTube-Transcriber-Summarizer




https://github.com/user-attachments/assets/5d67f527-4045-4607-bd66-1d34a8918a7b



## Overview
The **YouTube Transcriber Summarizer** is an application that leverages the power of Google Gemini Pro and large language models (LLMs) to transcribe and summarize YouTube videos. This tool is designed to provide concise summaries of YouTube content, making it easier for users to digest long videos quickly and efficiently.

## Features
- **Automatic Transcription**: Converts spoken content in YouTube videos into text using advanced speech recognition technology.
- **Summarization**: Provides a concise summary of the transcribed text, highlighting the main points and key takeaways.
- **User-Friendly Interface**: Simple and intuitive interface for uploading video links and retrieving summaries.
- **Scalable and Efficient**: Designed to handle videos of various lengths and complexities, ensuring quick processing times.


# Steps to Run this App:

1. Create an Virtual Environment :
   conda create -p YTTrans python==3.11 -y

2. Activate your virtual Environment

3. Install requirements.txt file :
   pip install -r requirements.txt

4. Create .env file and save your GOOGLE_API_KEY:

5. Run App:
   streamlit run app.py

6. Access the application: (It will redirect automatically.)
   
7. Transcribe and Summarize
   - Enter the YouTube video link.
   - Press Enter for Thumbnail.
   - Click on "Get Detailed Notes.
