# Installing Prometheus
```sh
wget https://github.com/prometheus/prometheus/releases/download/v2.20.0/prometheus-2.20.0.linux-amd64.tar.gz
tar xvfz prometheus-*.tar.gz
cd prometheus-2.20.0.linux-amd64/
```

# Configure Prometheus
```sh
vi prometheus.yml 
```

# Start Prometheus Server on default port 9090
```sh
 ./prometheus --config.file=prometheus.yml
 ```
 
# Validating installation 
You can verify that Prometheus is serving metrics about itself by navigating to its metrics endpoint: localhost:9090/metrics


# Using the expression browser - Refer to slide deck 
