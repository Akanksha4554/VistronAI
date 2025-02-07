# VistronAI - Unlocking the Future with Advanced AI Solutions for Every Need  🚀
VistronAI is an integrated suite of six advanced LLM-based applications for audio, video, document, and URL analysis, real-time Q&A, and OCR for images. Leveraging cutting-edge language models like Google's Gemini and Llama, VistronAI enhances content comprehension, workflow automation, and provides seamless user interactions.

# Key Features🔑
1. Audio & Video 🎧🎥: 
Automatically summarize audio and video files in formats like MP3, MP4, WAV, and OGG and Q&A using advanced LLM's.

2. Real-time Q&A❓:
Upload documents, videos, and audio files to ask context-based questions and receive accurate, informative answers.

3. OCR for Images 📷:
Extract text from images with high accuracy using Tesseract OCR and analyze it for further processing, such as translation or Q&A tasks.

4. Document Analysis 📄:
Supports PDF, Word, PowerPoint, and text document formats, enabling in-depth analysis and question answering.

5. Interactive Streamlit UI 🌐:
A user-friendly interface for seamless interaction with all the applications, designed using Streamlit.


# Technologies Used 🛠️
### Language Models:
Google Gemini 1.5 Pro, Gemini 1.5 Flash, Gemini 2.0 Exp
Llama 3.1, Llama 3.3

### Backend:
Python, LangChain, FAISS (for efficient information retrieval and data handling)
Tesseract OCR (for image-based text extraction)

### Frontend:
HTML, CSS, JavaScript, Streamlit (for building an interactive web interface)

### Deployment:
Streamlit, Netlify (To be done)

### Use 🔧

#### Clone the Repository

```bash
git clone https://github.com/sonali9561/name of application
cd name of application

```
#### Install Requirements
```bash
pip install -r requirements.txt

```
#### Run the App
```bash
streamlit run app.py
The app should now be running locally at http://localhost:8501.
```

# How It Works 💡

#### Audix 🎧: 
Upload an audio file (MP3, WAV, OGG), and the app uses Google Gemini 1.5 Pro to analyze and summarize the content. It also handles Q&A and supports voice interaction, extracting key points for efficient content comprehension.

#### AskYT🎥: 
Engage with YouTube content in an insightful way. Upload a YouTube link, and AskYT summarizes the video transcript, performs sentiment analysis, and provides intelligent Q&A. With speech-to-text support, multi-language capabilities, and PDF export, AskYT enhances learning and analysis, delivering AI-driven insights from YouTube videos.

#### QuickURL 🌐:
A Streamlit-powered tool designed to simplify online research. Upload a URL, and Google Gemini 1.5 Flash quickly summarizes the content and provides contextually accurate answers to questions based on that content. This helps users save time by instantly retrieving relevant information from any webpage.

#### SmartDOC 📑:
Upload PDFs, Word, PPT, or text files, and transform them into interactive Q&A sessions. Using LLAMA 3.3 70b and FAISS, SmartDOC processes documents to provide instant, context-aware responses, enabling users to quickly extract key insights from various documents.

#### VisionLex 📸:
OCR for Image Text Extraction: Upload images, and VisionLex utilizes Tesseract OCR to extract text from 50+ languages. Google Gemini 1.5 Flash is used for advanced translation and Q&A on the extracted text. It converts images into multilingual text insights, processes the extracted data, and translates it into different languages, all via an intuitive Streamlit interface.

#### EnlightAI 🤖:
AI-Powered Chatbot: EnlightAI leverages Llama 3.1-8b-instant for intelligent, context-aware conversations. It empowers users with instant, accurate responses to queries, helping them solve problems efficiently through a real-time, AI-driven interface designed for smooth, user-friendly interactions.

# Use Cases📝  📚 💼
#### Education: 
Quickly summarize lectures, podcasts, and videos. Ask specific questions to gain insights from educational media.
#### Business: 
Automate document analysis and OCR processes for improved efficiency.
#### Media & Content Creation: 
Extract key insights from long audio or video content, improving content workflows.
#### Research: 
Extract and analyze data from various document formats, including PDFs and text files, using real-time Q&A.

# Contribution 🤝
Feel free to contribute by forking the repository and submitting pull requests with new features, improvements, or bug fixes.

# License📜
This project is licensed under the MIT License - see the LICENSE file for details.
