# Backend - FastAPI Application

FastAPI backend with Google Gemini LLM integration.

## Quick Start

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Create a `.env` file with your Google API key:

   ```
   GOOGLE_API_KEY=your_api_key_here
   ```

3. Run the server:
   ```bash
   uvicorn main:app --reload
   ```

The server will start at http://localhost:8000

## API Documentation

Once the server is running, visit:

- **Swagger UI**: http://localhost:8000/docs
- **ReDoc**: http://localhost:8000/redoc

## Endpoints

- `GET /` - Welcome message
- `GET /health` - Health check
- `GET /api/random-quote` - Generate random quote using Gemini LLM

For detailed setup instructions, see the main [README.md](../README.md) file.
