# RabbitMQ Tutorial 6: RPC

https://www.rabbitmq.com/tutorials/tutorial-six-javascript

```bash
npm install
docker run -d -p 15672:15672 -p 5672:5672 -p 5671:5671 --name rabbitmq-container rabbitmq:3
npm run server
npm run client 15
```