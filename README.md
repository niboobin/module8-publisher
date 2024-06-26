## How many data your publisher program will send to the message broker in one run?

The publisher program will send 5 messages to the message broker in one run.\

## The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

The URL "amqp://guest:guest@localhost:5672" is the connection string to the message broker.

## Running RabbitMQ

![RabbitMQ](https://cdn.discordapp.com/attachments/314315831465213953/1232355746163986432/image.png?ex=66292839&is=6627d6b9&hm=836d6ad31a44a22ce4656e25de911d2017c3f9474d19e30f607c2ed6b7e965d8&)

## Sending and processing event

By running `cargo run` on the publisher app, it sends out 5 events to the broker. Those events are processed by the subscriber.

![Event](https://cdn.discordapp.com/attachments/314315831465213953/1232364691305791508/image.png?ex=6629308e&is=6627df0e&hm=47be450d0541a30b95859acf1dfdc40968657c98f4d8abc9cdf263ef5e1ebd7c&)

## Monitoring chart based on publisher

A spike in the monitoring chart represents a sudden increase in the number of messages being published to the broker.

![Chart](https://cdn.discordapp.com/attachments/314315831465213953/1232366717284384860/image.png?ex=66293271&is=6627e0f1&hm=505b5ee15d858c653227bcb11a9fe1832db01665a4afcd3f53d018ad5b9104f8&)
