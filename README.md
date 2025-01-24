# Website Contextual Chatbot 

## Overview

This Node.js-based chatbot is designed to intelligently scrape and analyze website content, providing contextual responses to user queries using advanced natural language processing.

## Features 

- **Web Scraping**: Extracts content from any specified website using `axios` and `cheerio`
- **Intelligent Response Generation**: Leverages Hugging Face's GPT-2 model for context-aware answers
- **Response Caching**: Improves performance by caching previous query responses
- **User-Friendly Interface**: Simple command-line interaction for easy website exploration

## Prerequisites 

- **Node.js**: Version 14 or above
- **npm**: Comes bundled with Node.js
- **Hugging Face API Key**: Required for natural language processing

## Installation Guide 

### 1. Clone the Repository

```bash
git clone <repository-url>
cd chatbot
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the project root:

```bash
touch .env
```

Add your Hugging Face API key:

```
HF_API_KEY=your_huggingface_api_key
```

## Obtaining a Hugging Face API Key 

1. Visit [Hugging Face](https://huggingface.co/)
2. Log in or create a new account
3. Navigate to **Account Settings**
4. Go to the **API Tokens** section
5. Click **New Token**
6. Name your token (e.g., `Chatbot-Token`)
7. Copy and securely store the generated token

## Running the Chatbot 

### Start the Application

```bash
npm start
```

### Usage Example

1. When prompted, enter a website URL:
    ```
    Enter the website URL to explore: https://example.com/product-page
    ```

2. Ask questions about the website content:
    ```
    ❓ Ask a question: What is the price of this product?
    💬 Chatbot: The price of this product is ₹4,999 with additional offers available.
    ```

3. To end the session, type `quit`

## Security Considerations 

- Keep your Hugging Face API key confidential
- Do not commit the `.env` file to version control
- Consider using environment-specific configurations for different deployment stages

## Contact 
[vinay singh bisht](mailto:vinaysinghbisht17@gmail.com)
