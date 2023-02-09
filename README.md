# Play with Pyrra

This is an example with pyrra filesystem mode.

## Running the Example

To run the example docker-compose setup you need to have Docker and docker-compose installed.

```bash
docker-compose up -d
```

After all services started, you will fill 5 containers.

Pyrra is available on [localhost:9099](http://localhost:9099) and Prometheus at [localhost:9090](http://localhost:9090) and Grafana at [localhost:3000](localhost:3090)

Pyrra should show you the available SLOs on its overview page and you can click on the individual ones to see the specific SLO and all it's details.