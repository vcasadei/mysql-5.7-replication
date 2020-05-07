FROM percona/percona-server:5.7.26

COPY my.cnf /etc/my.cnf
COPY primary.cnf /etc/my.cnf.d/docker.cnf
COPY --chown=mysql:mysql empty.log /var/log/mysql/mysql-bin.log
COPY --chown=mysql:mysql empty.log /var/log/mysql/error.log
COPY --chown=mysql:mysql empty.log /var/log/mysql/mysql-slow.log
COPY --chown=mysql:mysql empty.log /var/log/mysql/all-queries.log