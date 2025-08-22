[![cicd demo](https://github.com/anups07/Github_action/actions/workflows/cicd.yml/badge.svg)](https://github.com/anups07/Github_action/actions/workflows/cicd.yml)

CICD_DEMO workflow output:

```
ubuntu@ip-172-31-36-132:~$ docker ps
CONTAINER ID   IMAGE                           COMMAND                  CREATED         STATUS         PORTS                                     NAMES
455347935ee6   anups07/demo-node-app:6de38dc   "docker-entrypoint.s…"   6 minutes ago   Up 6 minutes   0.0.0.0:80->3000/tcp, [::]:80->3000/tcp   demo-node-app-api

ubuntu@ip-172-31-36-132:~$ curl http://54.158.109.127
Hello World!
```
<img width="911" height="290" alt="image" src="https://github.com/user-attachments/assets/1f65f8a3-e702-4fbd-9fcb-1e67cfc3705b" />
