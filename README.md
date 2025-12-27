# Code Review Assistant

## Overview

The Code Review Assistant is an AI-powered web application that provides automated code analysis and review capabilities. Built as a single-page HTML application, it leverages OpenRouter.ai's API to deliver intelligent code reviews using the GPT-OSS-120B model. Users can paste their code into the interface and receive structured feedback including improvement suggestions and positive aspects of their code. The application features a modern, glassmorphic UI design with a gradient purple theme, secure API key management via localStorage, and robust error handling for API responses. It supports code review for any programming language without requiring language detection, making it a versatile tool for developers seeking quick, AI-driven code quality insights.

**Live Demo:** [https://walidahmed90.github.io/Code-Review-Assistant/](https://walidahmed90.github.io/Code-Review-Assistant/)

## Features

- **AI-Powered Code Review**: Utilizes OpenRouter.ai's GPT-OSS-120B model for intelligent code analysis
- **Structured Feedback**: Returns JSON-formatted results with improvements and positive feedback
- **Secure API Key Management**: Stores API keys locally using browser localStorage
- **Modern UI**: Glassmorphic design with gradient backgrounds and smooth animations
- **Error Handling**: Comprehensive error handling with helpful user messages
- **Example Code Samples**: Quick-load buttons for JavaScript, Python, and React examples

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Tailwind CSS (CDN)
- **Icons**: Lucide Icons
- **AI Service**: OpenRouter.ai API
- **Model**: openai/gpt-oss-120b:free

## Setup Instructions

1. Open `code_review.html` in a web browser
2. Click the settings icon to configure your OpenRouter API key
3. Enter your API key (format: `sk-or-v1-...`)
4. For free models, ensure "Free model publication" is enabled in your [OpenRouter privacy settings](https://openrouter.ai/settings/privacy)
5. Paste your code and click "Review Code with AI"

## Usage

1. Enter or paste your code in the text area
2. Click the "Review Code with AI" button
3. Wait for the AI to analyze your code
4. Review the structured feedback showing:
   - **Improvements**: List of issues and suggestions for better code
   - **What's Good**: Positive aspects and strengths of your code

## API Requirements

- OpenRouter.ai API key (get one at [openrouter.ai](https://openrouter.ai))
- Free model requires privacy settings configuration

## License

This project is open source and available for use and modification.

