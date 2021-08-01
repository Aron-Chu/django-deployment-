# django-containerization-
Utilized both dockerfile and docker-compose to containerize a Django application from Corey Schafers Django tutorial. 

## Overview
- When executed, the Django application would be containerized using docker-compose.

## Prerequisites
This application requires the following items (May be installed automatically)
- Python 3 
- Pip

## Deployment
- Change directory into the infrastructure folder
     ```
     cd infrastructure
     ```
- Change directory into the dev1 folder
     ```
     cd dev1
     ```
- Then to deploy the container, use this command
     ```
     docker-compose up
     ```
- To view the site when using a virtual Linux machine, get the IP address
     ```
     sudo apt install net-tools
     ifconfig
     inet (ipaddress)
     ```

Now enter (ipaddress):8000 to view the Django blog site.
