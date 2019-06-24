# docker-compose


```shell
export CDT_DOCS=<cdt-docs-dir>"
cd $CDT_DOCS/docker-compose
```

### local development

- by default, *latest* tag is being used for production deployment. You may need
  to find out the version [on docker
  hub](https://cloud.docker.com/repository/list), and use them.

```yaml
  cdt-be:
    image: eightwelve/cdt-be:master-20190621204218
```

- now you can run whichever service you would like:

```shell
docker-compose up -d cdt-web
```

- visit [localhost:6015](localhost:6015) on browser
