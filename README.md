# AbsentEmailGenerator

## Overview
AbsentEmailGenerator is a Streamlit application designed to assist users in generating formal email templates for explaining their absence to a professor based on a specified reason. The application leverages the GPT-3.5-turbo-16k model to craft these email templates.

## Features
1. **Interactive User Input**: Allows users to specify their reasons for absence.
2. **Instantaneous Email Template Generation**: Crafted email templates are rendered instantly based on the user's input.
3. **Clean UI**: A user-friendly interface empowered by Streamlit.

## Dependencies
- `streamlit`: Used to create and host the web application.
- `langchain`: A custom package that seems to house tools for interfacing with language models.
- `tempfile`: Creates temporary files.

## Usage
1. **Provide the Reason**: Input the reason for your absence in the text input field.
2. **Generate Email**: Click the "Generate Email Template" button after inputting the reason.
3. **See the Template**: The generated formal email template, based on the input reason, will be displayed.

## Setup & Execution
Ensure you've installed all necessary dependencies, especially the `streamlit` and `langchain` packages.

```bash
pip install streamlit langchain
