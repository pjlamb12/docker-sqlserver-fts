# pjlamb12/sqlserver-fts

This is the repo for the [pjlamb12/sqlserver-fts](https://hub.docker.com/repository/docker/pjlamb12/sqlserver-fts) Docker image. The image is based on the Ubuntu 16.04 image, with [SQL Server for Linux](https://github.com/Microsoft/mssql-docker) running. It is different than the official image from Microsft because it enables full text search as well.

To use the image:

```bash
docker pull pjlamb12/sqlserver-fts
```

Or, in the `Dockerfile`:

```Dockerfile
FROM pjlamb12/sqlserver-fts
```

Contributions welcome, with the plan to push a new version each time a new version of SQL Server for Linux is released.
