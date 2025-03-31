# ACE HIRE - AI Interview Preparation Platform

![ACE HIRE Logo](https://drive.google.com/file/d/1qQg5LIJUYyaIoJQdvxlOM6CL6aLZMIs_/view?usp=sharing)

Become an ACE HIRE today - your gateway to interview success with AI-powered practice sessions and feedback.

## 🌟 Features

- **Resume-Job Matching**: Analyze how well your resume matches job descriptions
- **Personalized Questions**: AI-generated interview questions tailored to your resume
- **Practice Sessions**: Realistic interview simulations with voice recording
- **Performance Analytics**: Detailed feedback on your responses
- **Multi-language Support**: Practice in multiple Indian languages
- **Progress Tracking**: Save and review your interview history

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Streamlit
- Google Gemini API key (for question generation)
- OpenAI API key (for analysis)

### Installation

1. Clone the repository:
```
   git clone https://github.com/yourusername/ace-hire.git
   cd ace-hire
```

2. Install dependencies:
```
  pip install -r requirements.txt
```

3. Create a .env file with your API keys:
```
OPENAI_API_KEY=your_openai_key
GEMINI_API_KEY=your_gemini_key
```

4. Initialize the database:
```
python -c "from utils.db import initialize_database; initialize_database()"
```

5. Run the application:
```
streamlit run Ace_Hire.py
```

## 🗂️ Project Structure
    ace-hire/
    ├── app.py                # Main application file
    ├── utils/
    │   ├── db.py             # Database operations
    │   ├── nlp_processor.py  # NLP analysis functions
    │   ├── pdf_processor.py  # Resume parsing
    │   └── openai_helpers.py # OpenAI integration
    ├── static/               # Static assets
    ├── requirements.txt      # Dependencies
    └── README.md             # This file

## 📋 Usage Guide
1. Upload Your Resume
    - Upload your resume (PDF/DOCX)
    - Paste or upload the job description

2. Resume Analysis
    - View your resume-job match score
    - See keyword matches and gaps

3. Generate Questions
    - Get personalized interview questions
    - Customize question difficulty

4. Practice Interview
    - Record your answers to questions
    - Get instant feedback on responses

5. Review Performance
    - View comprehensive feedback reports
    - Track progress over time

# 📚 Documentation
For detailed documentation, please visit our [report](https://docs.google.com/document/d/1Ya14k2mQhb7dpngNkGItMhwa9rPPxyGOU7FP-cOv6OI/edit?usp=sharing).

# 🤝 Contributing
We welcome contributions!
Steps to contribute:

1. Fork the repository

2. Create your feature branch:
```
git checkout -b feature/AmazingFeature
```
3. Commit your changes:
```
git commit -m "Add AmazingFeature"
```
4. Push to the branch:
```
git push origin feature/AmazingFeature
```
5. Open a Pull Request

# 📜 License
Distributed under the MIT `(License)`. See LICENSE for more information.
