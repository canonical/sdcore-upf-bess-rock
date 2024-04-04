CONTRIBUTING.md # Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-upf-bess_1.4.0_amd64.rock docker-daemon:sdcore-upf-bess:1.4.0
docker run sdcore-upf-bess:1.4.0
```
