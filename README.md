# Zeppelin

A `CentOS:7` based `Spark 1.6` and [Zeppelin](http://zeppelin.apache.org/) Docker container

This image is large and comes built with ALL the default interpreters that come
with Zeppelin.

## Simple Usage
To start Zeppelin, pull the latest image and run the container:
```bash
docker pull samvantran/centos7-zeppelin06-spark16
docker run -d -p 8080:8080 samvantran/centos7-zeppelin06-spark16
```

