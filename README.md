## Instructions
- Clone the repo

  ```git clone https://github.com/thechetantalwar/node-demo```
- Change the directory

  ```cd node-demo```
- Build Docker Image
  
  ```docker build -t nodeapp -f Dockerfile .```
- Create container with `nodeapp` image and verify the application running inside it
  
 ```docker run -d nodeapp```
