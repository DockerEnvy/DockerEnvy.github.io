##DockerEnvy.github.io
====================

##Useful Docks, Configs, and Info

####Currently useful Repos include:


ubuntu

deadflowers/docker-wordpress-nginx   ( sql inside/self contained)

ansible/centos7-ansible              
        
dorowu/ubuntu-desktop-lxde-vnc       

abe78/dockerhub-demo                 

by centurylink
appcontainers/wordpress (mysql removed/separate container like totum stack)

eugeneware/docker-wordpress-nginx (same as deadflowers)

totum/wordpress (w/mysql)

totum/mysql + totum/wordpress


##google/cadvisor container mgmt stats

```
sudo docker run \
  --volume=/:/rootfs:ro \
  --volume=/var/run:/var/run:rw \
  --volume=/sys:/sys:ro \
  --volume=/var/lib/docker/:/var/lib/docker:ro \
  --publish=8080:8080 \
  --detach=true \
  --name=cadvisor \
  google/cadvisor:latest
```

##Other Resources
http://linoxide.com/linux-how-to/install-wordpress-nginx-docker-container/

piwiki?

adjenti?

dokku?



