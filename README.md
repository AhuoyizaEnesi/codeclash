# CodeClash⚡

**Real-Time Competitive Programming Platform**

CodeClash transforms coding interview preparation into an engaging competitive experience. Challenge peers in real-time LeetCode problem-solving battles, track your progress through ranking systems, and build coding skills through gamified learning.

## Overview

CodeClash is a competitive programming platform designed to make coding practice more engaging and social. Users can participate in head-to-head coding battles, track their skill progression through a comprehensive ranking system, and compete on global leaderboards.

## Features

### Core Functionality
- **Real-Time Battles**: Engage in live 1v1 coding competitions with synchronized problem solving
- **Authentication System**: Secure login via email registration or Google OAuth integration
- **User Profiles**: Customizable profiles with avatar selection, skill tracking, and goal setting
- **Ranking System**: Progressive skill-based ranking from Bronze to Grandmaster tiers
- **Global Leaderboards**: Community-wide competition tracking and statistics
- **Responsive Design**: Modern, clean interface built with Tailwind CSS

## Technology Stack

### Frontend
- **React 18**: Modern React with hooks and functional components
- **Tailwind CSS**: Utility-first CSS framework for responsive design
- **Socket.io Client**: Real-time bidirectional communication
- **Lucide React**: Comprehensive icon library

### Backend
- **Node.js**: JavaScript runtime environment
- **Express.js**: Web application framework
- **Socket.io**: WebSocket implementation for real-time features
- **JWT**: JSON Web Token authentication with 14-day token expiration
- **bcryptjs**: Password hashing and security

### Planned Integrations
- **PostgreSQL**: Relational database for data persistence
- **Judge0 API**: Code execution and testing environment
- **Monaco Editor**: Advanced code editing interface

## Installation

### Prerequisites
- Node.js version 16 or higher
- npm version 8 or higher

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/Code-Clash.git
   cd Code-Clash
   ```

2. **Install Root Dependencies**
   ```bash
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd client
   npm install
   ```

4. **Install Backend Dependencies**
   ```bash
   cd ../server
   npm install
   ```

### Environment Configuration

#### Client Environment Variables
```bash
cp client/.env.example client/.env.local
```

#### Server Environment Variables
```bash
cp server/.env.example server/.env
```

### Development Server

From the root directory, start both servers:
```bash
npm run dev
```

This will launch:
- **Frontend**: http://localhost:3000
- **Backend**: http://localhost:3001

## Available Scripts

### Root Directory
- `npm run dev` - Start both frontend and backend servers
- `npm run client` - Start frontend server only
- `npm run server` - Start backend server only

### Frontend (client/)
- `npm start` - Start React development server
- `npm run build` - Create production build

### Backend (server/)
- `npm run dev` - Start server with nodemon (auto-restart on changes)
- `npm start` - Start production server

## Project Structure

```
CodeClash/
├── client/          # React frontend application
├── server/          # Express backend application
├── package.json     # Root package configuration
└── README.md        # Project documentation
```

## Contributing

We welcome contributions to CodeClash. Please ensure all code follows the established patterns and includes appropriate testing.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For questions, issues, or feature requests, please open an issue on the GitHub repository.
