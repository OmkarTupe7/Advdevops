```
sudo apt upgrade
```
```
sudo apt update
```
```
sudo apt-get install openjdk-11-jdk
```

Install Docker:

```
sudo apt update
```
```
sudo apt-get install docker.io
```


Install SonarQube on Docker:

```sudo su
```


```
sysctl -w vm.max_map_count=524288
```
```
sysctl -w fs.file-max=131072
```
```
ulimit -n 131072
```
```
ulimit -u 8192
```

```
docker run -d --name sonarqube -p 9000:9000 sonarqube
```
