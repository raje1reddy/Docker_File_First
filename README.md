# Docker_File_First
Initial docker file
sudo docker build -t padmaja_hello_world .
sudo docker run padmaja_hello_world
  
 
   sudo docker ps -a
  
  223  pwd
  
  
  224  sudo docker run -p 8000:80 padmaja_hello_world
  
  
  225  sudo docker run -p 8000:80 -v /home/preddy/docker_example_PHP/src/:/var/www/html padmaja_hello_world
  
 code .
  
  
