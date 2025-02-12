# AutoGen Job Search Assistant

## Overview
This project aims to create an AI-powered job search assistant using Microsoft AutoGen. The system consists of multiple AI agents that collaborate to find and optimize job opportunities on LinkedIn based on predefined conditions. The main objective is to automatically tailor your CV to better fit the most relevant job postings that match your ideal job description.

## Features
- **Job Finder Agent**: Searches for job postings on LinkedIn that match the specified criteria.
- **Decision Agent**: Determines if a job posting is relevant and worth applying for.
- **Key Insights Extractor**: Extracts key qualifications and skills required for the job.
- **CV Optimizer Agent**: Reads and restructures the user's CV to better fit the most suitable job opportunities.

## Installation
### Prerequisites
- Python 3.8+
- OpenAI API key (if using GPT models)
- pip

### Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/autogen-job-search.git
   cd autogen-job-search
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Set up OpenAI API key:
   ```sh
   export OPENAI_API_KEY="your_api_key"
   ```
4. Run the project:
   ```sh
   python main.py
   ```

## Usage
1. Define your job search conditions in `config.json`.
2. Run the assistant to fetch relevant jobs.
3. The AI will analyze job postings and automatically optimize your CV for the best-matching opportunities.

## Future Improvements
- Integration with multiple job boards
- Support for local LLM models
- Advanced filtering and ranking of job postings

## License
MIT License

