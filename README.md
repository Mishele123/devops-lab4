## Deployment:
sudo cp files/lab4-service.service /etc/systemd/system/
sudo cp files/service.sh /opt/lab4-service/
sudo systemctl daemon-reload
sudo systemctl enable --now lab4-service
