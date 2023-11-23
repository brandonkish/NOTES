# Linux Cheat Sheet  

## **Programs**

| Description | Commands |
| --- | --- |
|Install VIM| `apt-get update` <br> `apt-get install vim`



## **Directories**

| Description | Commands |
| --- | --- |
| Change Directory  | `cd <folderpath>`|
| Remove Directory  | `rm <name>` |
| Make Directory | `mkdir <name>` |
 
## **Docker**
| Description | Commands |
| --- | --- |
| Start Docker YML  | In the folder of the yml -> `docker-compose up` |
| Fetch docker image from docker registry | `docker pull <name of docker>` | 
| See all docker images on system  | `docker images` |
| Show all running dockers  | `docker ps` |
| Show all docker networks up  | `docker network ls` |
| Enter a docker container  | `docker exec -it <container ID> /bin/sh` <br> `docker -it <container ID> bash`|
| Get docker container IP  | in docker container -> `ifconfig` |
| ???  | `docker volume ls` |
| ???  | `docker network inspect` |
| Exit docker container  | `exit` |
| Stop docker container  | `docker stop <containerid>` |
| Delete container  | `docker rm <containerid>` |
 

## **Files**

| Description | Commands |
| --- | --- |
| View File | `cat <name>` |
| Change Permissions | `chmod a+x <name>` |
| List files and show permissions  | `ls -i` |

## **Python**
| Description | Commands |
| --- | --- |
| Run script | `python3 <name>` |
  

## **VIM Editor**
| Description | Commands |
| --- | --- |
| Create new python file  |  `vi <name>` |
| Open python script  |  `vi <name>` |
| Enter Command Mode  |  i key |
| Save and exit   |  Esc Key -> `:wq` |
| Exit without saving  |  Esc Key -> `:q`  |
| Use tabs Instead Of Spaces| Inside of VIM in command mode > `:set softtabstop=0 noexpandtab` |
| Use Spaces Instead Of Tabs| Inside of VIM in command mode > `:set shiftwidth=4 smarttab` |

## **User Commands**
| Description | Commands |
| --- | --- |
| Change User   |  `su <username>` |
| Run command as admin  |  `sudo <command>` |
| Change Sudo password   |  `sudo passwd root`   |
