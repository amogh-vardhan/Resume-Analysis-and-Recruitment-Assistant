# Resume Parser and Matcher Using NLP

A Python-based tool for extracting, analyzing, and matching resumes with job descriptions using advanced Natural Language Processing (NLP) techniques. This tool supports PDF and DOCX file formats and provides insights into resumes by extracting key information such as names, education, skills, contact information, and calculating match percentages with job descriptions. It also integrates with Anthropic's Claude AI for answering advanced queries.

---

## Features

- **Resume Parsing**:
  - Extract text from resumes in PDF or DOCX formats.
  - Identify names, education, skills, phone numbers, and email addresses.
- **Job Description Analysis**:
  - Extracts keywords and analyzes job descriptions.
  - Matches skills with resumes to calculate compatibility percentages.
- **AI Integration**:
  - Uses Anthropic's Claude AI to answer detailed queries about candidates and job descriptions.
- **Keyword Matching**:
  - Leverages NLP to extract domain-specific keywords for analysis.

---

## Prerequisites

- Python 3.7 or higher
- Required Python libraries:
  - `anthropic`
  - `docx2txt`
  - `PyPDF2`
  - `spacy`
  - `nltk`

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/resume-parser.git
