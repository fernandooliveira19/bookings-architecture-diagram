# Docker container architecture

This diagram contains whole architecture docker containers used to Booking Project. 

![Docker containers](https://github.com/fernandooliveira19/bookings-architecture-diagram/blob/main/booking-ms-architecture.png)

## Order of execution of the microservices

* 1 - bkn-config-server - not implemented yet
* 2 - bkn-eureka-server - https://github.com/fernandooliveira19/bkn-eureka-server
* 3 - bkn-api-gateway-zuul - https://github.com/fernandooliveira19/bkn-api-gateway-zuul
* 4 - bkn-booking - https://github.com/fernandooliveira19/bkn-booking
* 5 - bkn-user - https://github.com/fernandooliveira19/bkn-user
* 6 - bkn-web-app - https://github.com/fernandooliveira19/booking-app-starter
* 7 - bkn-mobile - not implemented yet
