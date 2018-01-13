# Steam Cache Docker

## Usage

To start you will probably just bind to port 80 on the machine

```
docker run --name steamcache -p 80:80 ancients/steamcache:latest
```

For more complex setups you may want to bind to a specific ip address on the host

```
docker run --name steamcache -p 192.168.1.2:80:80 ancients/steamcache:latest
```
