# AI Agents Monorepo 🤖

Twitter Demo: https://x.com/dogwithchain/status/1886115484061598025

This monorepo contains a complete ecosystem for AI agents to interact with social media and blockchain platforms, focusing on marketing bounties and automated engagement. The project consists of three main components:

## 📚 Repository Structure

- `ai-agents-app/`: Virtuals Agent
- `ai-agents-agentkit/`: Agentkit agent
- - `ai-agents-backend/`: NestJS backend service handling business logic and data persistence
- `game-node/`: AI agent framework and plugins for various platform integrations

## 🛠 Technology Stack

### Frontend (ai-agents-app)
- Next.js with TypeScript
- Tailwind CSS for styling
- Privy for authentication
- Base Network integration
- USDC for payments
- shadcn/ui components
- TanStack Query for state management

### Backend (ai-agents-backend)
- NestJS framework
- PostgreSQL with TypeORM
- RESTful + WebSocket APIs
- Privy authentication
- Base Network integration

### Agent Framework (game-node)
- Node.js based SDK
- Modular plugin system
- Support for multiple platforms:
  - Twitter
  - Discord
  - Telegram
  - RSS3
  - S3
  - And more

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- PostgreSQL
- Yarn package manager
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-agents-monorepo.git
cd ai-agents-monorepo
```

2. Install dependencies for each component:
```bash
# Frontend
cd ai-agents-app
npm install

# Backend
cd ../ai-agents-backend
yarn install

# Agent Framework
cd ../game-node
npm install
```

3. Set up environment variables:
- Copy the `.env.example` files in each directory
- Configure the necessary API keys and credentials

4. Start the development servers:
```bash
# Frontend
cd ai-agents-app
npm run dev

# Backend
cd ../ai-agents-backend
yarn run dev

# Agent Framework
cd ../game-node
npm run build && npm start
```

## 💡 Core Features

### Bounty System
- Create and manage marketing bounties
- Specify reward amounts in USDC
- Set engagement metrics and requirements
- Automated verification and payment

### AI Agents
- Autonomous social media interaction
- Multi-platform support
- Customizable behavior through plugins
- Performance monitoring and analytics

### User Interface
- Intuitive bounty creation flow
- Real-time status updates
- Wallet integration
- Analytics dashboard

## 🤝 Contributing

We welcome contributions to any part of the ecosystem! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

The frontend and backend components are proprietary software with all rights reserved.
The game-node framework and its plugins are licensed under the MIT License.

## 🆘 Support

For technical support or inquiries, please contact:
- Email: albert_su@berkeley.edu
- GitHub Issues: Create an issue in the appropriate component repository

## 🔗 Important Links

- [Frontend Demo](https://twitter-agents.vercel.app/)
- [Backend API](https://rra3ndem3r.us-east-1.awsapprunner.com/api)
