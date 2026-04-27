# Qozara.github.io

This repository serves as the root landing page for the Qozara collective. It is a static site built with modern web technologies, designed to showcase our research, projects, and publications.

## 🚀 Features

- **Dynamic Content Loading**: Fetches project data from `data/projects.json` and RSS feeds from `data/config.json`.
- **Responsive Design**: Built with a mobile-first approach using Flexbox and Grid.
- **Modern Typography**: Utilizes Google Fonts (Inter, Outfit, Space Grotesk) for a premium editorial look.
- **Dark Mode Support**: Automatically adapts to the user's system preference.

## 🛠️ Development

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge).
- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) (optional, for running a local server).

### Running Locally

1.  **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd qozara.github.io
    ```

2.  **Option A: Using VS Code (Recommended)**
    - Open the folder in VS Code.
    - Install the **Live Server** extension.
    - Right-click `index.html` and select "Open with Live Server".

3.  **Option B: Using Node.js**
    - Install a simple static server:
      ```bash
      npm install -g serve
      ```
    - Run the server:
      ```bash
      serve .
      ```
    - Open the URL provided by `serve` (usually `http://localhost:3000`) in your browser.

### Updating Content

- **Projects**: Edit `data/projects.json` to add, remove, or modify project cards.
- **RSS Feed**: Edit `data/config.json` to change the `rssFeedUrl`.

## 📂 Repository Structure

```
qozara.github.io/
├── data/
│   ├── projects.json       # Project data and metadata
│   └── config.json         # Configuration (e.g., RSS feed URL)
├── assets/
│   └── logo.png            # The Qozara logo
├── index.html              # The main landing page
└── README.md               # This file
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
