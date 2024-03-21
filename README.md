# ssh-docker-privilege

## Build docker
`sudo docker build -t ssh_privileged .`

## Run docker
`sudo docker run -d --privileged -p 2222:22 --name sshP ssh_privileged`

## Connect SSH from host
`sshpass "test" ssh -o "StrictHostKeyChecking no" root@127.0.0.1`


## Cleanup
`sudo docker rm -f sshP`

