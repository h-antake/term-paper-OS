# term-paper-OS
## Introduction - Docker
  #### Docker is an open platform for developing, installing, and running applications. You may divide your apps from your infrastructure using Docker, which speeds up software delivery. You can use Docker to manage your infrastructure in the same ways that you do to your applications. You may significantly shorten the time between developing code and having it run in production by using the Docker's methodology for shipping, testing, and deploying code quickly.
  #### Docker provides the ability to package and run an application in a loosely isolated environment called a container. The isolation and security allows you to run many containers simultaneously on a given host.
  #### Docker provides tooling and a platform to manage the lifecycle of your containers :
  
* Develop your application and its supporting components using containers.
* The container becomes the unit for distributing and testing your application.
* When you’re ready, deploy your application into your production environment, as a container or an orchestrated service. This works the same whether your production environment is a local data center, a cloud provider, or a hybrid of the two.

## Required Installation Steps and Procedures 
  #### Install interactively
1. Download Docker on your computer. https://docs.docker.com/desktop/
2. Double-click Docker Desktop Installer.exe to run the installer.
3. When prompted, ensure the Use WSL 2 instead of Hyper-V option on the Configuration page is selected or not depending on your choice of backend.
4. Follow the instructions on the installation wizard to authorize the installer and proceed with the install.
5. When the installation is successful, click Close to complete the installation process.
    
  #### Install from command line
  ##### After downloading Docker Desktop Installer.exe, run the following command in a terminal to install Docker Desktop:
    "Docker Desktop Installer.exe" install
  ##### If you’re using PowerShell you should run it as:
    Start-Process '.\win\build\Docker Desktop Installer.exe' -Wait install
  ##### If using the Windows Command Prompt:
    start /w "" "Docker Desktop Installer.exe" install
  ##### Setting and Testing if Docker is Running


 ## Example of Codes and Commands
  #### To list running containers
    $ docker container ls
![command1](https://user-images.githubusercontent.com/107777951/174487173-2a35ec0d-42fc-4ec2-a883-54fc041ce53b.JPG)
  #### To pull down images
    $ docker pull [IMAGE]
![command2](https://user-images.githubusercontent.com/107777951/174487428-b8b0cc4d-09c8-44aa-93df-567a14dccf84.JPG)
  #### To show docker version info
    $ docker version
![Test1](https://user-images.githubusercontent.com/107777951/174486976-406ebdfe-8439-4fa0-9eb7-15de92361b94.JPG)
 
