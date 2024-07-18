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

## Contributing
### Update
```bash
git pull
cd cvutchat-socket; git pull; cd ..
cd cvutchat-rest; git pull; cd ..
cd cvutchat-auth; git pull; cd ..
cd cvutchat-weather; git pull; cd ..
cd cvutchat-data; git pull; cd ..
cd cvutchat-frontend; git pull; cd ..
```