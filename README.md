# Deploy_Real_Chat_App



Follow below steps to deploy application with Docker
Step1:
  - Clone my code with

        git clone https://github.com/Thanhlam43k4/Deploy_Real_Chat_App.git

Step2:
  -Download DockerDesktop to your local computer

        https://docs.docker.com/get-docker/

Step3:
  -Build Docker Image with Dockerfile
  
        docker build -t <image_name> .

Step4:
  -Build Docker Container 

         docker run -dp 127.0.0.1:3700:3700 <image_name>

Step5:
  -To use application you search to 
  
        http://localhost:3700/
>>>And deploy your website succesffully!!!!
        
Deploy application with Docker
