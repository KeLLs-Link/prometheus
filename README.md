# Prometheus
## **Monitoring-with-Prometheus**
- **Introduction to Prometheus Monitoring** 
- **What is prometheus**
- **Where and why is prometheus used?**
- **Prometheus architecture**
- **Example configuration**
- **Key characteristics**

## **What is prometheus?**
Prometheus is a monitoring tool that was created to monitor highly dynamic container environment- like kubenetes, docker swam, etc. It can also be used in traditional non-container (bare server) infrastructure- where you have bare servers with application deployed directly on them.

over the past years, prometheus has become the main stream monitoring tool of choice in containers and micro-service infrastructur.

## **Why use prometheus**
Modern day DevOps is becoming more and more complex to handle manually and therefore needs more automation. Typically you have multiple servers that run multiple containerised applications and there are 100's of different processes running on that infrastructure and things are interconnected.

Maintaining such setups to run smoothly without application downtime can be very challenging.
Imagine having such a complex archtecture with loads of servers distributed accross different locations and you have no insight of what is happening on hardware level or application level like;
- erros
- response latency
- hardware down
- server overload and running out of resource

![image](./screenshot/Snipaste_2024-10-04_15-01-37.jpg)

Prometheus makes searching problem more efficient through constantly 
- monitoring whether a service is running, 
- alerts maintainers when a 