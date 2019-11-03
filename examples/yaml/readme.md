#### Start your `reverse-proxy` with the following command:

```
docker-compose up -d reverse-proxy
```
#### Results

```
http://yourdomainorip:80 gives "404 page not found"

http://yourdomainorip:8080 gives you Traefik Dashboard
```
