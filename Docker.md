```bash
docker help
```

```bash
docker container ls
```
list all open containers

```bash
docker container ls -l
```
list all containers even closed ones

```bash
docker container ls --help
```
get all the commands that can be used with ls

```bash
docker container stop <container id> | <container name
```
stop the container

```bash
docker container start <container id> | <container name>
```
start the container

```bash
docker container rm <container id> | <container name>
```

```bash
docker pull nginx
```
to pull an instance (in this case nginx)

```bash
docker container run -p 8081:80 nginx
```
to make a nginx container with a port number 8081:80

```bash
docker container run -d -p 8080:80 --name nginx-con nginx
```
to name the container nginx-con

