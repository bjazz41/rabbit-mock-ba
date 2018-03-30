# rabbit-mock-ba
This is just the kubernetes YAML files for service and deployment.

## Service
Exposes the Rabbit HTTP API on NodePort 32000.
Logon to Rabbit "dashboard" on  this port.
User name: guest, password: guest.

Defines the AQMP port as _rabbit-amqp_.

## Deployment
Uses docker image _rabbitmq:3.6-management_.