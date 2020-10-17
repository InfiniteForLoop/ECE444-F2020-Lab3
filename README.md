# ECE444-F2020-Lab3

## How to build and start system:

1. Download/Install Docker
2. Clone this repo and use "lab4_Microservice_Experiment" branch
3. Build image run: docker build -t flask-sample .
4. Run container: docker run -it --name flask-sample --rm -p 5000:5000 flask-sample
5. Go to http://localhost:5000/ on your preferred browser
