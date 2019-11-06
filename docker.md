# explain
모든 도커 컨테이너 삭제(remove all docker containers)
구동중인 모든 도커 컨테이너들을 중지시키고, 삭제한다.

```
    docker stop $(docker ps -a -q)
    docker rm $(docker ps -a -q)
```


모든 도커 이미지 삭제(remove all docker images)

```
    docker rmi $(docker images -q)
```

# copy
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
docker rmi $(docker images -q)