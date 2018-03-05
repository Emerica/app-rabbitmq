# app-rabbitmq
Entermedia RabbitMq Transcoder


-Find out how to complie this along side, or just get it merged?

-Preset when configuring

![Config](https://i.imgur.com/gluMLGj.png)


-queue

-ip

-port

-vhost

-username

-password


Output to Rabbit is a json string with the absolute path of the input and output, as well as the asset id.
The worker that acknowledges the job should update the status of the conversion.
