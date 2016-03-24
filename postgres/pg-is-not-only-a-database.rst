==================================
PostgresQL is not only a database
==================================
.. contents::

Presentation
=============
- aRkadeFR, first talk, py developer and to developer,
  Using Django ORM! But carefuly :D
- The PostgresQL environment (setup, configuration, container?, chiffrement?)
- The administration commands (all pg_* commands)
- The environment as a developer (editor, debug…)

Installation
=============
- How to install, where? (hardware, disk, partition, network…)
- Authentication
- Containerisation

Maintenance
============
- CLI command
.. code-block::

    Ver Cluster Port Status Owner    Data directory               Log file
    9.1 main    5433 down   postgres /var/lib/postgresql/9.1/main /var/log/postgresql/postgresql-9.1-main.log
    9.4 main    5432 online postgres /var/lib/postgresql/9.4/main /var/log/postgresql/postgresql-9.4-main.log

- Upgrade (pg_clusterupgrade)

Environment
============
- psql, with psqlrc, with your editor (help and all "``\``" command, "``\ef``")
- community (dba.stackexchange, irc, meetup…)

Interact with your code
============
- ORM? Django one yes but not 100%

References
=======================================
[1] http://www.craigkerstiens.com/2013/02/21/more-out-of-psql/
