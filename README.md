# Excel Flow

Excel Flow is a browser-based spreadsheet with formulas, charts, formatting tools, and a workbook-aware AI agent powered by Groq.

## Groq AI setup

1. Open `index.html` and set `window.GROQ_API_KEY` near the bottom of the file.
2. Select **AI** in the browser and reload the page after changing the key.

The app calls Groq's OpenAI-compatible chat completions endpoint with `llama-3.3-70b-versatile` and `openai/gpt-oss-120b` fallback support. Never commit an API key to this repository.

## Search visibility

The app includes a descriptive page title, search/social metadata, `SoftwareApplication` structured data, and `robots.txt`. After deploying it to a public HTTPS URL:

1. Add the deployed site to Google Search Console.
2. Verify ownership using the existing Google verification file.
3. Request indexing for the homepage.
4. Add a sitemap in Search Console if the site grows beyond this single page.

Search rankings and AI Overview inclusion are determined by Google and cannot be guaranteed by metadata alone.

Author
Taraksh Choudhary
