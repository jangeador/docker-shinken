FROM pockost/shinken:2.4-mongodb-base
MAINTAINER Romain THERRAT

EXPOSE 7771

ENTRYPOINT ["/usr/bin/shinken-poller", "-c", "/etc/shinken/daemons/pollerd.ini"]
