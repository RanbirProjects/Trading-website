# Advanced Trading Platform

A full-stack trading application built with the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Features

- Real-time market data and price updates
- User authentication and authorization
- Portfolio management
- Trading functionality
- Market analysis tools
- Responsive design
- Real-time notifications

## Tech Stack

- Frontend: React.js, Redux, Material-UI, WebSocket
- Backend: Node.js, Express.js
- Database: MongoDB
- Real-time: Socket.io
- Authentication: JWT
- API Integration: Alpha Vantage, Binance API

## Project Structure

```
trading-app/
├── client/                 # Frontend React application
├── server/                 # Backend Node.js/Express application
├── .gitignore
└── README.md
```

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd server
   npm install

   # Install frontend dependencies
   cd ../client
   npm install
   ```

3. Create a `.env` file in the server directory with the following variables:
   ```
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ALPHA_VANTAGE_API_KEY=your_alpha_vantage_api_key
   BINANCE_API_KEY=your_binance_api_key
   BINANCE_API_SECRET=your_binance_api_secret
   ```

4. Start the development servers:
   ```bash
   # Start backend server
   cd server
   npm run dev

   # Start frontend server
   cd ../client
   npm start
   ```

## License

MIT 