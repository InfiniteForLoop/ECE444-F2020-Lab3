## ECE444-F2020-Lab3

# How to build and start system:

Download/Install Docker
Clone this repo and use "lab4_Microservice_Experiment" branch
Build image run: docker build -t flask-sample .
Run container: docker run -it --name flask-sample --rm -p 5000:5000 flask-sample
Go to http://localhost:5000/ on your preferred browser
