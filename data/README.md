# Qozara Data Configuration

This directory contains the configuration files for the dynamic RSS feed on the homepage.

## 1. Production Setup
To use the live Substack feed, your `config.json` must use the proxy URL:

`{ "rssFeedUrl": "https://api.rss2json.com/v1/api.json?rss_url=https://qozara.substack.com/feed" }`

## 2. Testing with Mocks
To test UI layouts, replace the URL in `config.json` with one of the local mock files:

* **0 Posts:** `"data/mock-0-posts.json"` (Hides the entire section)
* **1 Post:** `"data/mock-1-post.json"` (Shows 1 card, left-aligned)
* **2 Posts:** `"data/mock-2-posts.json"` (Shows 2 cards, left-aligned)
* **4 Posts:** `"data/mock-4-posts.json"` (Sorts by date, displays only the 3 newest cards)

## 3. Local Development Requirement
You must use a local server (like VS Code Live Server or Python `http.server`) to test this on your computer. Opening the HTML file directly from your file explorer will result in a security error.