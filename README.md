# YouTube Video Summarizer

This is a Python-based application that uses Google Gemini Pro and Streamlit to provide concise summaries of YouTube videos. It leverages the power of large language models (LLMs) to analyze and summarize video content effectively.

## Features

- Extracts video transcripts from YouTube.
- Generates summaries using Google Gemini Pro.
- Interactive web interface built with Streamlit.
- User-friendly and efficient in processing video content.

## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/arnavdaryani/Youtube-Video-Summarizer.git
    cd Youtube-Video-Summarizer
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## Usage

1. Open the Streamlit app in your web browser.
2. Enter the URL of the YouTube video you want to summarize.
3. Click the "Summarize" button.
4. View the generated summary on the app interface.

## File Structure

- `app.py`: The main Streamlit app script. It also contains utility functions for video transcript extraction and summarization.
- `requirements.txt`: A list of all Python dependencies required for the project.
