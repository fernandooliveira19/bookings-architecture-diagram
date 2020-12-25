# Docker container architecture

This diagram contains whole architecture docker containers used to Booking Project. 

![Docker containers](https://github.com/fernandooliveira19/bookings-architecture-diagram/blob/main/booking-ms-architecture.png)

## Order of execution of the microservices

* 1 - bkn-config-server
* 2 - bkn-eureka-server
* 3 - bkn-api-gateway-zuul
* 4 - bkn-oauth
* others

## Docker commands

* Create network

$ docker network create bkn-net
