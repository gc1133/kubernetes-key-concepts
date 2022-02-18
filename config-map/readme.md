```
k apply -f database-config.yaml
k apply -f nginx.yaml
k exec -it nginx-7c84cfb456-vxx69 sh

cd /app/config/db
ls
database.properties
cat database.properties
database.url=http://testdb:3306
database.password=Password@1234
```
