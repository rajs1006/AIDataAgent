# AI Data Agent

An AI-powered data agent that connects with multiple data sources and allows natural language queries.

## Features

- User authentication
- Multiple data source connections
- Real-time file monitoring
- Natural language querying
- Rich chat interface
- Dark mode UI

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   # Frontend
   cd frontend && npm install

   # Backend
   cd backend && pip install -r requirements.txt
   ```

3. Set up environment variables
4. Run with Docker:
   ```bash
   docker-compose up
   ```

## Development

- Frontend: http://localhost:3000
- Backend: http://localhost:8000
- MongoDB: localhost:27017
- Qdrant: localhost:6333

## Architecture

### Frontend

- Next.js 14 with App Router
- Shadcn/UI components
- React Query
- Zustand
- TailwindCSS

### Backend

- FastAPI
- MongoDB
- Qdrant
- OpenAI
- File watcher

