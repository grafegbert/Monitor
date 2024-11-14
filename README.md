# Installation von Monitoring

## installation
### Prometheus
```sh
sudo apt-get install prometheus
prometheus --version
sudo ufw allow 9090/tcp
sudo systemctl enable prometheus
sudo systemctl start prometheus
sudo systemctl status prometheus
```

### Grafana
```sh
sudo apt-get install grafana
sudo /bin/systemctl enable grafana-server
sudo /bin/systemctl start grafana-server
ss -tulpen
```
open grafana: http://localhost:3000/
