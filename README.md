# mirror-images

Mirror images to Amazon ECR Public.

## Configuration

Create a public ECR repository:

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
| [docker.io/atmoz/sftp](https://hub.docker.com/r/atmoz/sftp)                                    | [public.ecr.aws/andreswebs/sftp](https://gallery.ecr.aws/andreswebs/sftp) |

## Authors

**Andre Silva** - [@andreswebs](https://github.com/andreswebs)

## License

This project is licensed under the [Unlicense](UNLICENSE.md).
