# Docker Volume Demonstration – studentdata

This project demonstrates the use of Docker volumes to show data persistence and data sharing between containers.

## Objective
- Create a Docker volume named `studentdata`
- Mount the volume inside multiple containers
- Write data from one container
- Read the same data from another container
- Prove that deleting containers does not delete volume data

## Description
A Docker volume named `studentdata` is created using the local volume driver.  
This volume is mounted at `/student` inside multiple Ubuntu containers.  
Data written by one container is successfully accessed by another container, even after container deletion, proving persistence.

## Observations
- Data written inside the volume remains available after container removal
- Multiple containers can share the same volume
- Docker volumes store data outside the container lifecycle

## Conclusion
Docker volumes provide persistent storage and enable data sharing between containers.  
They are essential for applications requiring reliable data storage such as databases and logs.

## Author
Aryan Choudhary  
B.Tech CSE – Lovely Professional University
