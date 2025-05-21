# NLP Workshop Project

This repository contains a comprehensive Natural Language Processing (NLP) workshop with both introductory exercises and an advanced project. The workshop is designed to help you learn and practice various NLP techniques, from basic text processing to advanced applications of sentiment analysis in business analytics.

## Project Structure

- `intro_to_nlp.ipynb`: Introductory notebook with basic NLP exercises
- `nlp_project.ipynb`: Advanced project notebook with guided exercises for sentiment analysis in data consulting
- `requirements.txt`: Required Python packages

## Setup Instructions

1. Create a virtual environment (recommended):
```bash
python -m venv nlp_env
source nlp_env/bin/activate  # On Windows: nlp_env\Scripts\activate
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Download required NLTK data and spaCy model:
```bash
python -m spacy download en_core_web_sm
python -m nltk.downloader punkt stopwords wordnet
```

## Requirements

- Python 3.8 or higher
- Jupyter Notebook
- See requirements.txt for package dependencies

## Getting Started

1. Start with the introductory notebook (`intro_to_nlp.ipynb`) to learn basic NLP concepts
2. Complete the exercises in each section
3. Move on to the advanced project notebook (`nlp_project.ipynb`)
4. Experiment with different techniques!

## Additional Resources

- [NLTK Documentation](https://www.nltk.org/)
- [spaCy Documentation](https://spacy.io/usage)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/)
