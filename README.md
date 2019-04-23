# mean-docker-sample
Application build using the MEAN stack and Docker <br/> <br/>
<b>To Run image:</b> docker run -p 4200:4200 -v absolutePathOnHost:pathOnContainer -itd joshnano/angular-simple:x.x.x 

<b>Example</b>: docker run -p 4200:4200 -v c:/users/joshwerner.exchange/desktop/docker_shared:/mnt/docker_shared -itd joshnano/angular-simple:1.0.85


<b>**Note</b>
-d - detached mode: docker will run in the background
-p - port: sets port mapping
-it - interactive mode: can execute commands in container
  -i: interactive keeps standard input open
  -t: allocates a terminal
-v - volume: creates shareable volume. Can also create shareable volumes between containers
