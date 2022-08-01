# docker setup  

```shell
sudo bash -c "$(curl -LSsq https://get.docker.com)"  
sudo usermod -aG docker ${USER:-$(whoami)}  
```  

# docker containers  

```shell
docker pull node  
docker pull mongo  
docker pull ghost  
docker pull nginx  
docker pull lakruzz/jekyll-plus
```  
