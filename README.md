# 🚀 Minimal Flowise Proxy Implementation

A minimal FastAPI backend (port 5000) and HTML frontend (port 5002) for proxying Flowise chat requests with basepath support.

## 📁 Structure

```
flowise-proxy-service-py-mini/
├── backend/
│   ├── .env                    # Environment configuration
│   ├── requirements.txt        # Python dependencies
│   └── main.py                 # FastAPI application
├── frontend/
│   └── index.html             # Simple chat interface
├── frontend_server.py         # Python HTTP server for frontend
├── start-all.bat             # Start both services (Windows)
├── start-backend.sh          # Start backend only (Unix)
├── start-frontend.sh         # Start frontend only (Unix)
├── start-backend.bat         # Start backend only (Windows)
└── start-frontend.bat        # Start frontend only (Windows)
```

## 🔧 Prerequisites

1. **Python 3.7+** installed
2. **Flowise instance** running on `http://localhost:3000`
3. **Chatflow ID** from your Flowise dashboard

