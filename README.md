# 11nanban
docker file for 11-produce with nanban

# How to use
docker rmi 11nanban  
git clone git@github.com:ubukawa/11nanban  
cd 11nanban  
docker build -t 11nanban .  
docker run -it --rm -v ${PWD}:/data 11nanban  
 
cd 11-produce  
vi config/default.hjson  
mkdir /data/xxx   //mbtilesDir

rake
