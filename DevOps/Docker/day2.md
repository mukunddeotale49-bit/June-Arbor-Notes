```
docker --version                  ## docker version 
docker pull <image>
docker run <image_ID>             ## run intractivly
docker run -d <image_ID>          ## run detached
docker run -d -P <image_ID>       ## give random port
docker run -d -p 80:80 <image_ID> ## on assing port container run 
docker ps                         ## list all runnning conatainer 
docker ps -a                      ## list all state container
docker ps -aq                     ## list all container only container ID 
docker stop <cont_ID>             ## stop container
docker rm <cont_ID>               ## remove container 
docker rmi <Image_ID>             ## to remove image
docker exec -it <cont_ID> bash    ## to enter into docker container
```
<img width="453" height="266" alt="image" src="https://github.com/user-attachments/assets/66898e0a-1c49-4bfd-ae6a-ddd04332d7b2" />
