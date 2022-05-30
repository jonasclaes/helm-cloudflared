# Cloudflare Helm Chart
This chart makes it easy to deploy an instance (or multiple instances) of `cloudflared`.  

## Table of contents
- [Cloudflare Helm Chart](#cloudflare-helm-chart)
  - [Table of contents](#table-of-contents)
  - [Usage](#usage)
  - [To do](#to-do)
  - [Author](#author)

## Usage
This is a usage example based on the cloning of this repo.
```bash
helm install cloudflared cloudflared --values cloudflared/values.yaml --set token=<your tunnel token>
```

## To do
- [ ] Publish this chart for ease of use

## Author
Jonas Claes <[jonas@jonasclaes.be](mailto:jonas@jonasclaes.be)>