<h1 align="center">📝 ThinkBoard✨</h1>

![Demo App](/frontend/public/video.gif)

Destaques:

- 🧱 Aplicativo Full-Stack desenvolvido com MERN Stack (MongoDB, Express, React, Node)
- ✨ Crie, atualize e exclua notas com título e descrição
- 🛠️ Criei e testei uma API REST totalmente funcional
- ⚙️ Limitação de taxa com Upstash Redis — um conceito do mundo real explicado de forma simples
- 🚀 Interface de usuário totalmente responsiva
- 🌐 Métodos HTTP, códigos de status e SQL vs NoSQL
---

## 🧪 .env Setup

### Backend (`/backend`)

```
MONGO_URI=<your_mongo_uri>

UPSTASH_REDIS_REST_URL=<your_redis_rest_url>
UPSTASH_REDIS_REST_TOKEN=<your_redis_rest_token>

NODE_ENV=development
```

## 🔧 Run the Backend

```
cd backend
npm install
npm run dev
```

## 💻 Run the Frontend

```
cd frontend
npm install
npm run dev
```