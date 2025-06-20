# React Crypto Tracker
# Crypto Hunter - React Crypto Tracker

A modern, responsive cryptocurrency tracking application built with React that provides real-time market data, interactive charts, and comprehensive coin information.

## 🚀 Live Demo

[**View Live Demo**](https://cryptotracker1076.netlify.app/)

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Integration](#api-integration)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

## ✨ Features

### 🔍 Real-Time Data
- Live cryptocurrency prices and market data
- 24-hour price change indicators with color-coded profit/loss
- Market capitalization rankings
- Trending coins carousel

### 📊 Interactive Charts
- Historical price charts with Chart.js integration
- Multiple time frame options (24 hours, 30 days, 3 months, 1 year)
- Dynamic chart updates based on selected time periods
- Responsive chart design for all screen sizes

### 🌐 Multi-Currency Support
- USD and INR currency support
- Automatic symbol conversion ($ for USD, ₹ for INR)
- Real-time currency switching

### 🎨 User Experience
- Clean, modern Material-UI design
- Dark theme optimized for extended viewing
- Responsive layout for mobile and desktop
- Smooth page transitions and loading states
- Search functionality for quick coin discovery

### 🔗 Navigation
- Single Page Application (SPA) with React Router
- Individual coin detail pages
- Seamless navigation between home and coin pages

## 🛠️ Tech Stack

### Frontend Framework
- **React** (v17.0.2) - Component-based UI library
- **React Router DOM** (v5.2.0) - Client-side routing
- **Material-UI** (v4.12.3) - UI component library

### Data Visualization
- **Chart.js** (v3.5.1) - Chart rendering library
- **React Chart.js 2** (v3.0.4) - React wrapper for Chart.js

### UI Components
- **React Alice Carousel** (v2.5.1) - Responsive carousel component
- **Material-UI Lab** (v4.0.0-alpha.60) - Experimental Material-UI components

### HTTP Client
- **Axios** (v0.21.1) - Promise-based HTTP client

### Styling
- **CSS3** with Google Fonts (Montserrat)
- **Material-UI Theming** system
- **Responsive Design** principles

## 🚀 Installation

### Prerequisites
- Node.js (v14.0.0 or higher)
- npm or yarn package manager

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/crypto-tracker.git
   cd crypto-tracker
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

4. **Build for production**
   ```bash
   npm run build
   # or
   yarn build
   ```

The application will be available at `http://localhost:3000`

## 💡 Usage

### Home Page
- Browse trending cryptocurrencies in the hero carousel
- View comprehensive market data in the sortable table
- Search for specific cryptocurrencies using the search bar
- Navigate through pages using the pagination controls

### Coin Detail Page
- View detailed information about individual cryptocurrencies
- Analyze historical price trends with interactive charts
- Switch between different time frames for chart analysis
- Access comprehensive coin metadata and market statistics

### Currency Switching
- Use the header dropdown to switch between USD and INR
- All prices and market data update automatically
- Currency preference is maintained across page navigation

## 🔌 API Integration

This application integrates with the **CoinGecko API** for real-time cryptocurrency data:

### Endpoints Used
- **Market Data**: `/coins/markets` - Real-time price and market cap data
- **Coin Details**: `/coins/{id}` - Detailed information about specific coins
- **Historical Data**: `/coins/{id}/market_chart` - Historical price data for charts
- **Trending Coins**: `/coins/markets` - Popular cryptocurrencies for carousel

### API Features
- No authentication required
- Rate limiting handled gracefully
- Error handling for network issues
- Automatic data refresh

## 📁 Project Structure

```
src/
├── components/
│   ├── Banner/
│   │   ├── Banner.js          # Hero section component
│   │   └── Carousel.js        # Trending coins carousel
│   ├── CoinInfo.js            # Interactive price charts
│   ├── CoinsTable.js          # Market data table
│   ├── Header.js              # Navigation header
│   └── SelectButton.js        # Custom button component
├── Pages/
│   ├── HomePage.js            # Main landing page
│   └── CoinPage.js            # Individual coin details
├── config/
│   ├── api.js                 # API endpoint configurations
│   └── data.js                # Static data and constants
├── CryptoContext.js           # Global state management
├── App.js                     # Main application component
├── App.css                    # Global styles
└── index.js                   # Application entry point
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
- Follow React best practices and hooks patterns
- Maintain consistent code formatting
- Write meaningful commit messages
- Test your changes across different screen sizes
- Ensure API calls are properly handled

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Credits

**Original Development**: This project was created and developed by [Aarav Singla](https://github.com/aaravsingla). 

The application demonstrates modern React development practices, responsive design principles, and effective API integration for real-time cryptocurrency tracking.

---

### 🌟 Show Your Support

If you found this project helpful, please consider giving it a ⭐ on GitHub!

### 📧 Contact

For questions, suggestions, or collaboration opportunities, feel free to reach out through the repository's issue tracker.

---

*Built with ❤️ using React and modern web technologies*
