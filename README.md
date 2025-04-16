## Cryptocurrency News Aggregator in Rust

A simple, efficient, and scalable web service built with Rust that aggregates the latest cryptocurrency news. It allows users to search for news by cryptocurrency name or symbol, pulling articles from multiple reputable sources.

## Project Overview

This web service is designed to provide real-time cryptocurrency news through a clean and user-friendly interface. Users can search by cryptocurrency names or symbols, and the service will fetch and display the most recent articles from multiple public news APIs.

## Key Features

Cryptocurrency Search
Users can search by cryptocurrency symbol or name (e.g., BTC, ETH), and the service will retrieve the latest news related to the selected cryptocurrency.

API Integration
News is fetched from reliable sources such as:

CoinGecko API – for cryptocurrency metadata

NewsData.io API – for fetching the latest news articles.

News Display
The results include detailed information, such as:

Article Title

Source

Publication Date

Summary

Link to Full Article

Error Management
The service gracefully handles potential API errors, invalid user inputs, and unavailable data, ensuring a smooth user experience.
