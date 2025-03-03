## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v16 or higher)
- npm
- Docker
- PostgreSQL

### Installation
1. **Clone the Repository:**
```
  git clone https://github.com/your-username/SocialSync.git
  cd SocialSync/search-service
```

2. **Install Dependencies:**
```
  npm install
```

3. **Set Up Environment Variables:**

Create a `.env` file in the root directory and add the following:
```
PORT=3004
MONGO_URI=mongodb://127.0.0.1:27017
JWT_SECRET=
NODE_ENV=development
REDIS_URL=redis://localhost:6379
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
RABBITMQ_URL=amqp://guest:guest@localhost:5672

```

1. **Start the Server:**
```
  npm run dev
```

1. **Access the Application:**

The server will be running at `http://localhost:3004`.

## API Documentation

Explore the APIs using the following endpoints:

#### Base URL - 
  ```
  http://localhost:3000/v1
  ```


## Endpoints

| HTTP Verbs | Endpoints                 | Action                  |
| ---------- | ------------------------- | ----------------------- |
| GET        | /search/posts?query=Hello | Search post using query |

