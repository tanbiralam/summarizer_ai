
# Sumz: Article Summarizer with OpenAI GPT-4

Sumz is a web application designed to simplify your reading experience by providing concise summaries for lengthy articles. It utilizes the powerful OpenAI GPT-4 to generate accurate and coherent summaries.

## Features

- **Article Summarization:** Input the URL of an article, and Summize will generate a summary using OpenAI GPT-4.
- **History:** Access a history of previously summarized articles for quick reference.
- **Clipboard Copy:** Easily copy article URLs to the clipboard for sharing.

## Getting Started

### Prerequisites

Before running the application, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tanbiralam/summarizer_ai.git
   cd summarizer_ai
   ```

2.  Install dependencies:
        
    `npm install` 
    

### Usage

1.  Start the development server:
        
    `npm start` 
    
2.  Open your browser and visit http://localhost:3000 to use Sumz.
    

### API Key

To use Summize, you need to obtain an API key for the OpenAI GPT-4 API. Follow the instructions on the [OpenAI website](https://www.openai.com/) to obtain your API key. Once obtained, set the key in the `src/services/article.js` file.

`const rapidApiKey = '<YOUR_OPENAI_API_KEY>';`

## Project Structure

-   **src/components/Demo.jsx:** Main component handling article summarization.
-   **src/components/Hero.jsx:** Header component displaying the app's logo and title.
-   **src/services/article.js:** API setup for interacting with the OpenAI GPT-4 API.
-   **src/services/store.js:** Redux store configuration.
-   **src/App.jsx:** Main entry point rendering components.
## Live Preview

Explore a live preview of Sumz: [Live Preview](https://ai-sum.netlify.app/)
