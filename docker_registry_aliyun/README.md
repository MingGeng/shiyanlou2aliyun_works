## put daemon.json into /etc/docker and restart docker
cat daemon.json | sudo tee  /etc/docker/daemon.json
