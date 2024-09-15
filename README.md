# MyDockerWebApi Docker Assignment 

1. Clone the Repository
   First, clone the repository to your local machine:
     git clone https://github.com/yourusername/mywebapi.git
     cd mywebapi
2. Build and Run Using Docker Compose:
     docker-compose up --build

3. Accessing the Application
   Once the containers are running, you can access the Web API at:
   -http://localhost:5036
   -http://localhost:5282
4. Pull image from docker hub
   - docker pull nitesh4321kr/multicontainer-docker-asg:service1
   - docker pull nitesh4321kr/multicontainer-docker-asg:service2
   4.1. run images
     - docker run -d -p 5036:8080 nitesh4321kr/multicontainer-docker-asg:service1
     - docker run -d -p 5282:8080 nitesh4321kr/multicontainer-docker-asg:service2
