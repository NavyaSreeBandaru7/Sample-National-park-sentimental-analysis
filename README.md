# Sample-National-park-sentimental-analysis
📊 Universal Website Sentiment Analyzer
This Streamlit app analyzes text content from any website. It provides sentiment analysis and categorizes content by topic.

Features
Works with any website - no domain restrictions
Extracts and analyzes text content from web pages
Performs sentiment analysis (positive, negative, neutral)
Categorizes content by topic (hiking, fees, facilities, etc.)
Visualizes sentiment distribution across categories
Shows confidence scores for sentiment analysis
Generates word clouds from extracted text
Attempts to identify fees, facilities, and activities when relevant
Usage
Enter any website URL
Click "Analyze" to process the webpage
Explore the visualizations and extracted information
Categories Analyzed
Hiking: trail conditions, paths, hiking experiences
Fees: costs, prices, payment information
Equipment: gear, supplies needed for activities
Water: lakes, rivers, water features
Facilities: restrooms, visitor centers, amenities
Example URLs
You can analyze any website, such as:

Product reviews: https://www.amazon.com/product-reviews/...
Travel destinations: https://www.tripadvisor.com/...
Restaurant reviews: https://www.yelp.com/...
News articles: https://www.cnn.com/...
Blog posts: https://medium.com/...
Technical Details
This app uses:

Transformers library with DistilBERT for sentiment analysis
SpaCy for natural language processing
Beautiful Soup for web scraping
Matplotlib and WordCloud for visualizations
