
# AI-Powered Text Summarizer and Q&A Assistant

A web application that summarizes documents and answers questions about their content using Google Gemini AI.

## Features
- Upload text documents
- Generate concise summaries
- Ask questions about document content
- Download generated summaries
- PDF support (if tested successfully)

## Technologies
- Python
- Streamlit
- LangChain
- Google Gemini API
- pypdf

## Setup
1. Clone or download this repository.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the project folder and add:

   ```text
   GOOGLE_API_KEY=your_api_key_here
   ```

4. Run the application:

   ```bash
   streamlit run app.py
   ```

Never publish your actual API key.
