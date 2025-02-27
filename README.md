---
title: Language Translation App using Groq
emoji: ✨
colorFrom: blue
colorTo: red
sdk: streamlit
app_file: app.py
pinned: false
---
# Language Translation App using Groq 

## Project Overview

This project is a language translation application leveraging the Groq AI model. The app provides a simple and intuitive interface for translating text into multiple languages, including Hindi, French, and Spanish. It integrates Groq's advanced language model to ensure accurate and context-aware translations.

## Project Structure

```
📂Directory structure:
└── kiran-91-a-simple-language-translation-app/
    ├── README.md
    ├── GroqLCEL.ipynb
    ├── LICENSE
    ├── app.py
    ├── requirements.txt
    └── .github/
        └── workflows/
            └── main.yaml

```


## Key Technologies

- **Groq AI**: Utilized for the underlying language translation model.
- **LangChain**: For managing prompts and integrating the language model.
- **Streamlit**: For creating the interactive user interface.

## Features

- Multi-language support: Translate text into Hindi, French, or Spanish.
- User-friendly interface powered by Streamlit.
- Real-time feedback and error handling.
- Uses the "Gemma2-9b-It" model from Groq for high-quality translations.

## Installation

### Steps

1. Clone the repository:

   ```cmd
   git clone https://github.com/kiran-91/A-simple-language-translation-app.git
   cd A-simple-language-translation-app
   ```

2. Install the required Python packages:

   ```bash 
   pip install -r requirements.txt
   ```

3. Create a `.env` file to securely store your API keys:

   ```bash
   GROQ_API_KEY=<your_groq_api_key>
   ```

4. Run the Streamlit application:

   ```cmd
   streamlit run app.py
   ```

## Results
> Important Update: Due to a recent security incident involving unauthorized use of my API keys in a DDoS attack, i have temporarily suspended cloud deployment of my Streamlit app and removed all those deployed apps. Please follow the installation guide to run the app locally. I am here to support you with any issues that may arise



## Usage

1. Select the target language from the dropdown menu.
2. Enter the text you want to translate.
3. Click the "Translate" button to get the translated text.
4. If no text is entered, an error message will prompt you to enter valid input.

![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)

## Acknowledgments

- [Groq AI](https://www.groq.com/): For their powerful and efficient language model.
- [Streamlit](https://streamlit.io/): For the elegant and user-friendly UI framework.
