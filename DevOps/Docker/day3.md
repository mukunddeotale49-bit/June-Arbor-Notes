```
docker --version 
   14  docker ps
   15  docker ps -a
   16  docker network ls
   17  docker run -d -P --name cont1 nginx 
   18  docker ps
   19  docker inspect 2d6721d0d6db
   20  docker network ls
   21  ls
   22  docker ps
   23  ls
   24  docker run -d --network host nginx 
   25  docker ps
   26  curl localhost 
   27  docker ps
   28  docker inspect cbccd1987f1a
   29  ls
   30  docker run -d --network host nginx 
   31  docker ps
   32  docker ps -a
   33  ls
   34  docker ps
   35  docker run -d --network none nginx 
   36  docker ps
   37  docker inspect 50f9a82487be
   38  ls
   39  docker network ls
   40  ls
   41  docker ps
   42  docker inspect 2d6721d0d6db
   43  ls
   44  docker network create --subnet "10.0.0.0" 
   45  docker network create new-net --subnet "10.0.0.0" 
   46  docker network ls
   47  docker network create new-net --subnet "10.0.0.0/20" 
   48  docker network ls
   49  docker run -d -P --network new-net --name new-net-cont1 nginx 
   50  docker ps
   51  docker inspect 90fd4d27728a 
   52  docker run -d -P --network new-net --name new-net-cont2 nginx 
   53  docker ps
   54  docker inspect 81f56470a17f
   55  ls
   56  docker ps
   57  docker exec -it 90fd4d27728a bash 
   58  docker ps
   59  docker exec -it 81f56470a17f bash 
   60  docker exec -it 90fd4d27728a bash
```

