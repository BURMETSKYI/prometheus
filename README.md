# Install Prometheus
- mkdir prometheus
- cd prometheus
- wget <link_tar_file> # https://prometheus.io/download/
- tar xvfz prometheus-2.51.2.linux-amd64.tar.gz
- mv prometheus /usr/bin/
- create prometheus.yml
- ./prometheus

# Setup prometheus
- Create prometheus.service file
- useradd -rs /bin/false proemetheus
- chown prometheus:prometheus /usr/bin/prometheus
- chown -R prometheus:prometheus /etc/prometheus
- micro /etc/systemd/system/prometheus.srervice
  
- systemctl daemon-reload # reboot systemctl daemon
- systemctl start prometheus
- systemctl status prometheus

# How to install Prometheus server on Linux: 
https://www.youtube.com/watch?v=7Nnzu3IK6kE
