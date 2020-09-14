Run below commands:

`kubectl deploy -f spring-music-deploy.yaml`

`kubectl deploy -f spring-music-ingress.yaml`

`kubectl deploy -f mysql-deploy.yaml`

Test MySQL Connectivity
`kubectl run -it --rm --image=mysql:5.6 --restart=Never mysql-client -- mysql -h mysql -pPassw0rd`
