# docker setup  
sudo bash -c "$(curl -LSsq https://get.docker.com)"  
sudo usermod -aG docker ${USER:-$(whoami)}  
  
# docker containers  
  
docker pull node  
docker pull mongo  
docker pull ghost  
docker pull nginx  
docker pull lakruzz/jekyll-plus
  
