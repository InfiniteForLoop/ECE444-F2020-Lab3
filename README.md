# ECE444-F2020-Lab3

## How to build and start system:

1. Download/Install Docker
2. Clone this repo and use "lab4_Microservice_Experiment" branch
3. Build image run: docker build -t flask-sample .
4. Run container: docker run -it --name flask-sample --rm -p 5000:5000 flask-sample
5. Go to http://localhost:5000/ on your preferred browser


![alt text](https://github.com/InfiniteForLoop/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/activity_1_3.png)
![alt text](https://github.com/InfiniteForLoop/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/activity_2_3.png)
![alt text](https://github.com/InfiniteForLoop/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/activity_3_3.png)

## Question 3

Docker is a container. Containers are a set of processes that are isolated from the rest of the system, running from a distinct image that provides all files necessary to support the processes. It is built for running applications. In Docker, the containers running share the host OS kernel.

A Virtual Machine is made up of a user space plus kernel space of an operating system. Under VMs, server hardware is virtualized. Each VM has Operating system (OS) & apps. It shares hardware resource from the host.
