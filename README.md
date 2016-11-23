# project1_docker
Hosting website (HW 1,2,3) on docker container, automates the deployment of Linux applications inside software containers. 


# Dynamic-web-page
This web service provides the user with   1.Lucas series,   2.Fibonacci series,   3.Factorial of a number after user gives the input integer. 

you can get compressed Docker image from google drive using below link

https://drive.google.com/file/d/0B_zgqOd7NHNPYmdqMUFYNlVsOWc/view?usp=sharing

you can load my docker image using the below command

docker load -i lucas.tar.gz

you can run my docker image using the below command

docker run -d -p 8081:80 docker.io/aletiny/docker_project /startme.sh   or

docker run -d -p 8081:80  dbaf10d30693  /startme.sh 


