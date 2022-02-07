# Docker-dev

there are two types of volumes:

1. first type is to persist and share data between containers.
2. second type lets you share folders between the host and the container:

      * you can mount a local directory on your computer as a volume inside the container.
      
      * command to mount: -v \<full-path-local-directory>:\<full-path-inside-container>
  
      * ex: docker run -p 80:80 -v /Users/test-akun/Desktop/docker/src/:/var/www/html/ hello-world
      
      
