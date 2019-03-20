# CF RabbitMQ Enterprise Proxy

This small proxy app helps you to make your RabbitMQ instance dashboard from a SAP Cloud Platform publicly available. For it to work, the app needs to be bound to your RabbitMQ service instance.

## How to use

1. Clone this repo
1. Change the `host` in `manifest.yml` to something that isn't taken yet
1. Change the entry in `services` in `manifest.yml` from `rabbitmq-ent` to the name of your RabbitMQ instance in Cloud Foundry
1. Run `cf push` 
