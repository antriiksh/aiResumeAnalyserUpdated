## 🌟 Overview

**Resume Job Fit Analyzer** is a sophisticated web-based application that leverages Natural Language Processing (NLP) and Machine Learning to intelligently compare resumes with job descriptions. It provides detailed compatibility scores, skill gap analysis, and actionable recommendations to help job seekers optimize their resumes for specific positions.

---

## ✨ Features

#### Smart Analysis Engine
- **PDF Text Extraction**: Seamless parsing with PyMuPDF
- **NLP Processing**: Advanced text analysis using spaCy
- **Real-time Results**: Lightning-fast processing with live progress
- **Multi-format Support**: Handle various resume structures

</td>
<td width="50%">

## 🚀 Installation

### Prerequisites

Ensure you have the following installed:

```bash
✅ Python 3.11 or higher
✅ pip (Python package manager)
✅ Git
✅ 100MB free disk space
```

### Quick Start

# 1. Clone the repository
git clone https://github.com/antriiksh/resumeAnalyserUpdated.git
rename App(1).py to App.py
cd resume-analyzer

# 2. Create virtual environment
python -m venv venv

# 3. Activate virtual environment
# Windows:
.\venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

# 4. Install dependencies
pip install --upgrade pip
pip install -r requirements.txt

# 5. Download NLP model
python -m spacy download en_core_web_sm

# 6. Run the application
python main.py
```

**Access the Application**
   ```
   Navigate to http://localhost:5000
   ```

**Upload Resume**
   - Click "Choose File" or drag & drop PDF
   - Maximum file size: 16MB
   - Supported format: PDF (text-based)

**Paste Job Description**
   - Copy job posting from any source
   - Include requirements, skills, and responsibilities
   - More detail = better analysis

**Analyze**
   - Click "Analyze" button
   - Wait 2-5 seconds for processing
   - View comprehensive results

**Made by [Antriksh Kashyap](https://github.com/antriiksh)**
