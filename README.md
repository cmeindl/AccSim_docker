# AccSim_docker
Docker file to Run account Simulator

Runs on port 9000
:9000/*   - Get full array
:9000/ - get next item in array

```
sudo docker build -t "accsim" .

sudo docker run -p 9000:9000 accsim
```

