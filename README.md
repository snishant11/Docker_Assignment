# Docker_Assignment


# Task-1. 15 Docker command with explanation

   1.docker pull <image-name>    
     Explanation- This command is use to Pull the specified image from dockerhub
   ![dockerpull](https://user-images.githubusercontent.com/29401813/196509332-7a72eb23-6088-458c-80f6-45ec9386c215.JPG)

   2. docker build -t .
     
     Explanation- This command is use to build a docker image from the Dockerfile from the current directory
     
   3. docker images
     
     Explanation- This command is use to list the images available locally
     ![dockerimages](https://user-images.githubusercontent.com/29401813/196509132-67f8ee4c-61b8-4f44-99b4-7d81df2083fc.JPG)

   4. docker run <image-name>
     
     Explanation- This command is use to run the image as a container
     ![runhello-world](https://user-images.githubusercontent.com/29401813/196509211-316a8174-6a4f-42df-9061-94738cb3d00d.JPG)

   5. docker ps
     
     Explanation- This command is use to list all the running containers
     
   6. docker start
     
     Explanation- This command is use to start a container
     
   7. docker stop
     
     Explanation- This command is use to stop a container
     
   8. docker rmi
   
     Explanation- This command is use to delete a docker image
     
   9. docker kill
   
     Explanation- This command is use to forcefully shutdown a container
     
   10. docker tag <image-name[:tag]> <new-image-name[:new-tag]>
     
     Explanation- This command is use to rename/retag a docker image
     
   11. docker logs
     
     Explanation- This command is use to display the logs inside the running container
     
   12. docker login
     
     Explanation- This command is use to get access for pushing an image into the dockerhub
     
   13. docker push <image-name[:tag]>
   
     Explanation- This command is use to push an image into dockerhub
     
   14. docker network ls
     
     Explanation- This command is use to lists the docker networks available.
     
   15. docker exec -it bash
   
     Explanation- This command is use to gain access to a bash shell of a running container
