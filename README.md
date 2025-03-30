
# Crypto Listing and Price Checking Website

Welcome to the Crypto Listing and Price Checking Website, an application similar to CoinMarketCap, allowing users to track cryptocurrency prices and listings. This project features an admin panel for managing crypto listings and a public view for all users.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [API Integration](#api-integration)
- [Database](#database)
- [Running the Application](#running-the-application)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Admin Panel**: Manage and list cryptocurrencies.
- **Public View**: Users can search and track cryptocurrency prices.
- **Watchlist Functionality**: Users can create and manage their own watchlists.
- **Persistent Storage**: All data is stored in a PostgreSQL database via Drizzle ORM.
- **Market Data Integration**: Real-time price updates using the CoinGecko API.

## Technologies Used

- **Frontend**: React, TypeScript, Axios
- **Backend**: Node.js, Express
- **Database**: PostgreSQL
- **ORM**: Drizzle ORM
- **API**: CoinGecko API

## Getting Started

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Ashikurrahaman287/Crypto-Track
   cd crypto-listing-website
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up the PostgreSQL database**:
   - Ensure PostgreSQL is installed and running.
   - Create a new database for the application.

4. **Configure the database**:
   - Update the database configuration in `server/db.ts`.

5. **Run database migrations**:
   ```bash
   npm run db:push
   ```

6. **Run the application**:
   ```bash
   npm run dev
   ```

## API Integration

The application retrieves cryptocurrency market data from the [CoinGecko API](https://www.coingecko.com/en/api).

## Database

The application uses PostgreSQL for data storage. The `Drizzle ORM` is utilized to manage database interactions, making migrations and queries seamless.

## Running the Application

You can view the application by navigating to `http://localhost:3000` in your web browser. The admin panel is accessible only after login.

## Contributing

Contributions are welcome! Please create a pull request for any changes or fixes you would like to propose.

![image](https://github.com/user-attachments/assets/f102430e-5308-4b00-b985-1d3be68e8062)

