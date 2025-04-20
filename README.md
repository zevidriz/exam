# PDF Exam Generator

This is an AI-powered application that generates exam questions from PDF documents. It uses natural language processing to analyze the content of PDF files and create relevant questions automatically.

🔗 **[Try it live here!](https://pdf-exam-generator.streamlit.app)** (Coming soon)

## Features

- Upload any PDF document
- Automatically generate questions based on the content
- Adjustable number of questions (1-10)
- Export questions and answers to Word document
- Beautiful, modern user interface
- AI-powered question generation
- Smart selection of diverse questions
- Free to use!

## Local Installation

1. Make sure you have Python 3.8 or higher installed on your system.

2. Clone this repository or download the files to your local machine.

3. Install the required dependencies by running:
```bash
pip install -r requirements.txt
```

## Usage

### Option 1: Use the Online Version (Recommended)
Simply visit our [live demo](https://pdf-exam-generator.streamlit.app) to use the application without any installation.

### Option 2: Run Locally
1. Open a terminal/command prompt in the project directory.

2. Run the application:
```bash
streamlit run app.py
```

3. Your default web browser will open automatically with the application interface.

4. Upload a PDF file using the file uploader.

5. Select the number of questions you want to generate using the slider.

6. Click "Generate Questions" to create the exam questions.

7. Review the generated questions and answers in the interface.

8. Download the complete exam with answer key as a Word document.

## Requirements

- Python 3.8+
- Internet connection (for downloading AI models on first run)
- Sufficient disk space (approximately 2GB for AI models)
- Minimum 8GB RAM recommended

## Hosting Your Own Version

You can host your own version of this application for free using Streamlit Cloud:

1. Fork this repository to your GitHub account
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Sign in with your GitHub account
4. Deploy your forked repository
5. Your app will be live at `https://[your-app-name].streamlit.app`

## Technical Details

The application uses several advanced AI and NLP technologies:
- Transformers for question generation
- Sentence transformers for semantic analysis
- PyPDF2 for PDF processing
- NLTK for text processing
- Streamlit for the web interface

## Troubleshooting

If you encounter any issues:

1. Make sure all dependencies are correctly installed
2. Check if your PDF file is text-based (not scanned images)
3. Ensure you have a stable internet connection for the first run
4. Try with a different PDF if the current one doesn't generate questions

## Note

The quality of generated questions depends on the input PDF's content quality and formatting. Best results are achieved with well-structured, text-based PDF documents.

## Contributing

Feel free to contribute to this project by:
1. Reporting issues
2. Suggesting new features
3. Creating pull requests

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
