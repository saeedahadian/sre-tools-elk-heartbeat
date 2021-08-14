# Heartbeat

Heartbeat is a lightweight daemon from the elastic stack which is used to check the status of your services, uptime and response time of the services your server uses. Unlike Metricbeat, which only tells you if your servers are up or down, Heartbeat tells you whether your services are reachable.

## Setting up Heartbeat

> Todo: what permissions and chmod and chown command are needed to perform correctly

### Set your services

You can set what services you want to be monitored via Heartbeat in configs/heartbeat.docker.yml;
There are 3 protocols that are supported by heartbeat: 1-TCP, 2-ICMP, and 3-HTTP