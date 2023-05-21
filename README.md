# TKT21036  DevOps with Docker

#1.5 Sizes of Images
step 1: sudo docker pull devopsdocheruh/simple-web-service:alpine
step 2: sudo docker images

 shohidur@CourseVM:~$ sudo docker images
 REPOSITORY                          TAG           IMAGE ID       CREATED         SIZE
 shohidur/todo/1.0                   latest        57b589e51a6f   3 days ago      262MB
 nicolargo/glances                   latest        2da760422b19   4 days ago      70.6MB
 prom/prometheus                     latest        75972a31ad25   7 days ago      234MB
 alpine                              latest        5e2b554c1c45   11 days ago     7.33MB
 mongo                               latest        8b33e239cde6   2 weeks ago     651MB
 mcr.microsoft.com/mssql/server      2022-latest   e22cb0ce9bfe   2 weeks ago     1.58GB
 ubuntu                              latest        3b418d7b466a   3 weeks ago     77.8MB
 hectormolinero/xubuntu              latest        f45eaee8ff1d   13 months ago   2.85GB
 devopsdockeruh/simple-web-service   ubuntu        4e3362e907d5   2 years ago     83MB
 devopsdockeruh/simple-web-service   alpine        fd312adc88e0   2 years ago     15.7MB
 devopsdockeruh/pull_exercise        latest        d9854bc0e13a   4 years ago     75.3MB
 gaetan/dockercraft                  latest        59e40406abda   4 years ago     183MB

step 3: sudo docker run -d -it --namer exercise1.5 devopsdockeruh/simple-web-service:alpine

step 4: sudo docker exec -it exercise1.5 sh

step:5 cat /usr/src/app/text.log
