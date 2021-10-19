# Postgres Password set for odoo

## Getting Started

You can do it with the following command:

```sh
sudo -u postgres psql -c "ALTER USER odoo15 PASSWORD 'odoo15';"
```
#and go to odoo config file and write (db_password = admin,db_host = localhost,
db_port = 5432)
```sh
[options]
; This is the password that allows database operations:
admin_passwd = admin@123
db_host = localhost
db_port = 5432 
db_user = odoo15
db_password = odoo15
addons_path = /opt/odoo15/odoo/addons,/opt/odoo15/odoo-custom-addons
;logfile = /var/log/odoo/odoo15.log
```

