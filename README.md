# mirror-images

Public images mirrored to Amazon ECR Public (see list below).

## Configuration

To create a public ECR repository from the AWS CLI:

```sh
aws ecr-public create-repository --repository-name <repo-name>
```

## Currently mirrored

| Docker Hub                                                                                     | Amazon Public ECR |
| ---                                                                                            | ---               |
| [docker.io/grafana/loki](https://hub.docker.com/r/grafana/loki)                                | [public.ecr.aws/andreswebs/loki](https://gallery.ecr.aws/andreswebs/loki) |
| [docker.io/grafana/promtail](https://hub.docker.com/r/grafana/promtail)                        | [public.ecr.aws/andreswebs/promtail](https://gallery.ecr.aws/andreswebs/promtail) |
| [docker.io/memcached](https://hub.docker.com/_/memcached)                                      | [public.ecr.aws/andreswebs/memcached](https://gallery.ecr.aws/andreswebs/memcached) |
| [docker.io/niginxinc/nginx-unprivileged](https://hub.docker.com/r/nginxinc/nginx-unprivileged) | [public.ecr.aws/andreswebs/nginx-unprivileged](https://gallery.ecr.aws/andreswebs/nginx-unprivileged) |
| [docker.io/prom/memcached-exporter](https://hub.docker.com/r/prom/memcached-exporter)          | [public.ecr.aws/andreswebs/memcached-exporter](https://gallery.ecr.aws/andreswebs/memcached-exporter) |
| [docker.io/prom/pushgateway](https://hub.docker.com/r/prom/pushgateway)                        | [public.ecr.aws/andreswebs/pushgateway](https://gallery.ecr.aws/andreswebs/pushgateway) |
| [docker.io/amazon/aws-cli](https://hub.docker.com/r/amazon/aws-cli)                                    | [public.ecr.aws/andreswebs/aws-cli](https://gallery.ecr.aws/andreswebs/aws-cli) |
| [docker.io/jpetazzo/shpod](https://hub.docker.com/r/jpetazzo/shpod)                                    | [public.ecr.aws/andreswebs/shpod](https://gallery.ecr.aws/andreswebs/shpod) |
| [docker.io/atmoz/sftp](https://hub.docker.com/r/atmoz/sftp)                                    | [public.ecr.aws/andreswebs/sftp](https://gallery.ecr.aws/andreswebs/sftp) |
| [docker.io/ubuntu](https://hub.docker.com/_/ubuntu)                                    | [public.ecr.aws/andreswebs/ubuntu](https://gallery.ecr.aws/andreswebs/ubuntu) |
| [docker.io/alpine](https://hub.docker.com/_/alpine)                                    | [public.ecr.aws/andreswebs/alpine](https://gallery.ecr.aws/andreswebs/alpine) |

## Authors

**Andre Silva** - [@andreswebs](https://github.com/andreswebs)

## License

This project is licensed under the [Unlicense](UNLICENSE.md).
