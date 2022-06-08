# custome_image
custome image for docker container

## Builading Dockerfile
‌building Docker file on Server
```
docker image build -t ansible-ssh:1
```

## Creating Container
```
docker run --name sshd_ap -d -p 2222:22 ansible:1
```
