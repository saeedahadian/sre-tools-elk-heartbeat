# Heartbeat

Heartbeat is a lightweight daemon from the elastic stack which is used to check the status of your services, uptime and response time of the services your server uses. Unlike Metricbeat, which only tells you if your servers are up or down, Heartbeat tells you whether your services are reachable.

## Monitors

There are 3 different types of monitors in heartbeat that you can use to check if a service is responsive:

ICMP
: This checks whether you can ping a specific address.

TCP
: With this you can check reachability of a service on a specific port.

HTTP
: This option gives you more control on what kind of responses shows the availability of a service.

Each of these monitors could be configured in their respective directories below `configs`.

## Usage

In order to set environment variables you can use .env.sample file in the repository, or in case you use the fish shell you can use .env.fish.sample:

`cp .env.sample .env`

or in case of fish shell:

`cp .env.fish.sample .env`
