# 🦜 LangChain: Summarize Text From YouTube or Websites
Live Link - https://yt-website-content-summarizer-jrdg8drgjgyno4xasxqjke.streamlit.app/

## Overview
Welcome to the **LangChain Summarizer**! This Streamlit app leverages cutting-edge language models and AI-powered embedding techniques to provide concise summaries of content from YouTube videos or websites. Using a combination of the **Groq Gemma-7b-It model** and **OpenAI embeddings**, this tool allows users to extract key insights from long-form content without reading or watching everything themselves.

The summarizer uses a smart pipeline that:
1. Loads content from a YouTube video or webpage.
2. Breaks the text into manageable chunks.
3. Embeds the content for efficient retrieval of key information.
4. Summarizes the most relevant sections using AI, providing a quick overview.

## Features
- **Summarize YouTube Videos**: Input any YouTube URL and get a concise summary of the video's content.
- **Summarize Web Pages**: Provide a web page URL, and the app will summarize the text from the site.
- **AI-Powered**: Uses **Groq's Gemma-7b-It** model for generating summaries and **OpenAI embeddings** for text understanding and retrieval.
- **Automatic Text Splitting**: Handles long content by splitting it into smaller chunks before processing, making sure no important details are missed.
- **User-Friendly Interface**: Built using **Streamlit**, making it easy to use without any technical setup.

## Installation and Setup
To get started with this project, follow these steps:

### 1. Clone the Repository
```bash
git clone https://github.com/STAVAN-2710/YT-Website-Content-Summarizer.git
cd YT-Website-Content-Summarizer
