# docker-compose-BGPGuard

#### Just a docker-compose structure for BGPGuard ([https://github.com/zhida-li/BGPGuard](https://github.com/zhida-li/BGPGuard))

##### **Please follow the instructions:**

1. Install Docker, instructions available: [https://docs.docker.com/engine/install/](https://docs.docker.com/engine/install/)

2. Clone this repository
```
     git clone https://github.com/luizsoliveira/docker-compose-BGPGuard
     cd docker-compose-BGPGuard
```

3. Inside the **app** folder, clone the BGPGuard repository
```
    git clone https://github.com/zhida-li/BGPGuard app/BGPGuard

```
4. Inside the **main docker-compose project** folder, start docker-compose using the following command:
```
     docker-compose up
```
5. Open your browser at the following URL: [http://localhost:5000](http://localhost:5000)
6. Have fun and good research!

##### **In case of some changes to the BGPGuard code, please follow the instructions:**

1. Inside the **main docker-compose project** folder, stop (if is started), build the bgpguard-python-dev image and start the container again by running the following commands:
```
     docker-compose down
     docker-compose build
     docker-compose up
```