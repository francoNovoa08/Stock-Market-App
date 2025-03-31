# Stock Market App

## Overview
Stock Market App is a modern Android application built using Kotlin with Clean Architecture principles. 
It fetches stock market data from the Alpha Vantage API, displays a list of companies, and allows users to view detailed company information along with a stock chart showing how the stock changed during the previous day. 
The app also caches company data locally to counteract the low requests the API has.

## Features
- Fetch and display a list of stock market companies from the Alpha Vantage API
- View detailed company information, including stock performance
- Stock chart to visualise price changes over the last trading day
- Caching with Room database for offline accessibility.
- Uses Retrofit for network requests
- Dependency Injection with Dagger/Hilt
- Clean Architecture principles

## Tech Stack
- **Language**: Kotlin
- **Architecture**: Clean Architecture
- **Networking**: Retrofit
- **Dependency Injection**: Dagger/Hilt
- **Local Storage**: Room Database

## Setup and Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repository-url.git
   ```
2. Open the project in Android Studio
3. Sync Gradle and build the project
4. Run the app on an emulator or physical device

## API Integration
The app uses the Alpha Vantage API to fetch stock market data. The relevant endpoints are:
- **Company Listings**: Fetches a list of available companies.
- ****: Fetches stock data for a specific company.
- **Intraday Data**: Retrieves stock price changes over the last trading day.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
For contributions, feature requests, or issues, feel free to submit a pull request or open an issue!

