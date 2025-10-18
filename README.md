# 🌊 MIZUKAGAMI Memory - Backend

**The world's first multi-AI memory integration platform from Japan.**

Integrate memory across ChatGPT, Claude, and Gemini with a single platform.

## 🎯 Features

- **Multi-AI Memory**: Store and retrieve memories across all AI platforms
- **Vector Search**: Semantic search powered by Qdrant
- **Multi-Tenant**: Secure user isolation with Row Level Security
- **E2E Encryption**: Zero-knowledge architecture
- **MCP Server**: Native Claude Desktop integration
- **API Proxy**: ChatGPT/Gemini SDK compatibility

## 🛠️ Tech Stack

- **Framework**: FastAPI 0.104+
- **Database**: PostgreSQL 15+ (Supabase)
- **Vector DB**: Qdrant 1.7+
- **Cache**: Redis 7+
- **Auth**: Supabase Auth
- **Payment**: Stripe

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/kyousuke10000/mizukagami-memory-backend.git
cd mizukagami-memory-backend

# Install dependencies
pip install -r requirements.txt

# Setup environment
cp .env.example .env

# Run migrations
alembic upgrade head

# Start server
uvicorn app.main:app --reload
```

## 📚 Documentation

- [Architecture](./ARCHITECTURE.md)
- [API Docs](http://localhost:8000/docs)
- [Development Guide](./docs/development.md)

## 📅 Roadmap

See [Linear Project](https://linear.app) for detailed roadmap.

### Milestone 1: Core Infrastructure (Week 1-3)
- [x] Project setup
- [ ] Database schema
- [ ] Memory Core API
- [ ] MCP Server

### Milestone 2: Full Integration (Week 4-6)
- [ ] ChatGPT integration
- [ ] Gemini integration

### Milestone 3: Optimization (Week 7-9)
- [ ] Performance tuning
- [ ] E2E encryption

### Milestone 4: Launch (Week 10-12)
- [ ] Beta testing
- [ ] Official launch 🚀

---

**静けさの中で、全てのAIが記憶を共有する。**

*Built with serene philosophy from Japan 🇯🇵*
