# Task 7: Monitor System Resources Using Netdata

This task demonstrates how to use Netdata with Docker to monitor system resources like CPU, memory, disk I/O, and running containers.

##  Docker Command Used
```bash
docker run -d --name=netdata -p 19999:19999 netdata/netdata
