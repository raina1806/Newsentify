# Newsentify

**Newsentify** is an AI-powered news aggregator that fetches and categorizes news articles based on predefined keywords while providing real-time sentiment analysis and dynamic text summarization using natural language processing (NLP) techniques.

## Features

- **News Aggregation**: Uses the NewsAPI to fetch the latest news articles.
- **Categorization**: Automatically categorizes articles into topics like Technology, Sports, and Finance.
- **Sentiment Analysis**: Integrates TextBlob to determine the sentiment (Positive, Negative, or Neutral) of news articles.
- **Dynamic Summarization**: Summarizes article content dynamically using NLP techniques.
- **Customizable Filters**: Users can filter articles by categories, sentiment, and keywords.

## Technologies Used

- **Backend**: Flask (Python)
- **Sentiment Analysis**: TextBlob
- **API Integration**: NewsAPI
- **Frontend**: HTML, CSS, Jinja2 templates

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/newsentify.git
    cd newsentify
    ```
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Add your NewsAPI key in a `config.py` file:
    ```python
    API_KEY = 'your_api_key_here'
    ```

## Usage

1. Start the Flask server:
    ```bash
    python app.py
    ```
2. Open a web browser and go to `http://127.0.0.1:5000/`.
3. Use the search bar and filters to explore news articles.

## Project Structure

```
newsentify/
├── templates/
│   ├── index.html
├── static/
│   ├── styles.css
├── app.py
├── config.py
├── requirements.txt
└── README.md
```

## Screenshots


### News Dashboard
![News Dashboard]("https://github.com/raina1806/Newsentify/blob/2e97589a4a691cc903525a3711268da94cbcbfee/Dashboard.jpeg")

## Future Enhancements

- Advanced NLP models for more accurate summarization and sentiment analysis.
- User accounts for personalized news feeds.
- Integration with additional news APIs for broader coverage.
- Fake News Detection
- Advanced categories

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


**Newsentify** – Your AI-powered news companion for smarter, sentiment-aware news consumption.
