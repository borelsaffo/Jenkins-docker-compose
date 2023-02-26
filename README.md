# Jenkins-docker-compose
Deploy Jenkins with Docker-compose

pré-requis : 

# install docker 
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh

#  Install docker-compose : 
apt-get install docker-compose

on y'r VM : 

mkdir install-folder
cd install-forlder
git clone https://github.com/borelsaffo/Jenkins-docker-compose.git
docker-compose up -d
docker-compose ps
docker-compose logs

accès via GUI
