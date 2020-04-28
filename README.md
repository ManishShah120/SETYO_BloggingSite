# SETYO_BloggingSite = Set Up Your Own _BlogingSite
With this repo you can Automatically:-
1. Pull images from [DockerHub](https://hub.docker.com/)
2. Create Docker volumes for permanent use.
3. Set Up MySQl Database.
4. Set up WordPress site.

## Built with
- Linux
- Docker
- Worpress
- MYSQl

## Requirements/Installation
Make sure you have the latest versions of **Docker** and **Docker Compose** installed on your machine.
##### If Not than run the following commands:-
For Docker installation on linux[Ubuntu Distro/Similar commands for other distro as well]
```
sudo apt-get update
sudo apt-get remove docker docker-engine docker.io
sudo apt install docker.io
```
After Docker installation Now install Docker Compose:-
```
sudo curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```
After installation of the above files:-
```
sudo systemctl start docker
sudo systemctl enable docker
```

## Usage

Open a terminal and `cd` to the folder in which `docker-compose.yml` is saved and run:-

```
docker-compose up
```
Hola!, Everything is Set now the containers are now built and running. You should be able to access the WordPress installation with the configured IP in the browser address by `http://192.168.xx.xx:8081`.[Change it accordingly]
## Here is an instance of my Blog site which I built using this repo:- 
[img](address Url's)
### Fore more reference on docker-compose

Start the containers with the `up` command in daemon mode (by adding `-d` as an argument) or by using the `start` command:

```
docker-compose start
```

### Stopping containers

```
docker-compose stop
```


## Authors
[**Manish Kumar Shah**](https://github.com/ManishShah120)

# License
[MIT](https://github.com/ManishShah120/SETYO_BloggingSite/blob/master/LICENSE)

# About
This is a simple project built with docker to setup an worpress building environment on any system
