# automatically start docker-registry container with systemd

```
sudo curl https://raw.githubusercontent.com/74th/systemd-docker-registry/master/install.sh | sh
sudo systemctl enable docker
sudo systemctl enable docker-registry
sudo systemctl start docker-registry
```
