# Yallin's nginx-brotli Heroku Buildpack

Nginx-brotli-buildpack inside a dyno and runs NGINX per your configuration.

## Versions

* Nginx Brotli: https://github.com/google/ngx_brotli/tree/v1.0.0rc
* Heroku Stack: heroku-18

##  Required
* heroku/php: https://github.com/heroku/heroku-buildpack-php

## Usage

Install the `heroku/php` or make sure that this pack is installed:

    $ heroku buildpacks:set heroku/php
Or to use the master branch from GitHub instead:
    
    $ heroku buildpacks:set https://github.com/heroku/heroku-buildpack-php

Install the brotli buildpack:

    $ heroku buildpacks:set https://github.com/seyallin/heroku-brotli-nginx
    
  
    