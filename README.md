# Quote Generator

A simple, responsive web app that displays random quotes from two categories — **Education** and **Kalam** (quotes by A. P. J. Abdul Kalam). Built with vanilla HTML, CSS, and JavaScript.

## Features

- 🔀 Random quote generator — click "New quote" to get a fresh one from the selected category
- 🏷️ Category toggle — switch between "Education" and "Kalam" quote sets
- 📋 Copy to clipboard — copy the current quote with one click
- 🎨 Clean, card-based UI with a soft purple theme

## Tech Stack

- HTML5
- CSS3 (Flexbox layout)
- JavaScript (DOM manipulation, Clipboard API)

## How It Works

- Two arrays of quote objects (`educational` and `kalam`), each with `text` and `author`
- Clicking a category heading switches the active quote set
- The "New quote" button picks a random quote from the current set
- The "Copy to clipboard" button uses the Clipboard API to copy the quote text

## Live Demo


## Getting Started

1. Clone this repo
   ```
   git clone https://github.com/vinothinisuresh07/quote-generator.git
   ```
2. Open `index.html` in your browser — no build steps needed

## Author

**Vinothini** — [GitHub](https://github.com/vinothinisuresh07)
