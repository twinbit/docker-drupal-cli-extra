![Docker + Drupal](https://raw.githubusercontent.com/twinbit/drupal-docker-env/master/src/dde.png)

## Drupal Docker CLI extra ruby packages

Packages:
 - PHP 5.5 CLI
 - Composer + packages
    - "phing/phing": "2.7.*",
    - "drupal/phing-drush-task": "1.0",
    - "drush/drush": "6.*",
    - "pear/console_table": "1.1.5",
    - "squizlabs/php_codesniffer": "1.5.*",
    - "phpmd/phpmd": "1.5.*",
    - "drupal/coder": "7.2.*",
    - "sebastian/phpcpd": "*"
 - Drush 6.2
 - Mysql client 5.5
 - Mailcatcher 0.5.12
 - Ruby packages
   - 'sass', '~> 3.2.10'
   - 'sass-globbing', '~> 1.1.0'
   - 'compass', '~> 0.12.2'
   - 'compass-validator', '~> 3.0.1'
   - 'compass-normalize', '~> 1.4.3'
   - 'compass-rgbapng', '~> 0.2.1'
   - 'susy', '~> 1.0.9'
   - 'singularitygs', '~> 1.1.2'
   - 'toolkit', '~> 1.3.7'
   - 'breakpoint', '~> 2.0.6'
   - 'oily_png', '~> 1.1.0'
   - 'css_parser', '~> 1.3.4'
   - 'guard', '~> 1.8.2'
   - 'guard-compass', '~> 0.0.8'
   - 'guard-shell', '~> 0.5.1'
   - 'guard-livereload', '~> 1.4.0'
   - 'yajl-ruby', '~> 1.1.0'
   - 'rb-inotify', '~> 0.9', :require => false
   - 'rb-fsevent', :require => false
   - 'rb-fchange', :require => false


An automated build for this repo is available on the [Docker Hub](https://registry.hub.docker.com/u/twinbit).

This image is intended to be used in conjuction with the other images of the drupal docker stack:

- [twinbit/docker-drupal-data](https://github.com/twinbit/docker-drupal-data)
- [twinbit/docker-drupal-cli](https://github.com/twinbit/docker-drupal-cli)
- [twinbit/docker-drupal-mailcatcher](https://github.com/twinbit/docker-drupal-mailcatcher)
- [twinbit/docker-drupal-mysql](https://github.com/twinbit/docker-drupal-mysql)
- [twinbit/docker-drupal-nginx](https://github.com/twinbit/docker-drupal-nginx)
- [twinbit/docker-drupal-solr](https://github.com/twinbit/docker-drupal-solr)
- [twinbit/docker-drupal-php](https://github.com/twinbit/docker-drupal-php)

