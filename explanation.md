. Dockerfile directives used in the creation and running of each container.
Built the containers using the respective client & backend folders, specified
same network on both containers and placed them on different ports.

2. Docker-compose Networking (Application port allocation and a bridge network implementation) where necessary.
I placed both containers on same network but on different ports so that they can shared data.

3. Successful running of the applications and if not, debugging measures applied.
The Application compiled Successfuly.

4. Good practices such as Docker image tag naming standards for ease of identification of images and containers. 
named the images according to their services plus the application name(yolo);
e.g 
* yoloapi - for backend servises
* yoloweb - for client services
* mongo - for mongodb

5. Docker-compose volume definition and usage (where necessary).