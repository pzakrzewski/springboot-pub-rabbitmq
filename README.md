1. Setup RabbitMq with Docker<br/>
Here are docker images for RabbitMq: https://hub.docker.com/_/rabbitmq
2. Select one of them and run container<br/>
docker run -d --hostname my-rabbit --name some-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management
3. Important links:<br/>
-RabbitMq Management: http://localhost:15672/#/<br/>
-Add message to queue: http://localhost:8080/addMessage?message=test
4. Run together with https://github.com/pzakrzewski/springboot-client-rabbitmq/
