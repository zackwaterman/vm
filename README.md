# vm
```
docker run --rm -d -p 3443:80 -v $PWD:/workspace:rw -e USER=username -e PASSWORD=password -e RESOLUTION=1366x650 --name ubuntu-novnc4 fredblgr/ubuntu-novnc:20.04
```
