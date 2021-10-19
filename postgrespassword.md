# Postgres Password set for odoo

## Getting Started

You can do it with the following command:

```sh
sudo su postgres
psql
*alter user odoo with password admin;
```
#and go to odoo config file and write (db_password = admin,db_host = localhost,
db_port = 5432)
