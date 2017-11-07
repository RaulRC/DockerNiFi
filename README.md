# DockerNiFi
Info on this repo go to https://community.hortonworks.com/articles/69043/launching-a-nifi-docker-instance.html

# Updates RaulRC

* NiFi version: 1.3.0
* Mirror: http://apache.rediris.es
* Last update: 2017-08-23

```{r, engine='bash', count_lines}
#Docker Build
docker build -t rreguillo/nifi:<tag> .

#Docker Run
docker run -d -p 9090-9091:8080-8081 rreguillo/nifi:<tag>
```

## BEEVA PoC

* Slides
* Script
* Different PoC Topologies

## BEEVA Course

* Slides
* Minimal PoC