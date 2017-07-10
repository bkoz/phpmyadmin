# Deploying phpmyadmin into OpenShift

```
oc new-app mysql-emperheral -e MYSQL_USER=admin -e MYSQL_PASSWORD=daSqkbf6hA2We5sy -e MYSQL_ROOT_PASSWORD=imgddHiuWhiDd1ft 

oc new-app docker.io/phpmyadmin/phpmyadmin -e MYSQL_USER=admin -e MYSQL_PASSWORD=daSqkbf6hA2We5sy -e MYSQL_ROOT_PASSWORD=imgddHiuWhiDd1ft -e PMA_HOST=mysql
```
