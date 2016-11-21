# docker-ubuntu14-jmeter


This dockerfile assemble ubuntu 14.04 and jmeter

Primary use case : Automation testing with jmeter


You can find this dockerfile and the corresponding docker image on hub.docker.com


### Usage
```bash
docker pull arnaudblancher/docker-ubuntu14-jmeter
docker run --name jmeter_server  -it  arnaudblancher/docker-ubuntu14-jmeter:latest /bin/bash
```
