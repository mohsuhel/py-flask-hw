# Py-Flask-Helloworld
# steps involved to run python -flask to print the "hello world"

# 1. Go to Aws console and Launch the EC2 Server (server-1/ubuntu22.04 LTS)
![1](https://github.com/mohsuhel/py-flask-hw/assets/127845338/1be97a43-3ca0-491f-bede-1588abaab252)

# 2. Install the python on ec2 server 
- sudo apt update
- sudo apt install python3 (or) sudo apt install python3-pip
![2](https://github.com/mohsuhel/py-flask-hw/assets/127845338/77facdac-52c3-4292-9b05-bdef1047360e)

# 3. Installation Docker
- sudo apt update
- sudo apt install docker.io
  ![3](https://github.com/mohsuhel/py-flask-hw/assets/127845338/dd512d69-70dd-4ac4-967b-555889a21614)

  # create a account on DockerHub and login in the instance
  ![4](https://github.com/mohsuhel/py-flask-hw/assets/127845338/e54e2023-2526-42e4-896c-d98d1ef294d4)

  # using docker to build the image of flask application
  ![55](https://github.com/mohsuhel/py-flask-hw/assets/127845338/da63f7f9-8790-4a12-b9eb-c04ed7f4090f)
  # check the image is created or not
  - sudo docker images
    ![6](https://github.com/mohsuhel/py-flask-hw/assets/127845338/b55d43b6-0ac7-40f5-8a9d-70a1e6060e91)

  # run the image into container
  - sudo docker run -itd -p portnum :portnum image-name
  ![7](https://github.com/mohsuhel/py-flask-hw/assets/127845338/b19a087c-2ba6-4ccd-bad8-015bb97fb296)

  # check the ip address with port whether application is running or not
  ![9](https://github.com/mohsuhel/py-flask-hw/assets/127845338/d37394ee-b8c4-4d79-9a14-999a2a56f40e)

  # docker hub Image details
  docker pull mdsuh/py-hw:1.0




  

