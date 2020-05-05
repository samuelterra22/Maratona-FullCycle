# 02 - Microsserviço Live Manager e Comunicação

Comunicação entre serviços

- Websockets
- Pub/Sub
- WebRTC
- Filas utilizando RabbitMQ
- gRPC

Fluxo de comunicação entre Live manager e Streaming

Live Manager
- Aplicação backend
    - Nest.js
    - API REST
    - Websocket Server
    - MySql
    - Redis

- Aplicação Frontend
    - SPA (Single Page Application)
    - React
    - Material UI


Streaming
- SPA
- React
- Material UI
- HTTP Request
- Client Websocket
- WebRTC

Fluxo de comunicação entre Live manager e Chat

Live Manager
- Aplicação backend
    - Nest.js
    - gRPC
    
Chat
- Aplicação backend
    - Nest.js
    - gRPC
    - Redis
    
    
Fluxo de comunicação entre Streaming e Chat

Streaming
- Aplicação frontend
    - SPA
    - React
    - Websocket
    
Chat
- Aplicação backend
    - Nest.js
    - Wensocket server
    - MySql
    - RabbitMQ

Fluxo de comunicação entre Streaming e CodeBot

Streaming
- Aplicação frontend
    - SPA
    - gRPC
    
CodeBot
- Aplicação backend
    - Go Lang
    - gRPC
    - Postgress
