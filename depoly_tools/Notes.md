## Configure new website

# Needed Package
* Nginx
* Python3.6+ Pip
* virtualenv
    * 
* Git
* Update SQLite3 > 3.8

# Nginx Configure
* Reference nginx.template.conf, replace SITENAME.

# System Service
* Reference gunicorn_systemd.template.service, replace SITENAME.

# Floder Struct
    /home/sites
        /database
        /source
        /static
        /virtualenv