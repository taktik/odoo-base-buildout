# odoo-base-buildout

You will find here some example of base configuration files to bootstrap Odoo.
To do so, launch bootstrap.sh:

    ./bootstrap.sh

It will download the boostrap.py file.
Once your buildout.cfg is ready (based on buildout-xx.cfg), you can bootstrap:

    python bootstrap.py
    
Then, build the recipe:

    ./bin/buildout
