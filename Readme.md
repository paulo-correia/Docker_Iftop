# Iftop on Docker (Alpine Linux Image)

## Save Dockerfile on a folder Ex: Iftop
**Caution: Only one dockerfile per folder**

### Generate image

docker build -t `<name>` .

`<name>` = Ex: apache or your_docker_hub_name/iftop:1.0

### Running Container

docker run -it `<name>` /bin/sh

### If don't generate image, get from docker hub

docker run -it paulocorreia/alpine_iftop:1.0 /bin/sh

### Testing

inside your container type iftop