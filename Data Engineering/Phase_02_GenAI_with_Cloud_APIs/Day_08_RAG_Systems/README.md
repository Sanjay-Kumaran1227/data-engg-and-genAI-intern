# AI Social Media Post Generator using LangChain & Groq

## Project Overview

The AI Social Media Post Generator is a Python-based application that automatically creates engaging social media content using Large Language Models (LLMs). The project leverages LangChain and Groq's Llama 3.1 model to generate platform-specific posts for LinkedIn, Instagram, and Facebook.

Users can customize:

* Social media platform
* Post topic
* Maximum token length
* Emoji inclusion

The application then generates a tailored post optimized for the selected platform.

---

## Features

* AI-powered content generation
* Platform-specific post formatting
* Professional LinkedIn post creation
* Instagram caption generation with hashtags
* Facebook engagement-focused posts
* Custom topic input
* Optional emoji support
* Fast inference using Groq API
* LangChain integration

---

## Technologies Used

* Python
* LangChain
* Groq API
* Llama 3.1 8B Instant Model
* Prompt Engineering

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/social-media-post-generator.git
cd social-media-post-generator
```

### Install Required Packages

```bash
pip install langchain
pip install langchain-groq
pip install langchain-community
pip install langchain-core
```

Or install all dependencies:

```bash
pip install -r requirements.txt
```

---

## Groq API Setup

Create a Groq account and generate an API key.

### Windows

```cmd
set GROQ_API_KEY=your_api_key_here
```

### Linux/Mac

```bash
export GROQ_API_KEY="your_api_key_here"
```

---

## How to Run

Run the notebook or execute the Python script.

Example:

```text
Enter the social media platform: LinkedIn
Enter the topic: Artificial Intelligence in Healthcare
Enter the maximum token length: 150
Include emojis? yes
```

---

## Supported Platforms

### LinkedIn

* Professional tone
* Business-focused content
* Thought-provoking insights

### Instagram

* Engaging captions
* Automatic hashtag suggestions

### Facebook

* Friendly and informative posts
* Community engagement prompts

---

## Model Information

**Model:** llama-3.1-8b-instant

**Provider:** Groq

**Framework:** LangChain

---

## Workflow

```text
User Input
     ↓
Prompt Template Selection
     ↓
LangChain Processing
     ↓
Groq Llama 3.1 Model
     ↓
AI Generated Social Media Post
```
