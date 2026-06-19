# PolicyClear 🛡️

An AI-powered insurance policy explainer that converts complex policy documents into plain-English summaries — instantly, in your browser.

## What it does
Upload any insurance policy PDF (or paste the text), and PolicyClear gives you:
- Policy type and summary
- What's covered and what's not
- Waiting periods and claim limits
- Common reasons claims get rejected
- Red flags to watch out for
- Direct links to cashless hospital network locators for major Indian insurers

## How it works
- Runs entirely in the browser — no backend, no server, no data stored
- Extracts text from PDFs using [pdf.js](https://mozilla.github.io/pdf.js/)
- Sends extracted text to the [Claude AI API](https://www.anthropic.com) for analysis
- Returns a structured plain-English breakdown

## How to use
1. Open the [live demo](https://advaith2801.github.io/policyclear)
2. Enter your Anthropic API key (stored in memory only — never saved)
3. Upload a PDF or paste your policy text
4. Click Analyze

## Tech used
- Vanilla HTML, CSS, JavaScript
- pdf.js for in-browser PDF extraction
- Anthropic Claude API (claude-sonnet-4-6)

## Built by
Advaith — fresher building AI and automation projects.
