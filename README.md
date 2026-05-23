# Azure AI Text Analysis Project

This project uses Azure AI Language Services with Python to analyze hotel reviews.

## Features

- Language Detection
- Entity Recognition
- PII Detection
- PII Redaction

## Technologies Used

- Python
- Azure AI Language Service
- Azure AI Foundry
- Azure SDK
- Git & GitHub

## Project Structure

```text
text-analysis/
│
├── reviews/
│   ├── review1.txt
│   ├── review2.txt
│   ├── review3.txt
│   ├── review4.txt
│   └── review5.txt
│
├── requirements.txt
├── text-analysis.py
└── README.md
```

## Setup Instructions

### 1. Clone Repository

```bash
git clone <your-repository-url>
```

### 2. Create Virtual Environment

Mac/Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Windows:

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file and add:

```env
FOUNDRY_ENDPOINT=https://your-resource.services.ai.azure.com
```

### 5. Login to Azure

```bash
az login
```

### 6. Run the Project

```bash
python3 text-analysis.py
```

## Sample Features Demonstrated

### Language Detection

Detects the language of hotel reviews.

### Entity Recognition

Identifies:
- Locations
- Organizations
- People
- Other named entities

### PII Detection & Redaction

Detects sensitive information and creates a redacted version of the text.

## Learning Outcomes

This project demonstrates:

- Natural Language Processing (NLP)
- Cloud AI integration
- Azure AI SDK usage
- Python application development
- GitHub project management

## Author

Bhumi Gupta