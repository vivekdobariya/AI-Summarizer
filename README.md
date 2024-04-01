# Summarize Article With OpenAI Gpt-4

Simplify your reading with Summize, an open-source article summarizer that transforms lengthy articles into clear and concise summaries. This project utilizes the Rapid API Article Extractor and Summarizer service to extract and summarize articles. It provides a user-friendly interface where users can enter a URL, and the application will retrieve the article from the provided URL, summarize it, and display the summary.

## Deployment 🔗 :
[AI Summarizer-Link](https://text-summarization-ai.netlify.app/)

![image](https://github.com/vivekdobariya/AI-Summarizer/assets/126269382/77b7eca1-d889-4789-8111-a58af9c974e6)
## Features

- Extract and summarize articles using the Rapid API Article Extractor and Summarizer service.
- Save and display a history of previously summarized articles.
- Copy the article URL to the clipboard for easy sharing.

## Prerequisites

Before running the application, you need to obtain a Rapid API key for the Article Extractor and Summarizer service. Follow the steps below to get your API key:

1. Sign up for a Rapid API account at [Rapid API](https://rapidapi.com/).
2. Subscribe to the Article Extractor and Summarizer API.
3. Retrieve your API key from the Rapid API dashboard.

## Installation

1. Clone the repository: `git clone https://github.com/vivekdobariya/AI-Summarizer`
2. Navigate to the project directory: `cd AI-Summarizer`
3. Install the dependencies: `npm install`

## Rapid API: Article Extractor and Summarizer

- **Link**: [Rapid API - Article Extractor and Summarizer](https://rapidapi.com/restyler/api/article-extractor-and-summarizer)

## Configuration

Add a `.env` file in the cloned or downloaded folder. Open the `.env` file and replace the `VITE_RAPID_API_ARTICLE_KEY` placeholder with your Rapid API key.

## Usage

1. Start the application: `npm run dev`.
2. Open your web browser and navigate to `http://localhost:5173`.
3. Enter a URL of an article in the input field.
4. Click the submit button to extract and summarize the article.
5. The summarized article will be displayed below.
6. To copy the article URL, click the copy button next to the URL.
7. Previously summarized articles will be displayed in the search history section.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgements

- Rapid API - Provides the Article Extractor and Summarizer service.
