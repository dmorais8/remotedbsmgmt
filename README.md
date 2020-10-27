# remotedbsmgmt

This project aims to perform a database creation remotely using the ElephantSQL host.

The project consists of 3 scripts.

* remotedb.py: This script consumes the elephantSQL api rest to perform operations to create and delete database instances.
* remotehost.py: This script obtains postgreSQL dumps from a given host with GNU / Linux using SSH / SCP connections.
* pg_restore.py: This script performed the restore of the dump, obtained with remotehost.py, in a database instance hosted on ElephantSQL.
