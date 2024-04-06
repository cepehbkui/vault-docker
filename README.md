# vault-docker
Install vault in docker with saving settings in directory\
To create image

    docker build -t minvault . 

after start containers , execute the following commands inside the container

    vault operator init
    
save seal keys and root token
