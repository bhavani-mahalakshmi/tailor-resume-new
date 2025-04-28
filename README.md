# Resume Tailor

An AI-powered tool that helps tailor your resume to match job descriptions. The application uses AI to analyze your resume and the job description, then generates a tailored version of your resume in LaTeX format.

## Features

- Upload PDF or Word (.docx) resumes
- Paste job descriptions
- AI-powered resume tailoring
- LaTeX editor with live preview
- PDF download capability
- Modern, user-friendly interface

## Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- A modern web browser

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/resume-tailor.git
cd resume-tailor
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Running the Application

1. Start the Flask server:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:5000
```

## Usage

1. **Upload Your Resume**
   - Click the upload area or drag and drop your resume file
   - Supported formats: PDF (.pdf) or Word (.docx)

2. **Enter Job Description**
   - Paste the complete job description in the text area
   - Include job title, requirements, and responsibilities

3. **Generate Tailored Resume**
   - Click "Tailor Resume" to process your resume
   - Wait for the AI to analyze and generate the tailored version

4. **Review and Edit**
   - Review the generated LaTeX code in the editor
   - Make any necessary adjustments
   - Preview the changes in real-time

5. **Download**
   - Click the "Download PDF" button to save your tailored resume

## Development

### Project Structure
```
resume-tailor/
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
├── templates/         # HTML templates
│   └── index.html     # Main application template
└── static/           # Static files (CSS, JS, etc.)
```

## Acknowledgments

- Built with Flask
- Uses CodeMirror for LaTeX editing
- Font Awesome for icons
- Material Design Darker theme for CodeMirror

## Copyright

© 2025 Bhavani Mahalakshmi Gowri Sankar. All rights reserved.

Connect with me on [LinkedIn](https://www.linkedin.com/in/bhavani-mahalakshmi-gowri-sankar-6b6a54119/) 