LEGION
============
 Legion is an open source, easy-to-use, super-extensible and semi-automated network penetration testing tool that aids in discovery, reconnaissance and exploitation of information systems

![ ](https://briskinfosec.com//assets/tooloftheday/Tool_Of_the_day201.jpg)


Details:
============
|  Details | Description   |
| ------------ | ------------ |
|  Tool Name | LEGION |
|  Category | Network security  |
|  Purpose |  Legion is an open source, easy-to-use, super-extensible and semi-automated network penetration testing tool that aids in discovery, reconnaissance and exploitation of information systems |
|  License |    Opensource |

Demo Video:
-----------------
Click Here for [Video](https://www.youtube.com/watch?v=aotY9f06HcI  "Video")


Blog:
--------------
Click Here for [Blog](https://briskinfosec.com/tooloftheday/toolofthedaydetail/Legion-to-Discover-Reconnaissance-and-exploitation-of-infra-systems "Blog")

Installation
----------------

It is preferable to use the docker image over a traditional installation. This is because of all the dependency requirements and the complications that occur in environments which differ from a clean, non-default installation.

Installing in Docker
------------

**Linux with Local X11:**

Assumes Docker and X11 are installed and setup (including running docker commands as a non-root user)
It is critical to follow all the instructions for running as a non-root user. Skipping any of them will result in complications getting docker to communicate with the X server

**Within Terminal:**

Step 1: Download the Legion tool in to your machine by using the command below, #git clone https://github.com/GoVanguard/legion.git

Step 2: Now Navigate to the Legion folder

- cd legion/docker

Step 3: Now Navigate to the Docker folder to run legion tool in Docker mode.

Step 4: Change the Installation file in to an executable format as show below.

- chmod +x runIt.sh

Step 5: Run the installation file

- ./runIt.sh

**Linux with Remote X11:**

Assumes Docker and X11 are installed and setup

Replace X.X.X.X with the IP of the remote running X11.

**Within Terminal:**

- git clone https://github.com/GoVanguard/legion.git

- cd legion/docker

- chmod +x runIt.sh

- ./runIt.sh X.X.X.X

To Run Legion tool in Docker mode first setup Docker on Linux.

1. To install docker components typically needed and add setup the environment for docker, under a term, run:

- sudo apt-get update

- sudo apt-get install -y docker.io python-pip -y

- sudo groupadd docker

- pip install --user docker-compose


**Setup Docker to allow non-root users:**

 1. To enable non-root users to run docker commands, under a term, run:

- sudo usermod -aG docker $USER

- sudo chmod 666 /var/run/docker.sock

- sudo xhost +local:docker

**Traditional Installation**

1. Please use the docker image where possible! It's becoming very difficult to support all the various platforms and their own quirks

2. Assumes Ubuntu, Kali or Parrot Linux is being used with Python 3.6 installed.

**Within Terminal:**

- git clone https://github.com/GoVanguard/legion.git

- cd legion

- pip install –r requirements.txt

- sudo chmod +x startLegion.sh

- sudo ./startLegion.sh

Links
----------------

 ![ ](https://img.icons8.com/color/15/000000/youtube-play.png) [Briskinfosec Youtube Channel](https://www.youtube.com/channel/UCcPmqqYETcO_7-6p_uUsF1w "Briskinfosec Youtube Channel")


 ![ ](https://img.icons8.com/glyph-neue/15/000000/github.png) [Github](https://github.com/briskinfosec "Github") 

  ![ ](https://img.icons8.com/ios/15/000000/internet--v2.png) [Our Website](https://www.briskinfosec.com/ "Our Website")