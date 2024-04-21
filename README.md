# Quizify

## Overview

Quizify mission offered by Radical AI is a 10 tasks Quiz generating app. It is a web app which takes input a pdf document which the LLM will have as context and generate questions with multiple-choice answers based on it.
It has the option to generate multiple questions in the quiz based on a slider
## Tech Stack
- LLM = Vertex AI, gemini pro
- Interface = Streamlit
- Vector Store = Chromedb
- RAG = Langchain


```
# Clone the repository
git clone https://github.com/saiteja12-g/mission-quizify.git
cd mission-quizify

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
```
