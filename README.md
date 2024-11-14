# title

## installation
### Prometheus
´´´sh
sudo apt-get install prometheus
prometheus --version
sudo ufw allow 9090/tcp
sudo systemctl enable prometheus
sudo systemctl start prometheus
sudo systemctl status prometheus
´´´

### Grafana
