# YouTube Video Transcriber and Summarizer




https://github.com/user-attachments/assets/5d67f527-4045-4607-bd66-1d34a8918a7b



## Overview
Welcome to the YouTube Video Transcriber and Summarizer, an AI-powered web application designed to transcribe and summarize entire YouTube videos into crisp, concise text. Leveraging the power of Google's Generative AI, this app is ideal for quickly digesting lengthy video content, making it perfect for professionals, students, and content creators who want to save time while extracting valuable insights from videos.

## Features
- **AI-Powered Transcription** : Automatically transcribe YouTube videos using the youtube_transcript_api.
- **Summarization Using Google Generative AI** : Condense lengthy video transcripts into short, readable summaries.
- **Easy-to-Use Web Interface** : Built with Streamlit for an interactive, user-friendly experience.
- **Secure and Configurable**: Utilizes python-dotenv for managing environment variables securely.
- **File Management**: Efficient file handling and path management using pathlib.
- 
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
  
# Technologies Used
- **Streamlit** : For building the web interface.
- **youtube-transcript-api** : For fetching YouTube video transcripts.
- **google-generativeai** : For generating concise summaries using state-of-the-art AI models.
- **python-dotenv** : For secure environment variable management.
- **pathlib** : For easy and efficient file path handling.

# Contributing
Contributions are welcome! Please fork the repository and create a pull request for any feature enhancements or bug fixes.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Contact
- **Email** : brijesh29.it11@gmail.com
- **Linkedin** : https://www.linkedin.com/in/brijesh-kapadiya-536406282/
- **GitHub** : https://github.com/b-1129
