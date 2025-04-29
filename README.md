# OCR using Gemma-3

Gemma-3 OCR is a web application that allows you to extract structured text from images using the Gemma-3 Vision Model via Ollama. The app provides a simple interface to upload images and receive well-formatted Markdown output of the recognized text.

[![Watch the video]
(Demo.gif)]
## Features

- **Image Upload:** Easily upload PNG, JPG, or JPEG images from your device.
- **OCR Extraction:** Uses the Gemma-3 Vision Model to analyze and extract all readable content from images.
- **Structured Output:** Presents extracted text in a clear, concise, and well-organized Markdown format (including headings, lists, and code blocks).
- **Instant Preview:** Displays the uploaded image and the OCR results side by side.
- **Clear Results:** One-click button to clear the current results and start over.
- **User-Friendly Interface:** Built with Streamlit for a responsive and interactive experience.

## Getting Started

### Prerequisites

- Python 3.8+
- [Ollama](https://ollama.com/) installed and running locally
- Required Python packages (see `requirements.txt`)

### Installation

1. Clone this repository.
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
3. Make sure Ollama is running and the gemma3:12b model is available.

### Usage
Run the Streamlit app:
```sh
streamlit run app.py
