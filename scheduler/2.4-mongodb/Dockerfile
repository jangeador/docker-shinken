FROM pockost/shinken:2.4-mongodb-base
MAINTAINER Romain THERRAT

EXPOSE 7768

ENTRYPOINT ["/usr/bin/shinken-scheduler", "-c", "/etc/shinken/daemons/schedulerd.ini"]
