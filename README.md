This repository contains k8s deployment artifacts to run Spring Music application with MySQL database as backend.

Run below commands:

`kubectl apply -k .`

Test MySQL Connectivity

`kubectl run -it --rm --image=ghcr.io/mrporcles/mysql:5.6 --restart=Never mysql-client -- mysql -h mysql -pPassw0rd`
----
