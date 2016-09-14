Role Name
=========

Install certbot and letsencrypt and generates SSL/TLS certificate with auto renew property.


Role Variables
--------------

    user_name: _#Name of OS user_
    domain: _#Domain to generate certificate, without WWW_
    www_domain: _#Domain to generate certificate, with WWW_
    admin_email: _#Email for certificate_
    server_path: _#The path of your webroot (Root path of your web application where letsencrypt will challenge your server)_
    

License
-------

MIT


Author Information
------------------

https://github.com/andrebonna
