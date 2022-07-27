you like this work ?

[!["You like it ?"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/sorriso)
# kube-rabbitmq-dockerhub

Kubernetes yaml configuration files for rabbitmq using docker hub image

## prerequisite:

- Rancher desktop (or equivalent) installed locally & running with "containerd" selected as main command tool

## How to make it working :

- edit "redis/redis-PersistentVolume.yaml" and update 'path: "/Users/sorriso/Documents/GitHub/kube-rabbitmq-dockerhub/volume/data"'

- run "./0-pull.sh" to pull docker image

- run "./1-start.sh" to start service

- run "./2-stop.sh" to stop service
