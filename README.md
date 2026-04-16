# DuckDuckGo Search Skill for AI Edge Gallery

This skill allows local LLMs (like Gemma) to search the web using the official DuckDuckGo Instant Answer API.

## How to Deploy to GitHub Pages

To use this skill via URL in the **AI Edge Gallery** app, follow these steps:

1. **Create a new GitHub Repository** (e.g., `duckduckgo-search-skill`).
2. **Upload all the files** in this folder to the root of the repository.
3. **Go to Settings > Pages** in your GitHub repository.
4. **Set the Source** to `Deploy from a branch` and select your main branch.
5. **Wait for deployment** (it usually takes a minute).
6. **Get your URL**: It will look like `https://your-username.github.io/duckduckgo-search-skill/`.

## How to Load in Edge Gallery App

1. Open the **Edge Gallery** app on your phone.
2. Go to the **Agent Skills** section with your model (Gemma).
3. Tap the **Skills** chip.
4. Tap the **(+)** button.
5. Select **Load skill from URL**.
6. Paste your GitHub Pages URL (e.g., `https://your-username.github.io/duckduckgo-search-skill/`).
7. **Important**: Make sure the URL does *not* end with `SKILL.md`.

## Features
- **Instant Answers**: Fetches abstract summaries from DuckDuckGo.
- **Related Topics**: Provides snippets if no direct answer is found.
- **Privacy**: Does not require any API keys or registration.
