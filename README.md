# Events Menagment App
Events menagment app utilizing microservice architecture made using React and TypeScript for frontend, Spring Boot and Clojure for backend, and RabbitMQ for asynchronous communication. The project is focused on manual implementation of distributed system patterns including Circuit Breaker, Retry, Timeout, Transactional Outbox, Request-Response and Dead Letter Queue.

## Running project

```
git clone https://github.com/lalkee/events-app-microservice-architecture.git events-app
```
```
cd events-app
```
```
docker compose up --build
```
App will be avaliable on http://localhost:5173 