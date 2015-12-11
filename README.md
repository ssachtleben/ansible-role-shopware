# Ansible Shopware Role

This ansible role will download and install a Shopware shop.

## Variables

* ``shopware_version``: shopware version to install (string, default: ``latest``)
* ``shopware_root``: Configure shopware root directory (string, default: ``/var/www/shopware``)
* ``shopware_webuser``: Service user to run shopware with (string, default: ``www-data``)
* ``shopware_webgroup``: Service group for the ``shopware_user`` service user (string, default: ``www-data``)

## Configuration

Configurate shopware installation with the following defaults:

```
shopware_config:
	shop_url: "http://shopware.local/"
   db_host: "localhost"
   db_name: "shopware"
   db_user: "root"
   db_pass: "root"
   admin_email: "admin@email.com"
   admin_pass: "password"
```

## License

Apache Version 2.0