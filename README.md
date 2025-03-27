# 🚀 AI Project Idea Generator

## Overview
The **AI Project Idea Generator** is a web-based tool that helps users generate unique and impactful project ideas based on their domain, experience level, skills, project type, and preferred tech stack. This project utilizes Google Gemini API to generate meaningful project suggestions tailored to the user’s inputs.

## Features
- **User-Friendly Interface**: Built with Gradio for easy interaction.
- **Custom Project Ideas**: Generates project ideas based on user inputs like domain, experience level, and tech stack.
- **AI-Powered Suggestions**: Uses Gemini 1.5 Flash model for intelligent recommendations.
- **Detailed Project Plans**: Provides a project title, objectives, technologies, steps, and expected outcomes.

## Technologies Used
- **Python**
- **Gradio** (for UI)
- **Google Generative AI (Gemini 1.5 Flash)**
- **dotenv** (for API key management)

## Installation and Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/ai-project-idea-generator.git
   cd ai-project-idea-generator
   ```
2. Install dependencies:
   ```sh
   pip install gradio google-generativeai python-dotenv
   ```
3. Create a `.env` file and add your API key:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```
4. Run the application:
   ```sh
   python app.py
   ```

## Usage
1. Enter your domain (e.g., Data Science, AI, Web Development).
2. Select your experience level (Beginner, Intermediate, Advanced).
3. Optionally, enter relevant skills and preferred tech stack.
4. Choose the type of project (Practical Implementation, Case Study, Research Paper).
5. Click **Generate Project Idea** and get a detailed project suggestion.

## Running in Google Colab
If using Google Colab, install dependencies first:
```python
!pip install gradio google-generativeai python-dotenv
```
Upload and load the `.env` file:
```python
from google.colab import files
uploaded = files.upload()
from dotenv import load_dotenv
load_dotenv('.env.txt')
```

## Future Improvements
- Add project idea history and save functionality.
- Provide multiple project suggestions per request.
- Enhance UI with more interactive elements.
