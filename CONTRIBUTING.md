CONTRIBUTING.md # Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-bess_1.3_amd64.rock docker-daemon:sdcore-bess:1.3
docker run sdcore-bess:1.3
```
