# ydim

* https://github.com/zdavatz/ydim.git

## DESCRIPTION:

ywesee distributed invoice manager, Ruby

## INSTALL:

* gem install ydim

If you have a non standard path of postgres use something like

* gem install pg -- --with-pg-config=/usr/local/pgsql-10.1/bin/pg_config

Or if you are using bundler

* bundle config build.pg --with-pg-config=/usr/local/pgsql-10.1/bin/pg_config
* bundle install

## Migrating an old database

An old database can be migrated to UTF-8 by calling

    bundle install --path vendor
    bundle exec bin/migrate_to_utf_8

## DEVELOPERS:

* Masaomi Hatakeyama
* Zeno R.R. Davatz
* Hannes Wyss (up to Version 1.0)
* Niklaus Giger (ported to Ruby 2.3.0)

## LICENSE:

* GPLv2
