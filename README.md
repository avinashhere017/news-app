# News Application

This is a news application built with HTML, CSS, and JavaScript that fetches and displays the latest news based on different categories and search queries. It uses the News API to retrieve news articles.

## Features

- Display news articles by category (Cricket, Finance, Politics)
- Search for news articles by keyword
- Responsive design for different screen sizes
- Clickable news cards that open the full article in a new tab

## Technologies Used

- HTML
- CSS
- JavaScript
- News API

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/news-application.git
    cd news-application
    ```

2. Open `index.html` in your browser to view the application.

## Code Structure

- `index.html`: The main HTML file containing the structure of the web page.
- `style.css`: The CSS file containing styles for the web page.
- `script.js`: The JavaScript file containing the logic for fetching and displaying news articles.

## How It Works

1. The application loads with news articles about India by default.
2. Users can click on navigation links to view news articles by category.
3. Users can search for news articles by entering a keyword in the search bar and clicking the search button.
4. News articles are fetched from the News API and displayed as cards on the page.
5. Clicking on a news card opens the full article in a new tab.

## API Key

This application uses the News API. To use this application, you need an API key from the News API. Replace the `API_KEY` variable in `script.js` with your API key.

```javascript
const API_KEY = "your_api_key_here";
