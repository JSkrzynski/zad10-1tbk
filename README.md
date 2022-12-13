docker swarm init  

docker image rm zad10-1tbk  
docker image build -t zad10-1tbk .  

docker service create --detach --replicas 1 lab10z1  

```
@echo off
:loop
    timeout /t 5
    docker ps -a
goto loo
```
