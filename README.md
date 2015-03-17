# fluentd runtime

## Prepare

This image is extend from peihsinsu/fluentd, all the thing need to prepare, please reference to: https://github.com/micloud-dockers/fluentd

## Execute

```
docker run -v ~/data:/data -v ~/logs:/logs \
  -v /home/simonsu/dockerws/fluentd/td-agent:/etc/td-agent \
  -d peihsinsu/fluentd-runtime
```
