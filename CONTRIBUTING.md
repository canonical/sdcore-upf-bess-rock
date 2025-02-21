# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-upf-bess_2.0.1_amd64.rock docker-daemon:sdcore-upf-bess:2.0.1
docker run sdcore-upf-bess:2.0.1
```
