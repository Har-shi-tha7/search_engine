# search_engine
app.js
API Endpoints:
Add Article:

Endpoint: POST /articles
Input: JSON with title, content, tags (array), and date.
Response: Returns the ID of the created article.
Search Articles:

Endpoint: GET /articles/search
Query Parameters:
keyword: Search term for title and content.
tags: Filter articles by tags (optional).
sort: relevance (default) or date
