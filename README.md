# TutorGPT

## Overview
TutorGPT is an AI-powered multimodal system designed to automate student data insights and report generation. The system integrates document indexing, query-based information retrieval, and visually enriched report creation using advanced AI models such as GPT, LlamaParse, and vector databases.

## Features
- **Multimodal Support**: Processes text, PDFs, images, and tabular data.
- **Efficient Storage & Retrieval**: Uses chunking and vector databases for optimized searches.
- **OCR for Image-based Files**: Extracts text from images and supports diagrams.
- **Fast Query Processing**: Enables semantic searches for rapid information retrieval.
- **Context Preservation**: Maintains metadata for accurate report generation.

## Installation & Setup

### Step 1: Clone the Repository
```sh
git clone https://github.com/your-repo/tutorgpt.git
cd tutorgpt
```

### Step 2: Create a Virtual Environment
```sh
python -m venv env
```

### Step 3: Activate the Virtual Environment
#### Windows:
```sh
env\Scripts\activate
```
#### Mac/Linux:
```sh
source env/bin/activate
```

### Step 4: Install Dependencies
```sh
pip install -r req1.txt
pip install -r req2.txt
```

### Step 5: Run the Application
```sh
python app.py
```

## Usage
1. **Upload a document** (PDF, image, text, etc.).
2. **Query the document** for insights and generate reports.
3. **Retrieve structured data** from vector indexing.

## Technologies Used
- **LlamaParse**: For document parsing.
- **HuggingFace Models**: GPT-based embeddings.
- **Vector Databases**: FAISS, Pinecone, or Weaviate.
- **Gradio**: Interactive UI for user queries.
- **Docker (Optional)**: For offline execution.

## Future Enhancements
- Support for audio-based document parsing.
- Integration with cloud storage for document uploads.
- Advanced visualization tools for report generation.

## Contact
For issues or suggestions, reach out via GitHub Issues.
