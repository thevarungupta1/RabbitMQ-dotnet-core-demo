# RabbitMQ-dotnet-core-demo

To create a docker container running RabbitMQ

> docker run -d --hostname my-rabbitmq --name myrabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management


> dotnet --help

# create Producer
> dotnet new console --name Producer
> cd Producer
> mv Programe.cs Producer.cs
> dotnet add package RabbitMQ.Client
> dotnet restore
 

# create Consumer
> dotnet new console --name Consumer
> cd Consumer
> mv Programe.cs Consumer.cs
> dotnet add package RabbitMQ.Client
> dotnet restore

> code .

> dotnet run
