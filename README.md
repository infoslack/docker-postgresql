docker-postgresql
=================

    $ docker run -d -p 5432:5432 -e POSTGRESQL_USER=test -e POSTGRESQL_PASS=test123 -e POSTGRESQL_DB=test ex_postgresql
    $ psql -h localhost -U test test
    Password for user test:
    psql (9.3.3, server 9.3.5)
    SSL connection (cipher: DHE-RSA-AES256-SHA, bits: 256)
    Type "help" for help.

    test=#

Original here: [https://github.com/orchardup/docker-postgresql](https://github.com/orchardup/docker-postgresql)
