# Dockerised MySQL monitoring

Composition of several Docker images prepared to work in tandem for monitoring
MySQL server(s).

## Install

Clone repository. Copy file `./collectd/collectd.conf.sample` to
`./collectd/collectd.conf` and edit parameters accordingly. See 
[collectd MySQL plugin](https://collectd.org/wiki/index.php/Plugin:MySQL) 
configuration for more.

## Run

Run setup by executing
```
docker-compose up
```

