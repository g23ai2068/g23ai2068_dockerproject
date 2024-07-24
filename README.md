# g23ai2068_dockerproject

<b> STEPS FOLLOWED TO CREATE THIS PROJECT: </b>

1. Downloaded and installed Docker Desktop application from internet
2. Launched Visual Studio Code and connected to project folder
3. Inside project folder created an empty Docker file and source path
4. Opened the empty Dockerfile and connected to 'nginx' using FROM command
5. Provided the source path which contained my application (Refer: Dockerfile from repository)
6. Saved and closed Visual Studio Code and launched Terminal in MacOS
7. Checked the Docker Information using 'docker info' command
8. Changed directory in terminal containing Dockerfile using cd
9. Checked the Dockerfile using commend 'cat Dockerfile'
10. Created the Docker Image from scratch using command 'docker build.'
11. Verified the Docker Image was created successfully using command 'docker images' which lists all existing images
12. Added a new tag to Docker Image using command 'docker build -t g23ai2068 .'
13. Using 'docker run -d -p port:port <docker_image_id>' command executed the docker image in a new container
14. Checked currently running docker using 'docker ps'
15. Stopped the Docker Container using command 'docker stop'



APPLICATION DESCRIPTION:

'calculator.html' is a simple JavaScript application that performs arithmatic calculations.



AUTHOR DETAILS:

NAME: SHREYASH RAMOJWAR
ROLL NO.: G23AI2068
