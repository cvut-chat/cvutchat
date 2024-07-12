# CVUT Chat

## Installation

```bash
git clone https://github.com/cvut-chat/cvutchat
cd cvutchat
git clone https://github.com/cvut-chat/cvutchat-socket
git clone https://github.com/cvut-chat/cvutchat-rest
git clone https://github.com/cvut-chat/cvutchat-auth
git clone https://github.com/cvut-chat/cvutchat-weather
git clone https://github.com/cvut-chat/cvutchat-data
git clone https://github.com/cvut-chat/cvutchat-frontend
docker compose up -d
```

## How it works
![Diagram](https://i.imgur.com/kZ4WNPT.png)

## DEV
### Testing API
Register
```bash
curl -X POST http://localhost:5002/api/auth/register \
     -H "Content-Type: application/json" \
     -d '{"username": "newUser", "password": "password123"}'
```

Login
```bash
curl -X POST http://localhost:5002/api/auth/login \
     -H "Content-Type: application/json" \
     -d '{"username": "newUser", "password": "password123"}'
```