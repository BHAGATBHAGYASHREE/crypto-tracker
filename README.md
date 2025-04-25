# Cryptocurrency Price Tracker

A fully responsive React application that simulates real-time cryptocurrency price tracking similar to CoinMarketCap. Built with Next.js, Redux Toolkit, TypeScript, and Tailwind CSS.

## Features

- Real-time cryptocurrency price updates (simulated or via WebSocket)
- Responsive design that works on mobile, tablet, and desktop
- Sorting and filtering capabilities
- Color-coded percentage values
- 7-day price charts
- LocalStorage persistence for user preferences
- Unit tests for Redux reducers and selectors

## Tech Stack

- **Frontend Framework**: Next.js (App Router)
- **State Management**: Redux Toolkit
- **Styling**: Tailwind CSS with shadcn/ui components
- **Language**: TypeScript
- **Testing**: Jest

## Architecture Overview

The application follows a modern React architecture with the following key components:

- **Redux Store**: Central state management using Redux Toolkit
- **Crypto Slice**: Manages cryptocurrency data, filtering, sorting, and WebSocket connection
- **Components**: Modular UI components for the crypto table and related UI elements
- **Hooks**: Custom hooks for localStorage persistence
- **Utils**: Helper functions for formatting currencies, numbers, and percentages

## Getting Started

1. Clone the repository
2. Install dependencies:
   \`\`\`
   npm install
   \`\`\`
3. Run the development server:
   \`\`\`
   npm run dev
   \`\`\`
4. Open [http://localhost:3000](http://localhost:3000) in your browser

## WebSocket Integration

The application supports real-time data updates via WebSocket connection to Binance's public API. You can toggle between mock data and real data using the button in the UI.

## Testing

Run the test suite with:

\`\`\`
npm test
\`\`\`

## Future Enhancements

- Add more filter options (top gainers, losers, etc.)
- Implement detailed view for individual cryptocurrencies
- Add more unit and integration tests
- Implement dark mode
- Add more data sources and comparison features

## Demo

![Cryptocurrency Tracker Demo]
https://youtu.be/zQnjzWdCE5s
