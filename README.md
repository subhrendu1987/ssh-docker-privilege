# ssh-docker-privilege

## Build docker
`sudo docker build -t ssh_privileged .`

## Run docker
`docker run -d --privileged -p 2222:22 --name sshP ssh_privileged`
