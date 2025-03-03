## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v16 or higher)
- npm
- Docker
- PostgreSQL (if not using Docker)

### Installation
1. **Clone the Repository:**
```
  git clone https://github.com/your-username/SocialSync.git
  cd SocialSync/api-gateway
```

2. **Install Dependencies:**
```
  npm install
```

3. **Set Up Environment Variables:**

Create a `.env` file in the root directory and add the following:
```
  PORT=3000
  JWT_SECRET=
  NODE_ENV=development
  IDENTITY_SERVICE_URL=http://localhost:3001
  POST_SERVICE_URL=http://localhost:3002
  MEDIA_SERVICE_URL=http://localhost:3003
  SEARCH_SERVICE_URL=http://localhost:3004
  REDIS_URL=redis://localhost:6379
```

1. **Start the Server:**
```
  npm run dev
```

1. **Access the Application:**

The server will be running at `http://localhost:3000`.