Project TeamPizzaDelivery
Members Zykia, Nhu Thao, Landon

Task: Used Docker 
1. Build a Docker Image
   docker build -t my-app .

3. Run the Docker Container
   docker run -p 3000:3000 my-app

5. Stopped the Container
docker ps
docker stop <container_id>


7. Additional Comments 
docker logs <container_id>
docker exec -it <container_id> /bin/bash
