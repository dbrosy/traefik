##### `docker-compose.yml`
##### Start your `reverse-proxy` with the following command:
```
docker-compose -f docker-compose.yml up -d reverse-proxy
```
##### Results
```
http://yourdomainorip:80 gives "404 page not found"

http://yourdomainorip:8080 gives you Traefik Dashboard
```


##### `docker-compose-basic.yml`
##### Start your `reverse-proxy` with the following command:
```
docker-compose -f docker-compose-basic.yml  up -d reverse-proxy
```
##### Results
```
http://yourdomainorip:80 gives "404 page not found"

http://yourdomainorip:8080 gives you Traefik Dashboard
```
