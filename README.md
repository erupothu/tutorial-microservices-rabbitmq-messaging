# tutorial-microservices-rabbitmq-messaging

Installing RabbitMQ server on Ubuntu follow install-rabbitmq.txt file <br>

In browser <br>
http://localhost:15672/ <br>

int terminal <br>
> curl -X POST --data '{"id": 1, "name": "message4 to topic1"}' -H "Content-Type:application/json" http://localhost:9192/publish <br>

or we can publish from postman or RabbitMQ UI <br>

check LOG in spring-cloud-stream-consumer service <br>
