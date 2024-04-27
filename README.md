# Install Prometheus
- mkdir prometheus
- cd prometheus
- wget <link_tar_file> # https://prometheus.io/download/
- create prometheus.yml
- ./prometheus

# Setup prometheus
- Create prometheus.service file
- systemctl daemon-reload # reboot systemctl daemon
- systemctl start prometheus
- systemctl status prometheus

https://www.youtube.com/watch?v=7Nnzu3IK6kE
