# Docker Volume Using --mount (mydata)

This task demonstrates how to create a Docker volume and use the `--mount` option to persist and share data across containers.

## Objective
- Create a Docker volume named `mydata`
- Mount the volume inside an Ubuntu container
- Write data to the volume
- Access the same data from another container

## Steps Performed

A Docker volume named `mydata` is created and mounted at `/app/data` inside an Ubuntu container.  
A file is written to the mounted directory and then accessed from a second container using the same volume.

## Output Verification
The content written in the first container is successfully read in the second container, proving data persistence.

## Conclusion
Docker volumes created using the `--mount` option allow data to persist beyond container lifecycles and enable data sharing between containers.

## Author
Aryan Choudhary  
B.Tech CSE – Lovely Professional University
